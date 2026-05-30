# Hospitality Analytics Project

## Overview

This project was developed using Informatica Intelligent Cloud Services (IICS) and Oracle Database.

The objective is to process hospitality data, validate records, calculate revenue information, and generate analytics-ready data for reporting.

---

## Source Tables

### Guest Master

Contains guest information.

### Room Master

Contains room details.

### Check-In Check-Out

Contains guest stay transactions.

---

## Target Tables

### STG_GUEST_MASTER

Stores guest staging data.

### STG_ROOM_MASTER

Stores room staging data.

### FACT_GUEST_STAY

Stores final stay and revenue information.

### REJECT_STAY

Stores invalid records.

---

## Mappings

### 1. m_Load_STG_GUEST_MASTER

Loads guest data into staging.

Validation:

* AddressLine2 should not be null.

### 2. m_Load_STG_ROOM_MASTER

Loads room data into staging.

Validation:

* RoomType should not be null.

### 3. m_Load_FACT_GUEST_STAY

Main business mapping.

Functions:

* Guest Lookup
* Room Lookup
* Revenue Calculation
* Data Validation
* Reject Handling

---

## Main Business Logic

### Revenue Calculation

Final Amount = Room Rate + Extra Charges - Discount Amount

### Occupancy Status

CheckedIn → Occupied

Others → Available

---

## Data Quality

Invalid records are redirected to reject tables using Router transformations.

Examples:

* Missing Guest ID
* Missing Room ID
* Invalid Room Rate
* Missing Checkout Information

---

## Architecture

Source Tables

↓

Staging Layer

↓

Lookup & Validation

↓

Fact Table

↓

Power BI Dashboard

---

## Tools Used

* Informatica IICS
* Oracle SQL
* PL/SQL
* Power BI

---

## Project Outcome

* Data Integration
* Data Validation
* Revenue Analysis
* Occupancy Tracking
* Hospitality Reporting

---

## Author

Ananya S
