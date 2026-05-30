CREATE TABLE CHECKIN_CHECKOUT_HOSPITALITY (
    StayID NUMBER,
    GuestID NUMBER,
    RoomID NUMBER,
    CheckinDateTime TIMESTAMP,
    CheckoutDateTime TIMESTAMP,
    BookingSource VARCHAR2(50),
    NumberOfGuests NUMBER,
    RoomRate NUMBER(10,2),
    ExtraCharges NUMBER(10,2),
    DiscountAmount NUMBER(10,2),
    TotalAmount NUMBER(10,2),
    PaymentMode VARCHAR2(50),
    Status VARCHAR2(50),
    LastUpdated DATE
);
