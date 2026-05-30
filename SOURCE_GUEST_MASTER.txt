CREATE TABLE GUEST_MASTER_HOSPITALITY (
    GuestID NUMBER,
    FirstName VARCHAR2(50),
    LastName VARCHAR2(50),
    Gender VARCHAR2(10),
    DateOfBirth DATE,
    Email VARCHAR2(100),
    PhoneNumber NUMBER(15),
    AddressLine1 VARCHAR2(200),
    AddressLine2 VARCHAR2(200),
    City VARCHAR2(50),
    State VARCHAR2(50),
    Country VARCHAR2(50),
    IDProofType VARCHAR2(50),
    IDProofNumber VARCHAR2(50),
    RegistrationDate DATE
);
INSERT ALL
INTO GUEST_MASTER_HOSPITALITY VALUES (1, 'Rahul', 'Khan', 'Male', TO_DATE('2004-02-25','YYYY-MM-DD'), 'rahul.khan1@example.com', 8590720650, '170 Ring Road', 'Floor 2', 'Kolkata', 'WB', 'India', 'PAN', 'KMIMU7423C', TO_DATE('2024-03-18','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (2, 'Sapna', 'Khan', 'Female', TO_DATE('1992-02-22','YYYY-MM-DD'), 'sapna.khan2@example.com', 6451671742, '188 Park St', NULL, 'Bhopal', 'MP', 'India', 'PAN', 'XQRTK4757D', TO_DATE('2024-03-19','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (3, 'Rohit', 'Vats', 'Male', TO_DATE('1999-10-18','YYYY-MM-DD'), 'rohit.vats3@example.com', 8359799329, '138 Ring Road', 'Tower 1', 'Gurugram', 'HR', 'India', 'Passport', 'P9708002', TO_DATE('2024-03-21','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (4, 'Priya', 'Pandey', 'Female', TO_DATE('1975-04-21','YYYY-MM-DD'), 'priya.pandey4@example.com', 6313080912, '34 Link Road', 'Opp. Mall', 'Ahmedabad', 'GJ', 'India', 'Passport', 'R8717220', TO_DATE('2024-03-21','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (5, 'Kiran', 'Saxena', 'Female', TO_DATE('1985-09-05','YYYY-MM-DD'), 'kiran.saxena5@example.com', 6991201864, '88 Link Road', 'Block A', 'Kolkata', 'WB', 'India', 'Passport', 'S3608291', TO_DATE('2024-03-14','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (6, 'Suhail', 'Pandey', 'Male', TO_DATE('2004-10-02','YYYY-MM-DD'), 'suhail.pandey6@example.com', 7945538330, '151 Sector 62', 'Phase II', 'Gurugram', 'HR', 'India', 'Aadhaar', '3.63E+11', TO_DATE('2024-03-24','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (7, 'Neha', 'Das', 'Female', TO_DATE('1969-11-26','YYYY-MM-DD'), 'neha.das7@example.com', 6215305809, '157 Marine Drive', NULL, 'Mumbai', 'MH', 'India', 'VoterID', 'MH4034239', TO_DATE('2024-03-25','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (8, 'Rahul', 'Shah', 'Male', TO_DATE('1995-12-06','YYYY-MM-DD'), 'rahul.shah8@example.com', 7389158833, '138 MG Road', 'Apt 4B', 'Bhopal', 'MP', 'India', 'VoterID', 'MP5297717', TO_DATE('2024-03-26','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (9, 'Pallavi', 'Bijaoui', 'Female', TO_DATE('1975-05-22','YYYY-MM-DD'), 'pallavi.bijaoui9@example.com', 8520483318, '32 Garden Road', 'Block A', 'Hyderabad', 'TG', 'India', 'Passport', 'Y3977182', TO_DATE('2024-03-27','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (10, 'Neha', 'Bijaoui', 'Female', TO_DATE('1978-01-27','YYYY-MM-DD'), 'neha.bijaoui10@example.com', 7453701401, '33 Marine Drive', NULL, 'Pune', 'MH', 'India', 'PAN', 'GCUKC4250Q', TO_DATE('2024-03-28','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (11, 'Harsh', 'Reddy', 'Male', TO_DATE('1993-12-19','YYYY-MM-DD'), 'harsh.reddy11@example.com', 7362524832, '152 FC Road', 'Apt 4B', 'Kolkata', 'WB', 'India', 'VoterID', 'WB3212883', TO_DATE('2024-03-29','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (12, 'Priya', 'Verma', 'Female', TO_DATE('1966-07-05','YYYY-MM-DD'), 'priya.verma12@example.com', 7917485791, '17 FC Road', 'Block A', 'Noida', 'UP', 'India', 'Passport', 'P7127903', TO_DATE('2024-03-30','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (13, 'Kiran', 'Suryavanshi', 'Female', TO_DATE('1959-06-20','YYYY-MM-DD'), 'kiran.suryavanshi13@example.com', 6673841380, '129 Link Road', 'Suite 305', 'Pune', 'MH', 'India', 'PAN', 'GJUNA2918G', TO_DATE('2024-03-31','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (14, 'Kavya', 'Yadav', 'Female', TO_DATE('1965-01-12','YYYY-MM-DD'), 'kavya.yadav14@example.com', 6948257062, '115 FC Road', 'Floor 2', 'Lucknow', 'UP', 'India', 'VoterID', 'UP1750335', TO_DATE('2024-04-01','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (15, 'Meera', 'Vats', 'Female', TO_DATE('1960-12-19','YYYY-MM-DD'), 'meera.vats15@example.com', 7650152837, '9 Brigade Rd', NULL, 'Bengaluru', 'KA', 'India', 'Passport', 'D5540765', TO_DATE('2024-04-02','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (16, 'Vaibhav', 'Singh', 'Male', TO_DATE('1973-03-09','YYYY-MM-DD'), 'vaibhav.singh16@example.com', 7949445184, '159 MG Road', 'Phase II', 'Gurugram', 'HR', 'India', 'Aadhaar', '5.93E+11', TO_DATE('2024-04-03','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (17, 'Karan', 'Singh', 'Male', TO_DATE('1981-04-28','YYYY-MM-DD'), 'karan.singh17@example.com', 6023788395, '106 Garden Road', 'Apt 4B', 'Kolkata', 'WB', 'India', 'VoterID', 'WB1675856', TO_DATE('2024-04-04','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (18, 'Rohit', 'Patel', 'Male', TO_DATE('1966-04-14','YYYY-MM-DD'), 'rohit.patel18@example.com', 7134536040, '136 MG Road', 'Floor 2', 'Pune', 'MH', 'India', 'PAN', 'NPKFY1251G', TO_DATE('2024-04-05','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (19, 'Sapna', 'Yadav', 'Female', TO_DATE('2002-01-02','YYYY-MM-DD'), 'sapna.yadav19@example.com', 6468854413, '61 Marine Drive', 'Near Metro', 'Indore', 'MP', 'India', 'Passport', 'A1844817', TO_DATE('2024-04-06','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (20, 'Nisha', 'Khan', 'Female', TO_DATE('1986-06-15','YYYY-MM-DD'), 'nisha.khan20@example.com', 6249803566, '25 Garden Road', 'Block A', 'Delhi', 'DL', 'India', 'VoterID', 'DL3146053', TO_DATE('2024-04-07','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (21, 'Girdhar', 'Khan', 'Male', TO_DATE('1958-07-28','YYYY-MM-DD'), 'girdhar.khan21@example.com', 8988791683, '135 MG Road', 'Near Metro', 'Jaipur', 'RJ', 'India', 'PAN', 'CQEOE7883J', TO_DATE('2024-04-08','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (22, 'Manish', 'Kapoor', 'Male', TO_DATE('1971-04-07','YYYY-MM-DD'), 'manish.kapoor22@example.com', 6110130494, '129 Garden Road', 'Tower 1', 'Lucknow', 'UP', 'India', 'Passport', 'S1989483', TO_DATE('2024-04-09','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (23, 'Govinda', 'Yadav', 'Male', TO_DATE('1959-09-06','YYYY-MM-DD'), 'govinda.yadav23@example.com', 6863212905, '9 Ring Road', NULL, 'Jaipur', 'RJ', 'India', 'PAN', 'QMUUY9694J', TO_DATE('2024-04-10','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (24, 'Nisha', 'Verma', 'Female', TO_DATE('1991-11-26','YYYY-MM-DD'), 'nisha.verma24@example.com', 8327519620, '65 Park St', 'Opp. Mall', 'Lucknow', 'UP', 'India', 'Passport', 'A1523221', TO_DATE('2024-04-11','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (25, 'Aditi', 'Shah', 'Female', TO_DATE('2006-09-09','YYYY-MM-DD'), 'aditi.shah25@example.com', 8236671509, '89 Link Road', 'Phase II', 'Mumbai', 'MH', 'India', 'Aadhaar', '92643168730', TO_DATE('2024-04-12','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (26, 'Janardan', 'Singh', 'Male', TO_DATE('1969-11-11','YYYY-MM-DD'), 'janardan.singh26@example.com', 7556660034, '64 Marine Drive', 'Apt 4B', 'Ahmedabad', 'GJ', 'India', 'Passport', 'N7362810', TO_DATE('2024-04-13','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (27, 'Janardan', 'Yadav', 'Male', TO_DATE('1989-11-11','YYYY-MM-DD'), 'janardan.yadav27@example.com', 6475595022, '159 Garden Road', 'Apt 4B', 'Indore', 'MP', 'India', 'VoterID', 'MP1868754', TO_DATE('2024-04-14','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (28, 'Divya', 'Sahu', 'Female', TO_DATE('1992-10-18','YYYY-MM-DD'), 'divya.sahu28@example.com', 6636692922, '120 Ring Road', NULL, 'Mumbai', 'MH', 'India', 'Passport', 'J3241209', TO_DATE('2024-04-15','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (29, 'Aditi', 'Shah', 'Female', TO_DATE('1986-03-27','YYYY-MM-DD'), 'aditi.shah29@example.com', 7439677454, '105 Link Road', 'Apt 4B', 'Chennai', 'TN', 'India', 'PAN', 'FOUGJ0626U', TO_DATE('2024-04-16','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (30, 'Nikhil', 'Sahu', 'Male', TO_DATE('1994-06-22','YYYY-MM-DD'), 'nikhil.sahu30@example.com', 6985723921, '119 Nehru Place', 'Block A', 'Indore', 'MP', 'India', 'Passport', 'Z4115248', TO_DATE('2024-04-17','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (31, 'Isha', 'Pandey', 'Female', TO_DATE('1995-03-01','YYYY-MM-DD'), 'isha.pandey31@example.com', 9158885210, '67 Garden Road', 'Tower 1', 'Indore', 'MP', 'India', 'VoterID', 'MP7544466', TO_DATE('2024-04-18','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (32, 'Neha', 'Suryavanshi', 'Female', TO_DATE('1981-01-05','YYYY-MM-DD'), 'neha.suryavanshi32@example.com', 8301707782, '78 Ring Road', 'Near Metro', 'Gurugram', 'HR', 'India', 'PAN', 'HIFQZ5894J', TO_DATE('2024-04-19','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (33, 'Prashant', 'Das', 'Male', TO_DATE('1960-05-23','YYYY-MM-DD'), 'prashant.das33@example.com', 9554928438, '103 Nehru Place', 'Near Metro', 'Lucknow', 'UP', 'India', 'Passport', 'N6423880', TO_DATE('2024-04-20','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (34, 'Shreya', 'Gupta', 'Female', TO_DATE('1977-09-26','YYYY-MM-DD'), 'shreya.gupta34@example.com', 9843774045, '43 Brigade Rd', 'Opp. Mall', 'Mumbai', 'MH', 'India', 'Aadhaar', '2.82E+11', TO_DATE('2024-04-21','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (35, 'Arjun', 'Patel', 'Male', TO_DATE('1978-02-10','YYYY-MM-DD'), 'arjun.patel35@example.com', 7636378793, '33 Link Road', 'Floor 2', 'Noida', 'UP', 'India', 'Passport', 'U4954327', TO_DATE('2024-04-22','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (36, 'Vaibhav', 'Sahu', 'Male', TO_DATE('2003-01-27','YYYY-MM-DD'), 'vaibhav.sahu36@example.com', 8019761766, '39 Marine Drive', 'Near Metro', 'Bhopal', 'MP', 'India', 'PAN', 'ENFGW5653Y', TO_DATE('2024-04-23','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (37, 'Meera', 'Kumar', 'Female', TO_DATE('1967-07-31','YYYY-MM-DD'), 'meera.kumar37@example.com', 6621641284, '140 Brigade Rd', 'Tower 1', 'Kolkata', 'WB', 'India', 'PAN', 'BDWJZ6065R', TO_DATE('2024-04-24','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (38, 'Kavya', 'Sharma', 'Female', TO_DATE('1983-11-10','YYYY-MM-DD'), 'kavya.sharma38@example.com', 7033445052, '9 MG Road', 'Apt 4B', 'Bengaluru', 'KA', 'India', 'Aadhaar', '3.95E+11', TO_DATE('2024-04-25','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (39, 'Karan', 'Sharma', 'Male', TO_DATE('1990-01-07','YYYY-MM-DD'), 'karan.sharma39@example.com', 8031481687, '125 Park St', 'Suite 305', 'Lucknow', 'UP', 'India', 'Aadhaar', '2.31E+11', TO_DATE('2024-04-26','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (40, 'Swati', 'Reddy', 'Female', TO_DATE('1978-12-19','YYYY-MM-DD'), 'swati.reddy40@example.com', 9488216507, '83 Hitech City Rd', NULL, 'Kolkata', 'WB', 'India', 'Passport', 'F6772443', TO_DATE('2024-04-27','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (41, 'Vikram', 'Vats', 'Male', TO_DATE('1991-09-09','YYYY-MM-DD'), 'vikram.vats41@example.com', 6806726184, '43 Sector 62', 'Opp. Mall', 'Pune', 'MH', 'India', 'Aadhaar', '4.67E+11', TO_DATE('2024-04-28','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (42, 'Aditi', 'Verma', 'Female', TO_DATE('2005-01-10','YYYY-MM-DD'), 'aditi.verma42@example.com', 9163633040, '46 Park St', NULL, 'Hyderabad', 'TG', 'India', 'PAN', 'FCYEZ4179Q', TO_DATE('2024-04-29','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (43, 'Aditi', 'Singh', 'Female', TO_DATE('1970-07-08','YYYY-MM-DD'), 'aditi.singh43@example.com', 7066787233, '153 Salt Lake Ave', 'Apt 4B', 'Mumbai', 'MH', 'India', 'PAN', 'WHSJD7404T', TO_DATE('2024-04-30','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (44, 'Neha', 'Khan', 'Female', TO_DATE('2005-10-27','YYYY-MM-DD'), 'neha.khan44@example.com', 6061790884, '85 Nehru Place', 'Suite 305', 'Chennai', 'TN', 'India', 'VoterID', 'TN7442712', TO_DATE('2024-05-01','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (45, 'Rahul', 'Shah', 'Male', TO_DATE('2003-04-19','YYYY-MM-DD'), 'rahul.shah45@example.com', 6930599498, '67 Sector 62', NULL, 'Pune', 'MH', 'India', 'VoterID', 'MH9565387', TO_DATE('2024-05-01','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (46, 'Priya', 'Gupta', 'Female', TO_DATE('1987-08-28','YYYY-MM-DD'), 'priya.gupta46@example.com', 9371286781, '123 Brigade Rd', 'Suite 305', 'Kolkata', 'WB', 'India', 'Passport', 'A2730485', TO_DATE('2024-05-01','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (47, 'Girdhar', 'Gupta', 'Male', TO_DATE('1974-05-29','YYYY-MM-DD'), 'girdhar.gupta47@example.com', 6969988130, '185 Park St', 'Apt 4B', 'Kochi', 'KL', 'India', 'VoterID', 'KL4859582', TO_DATE('2024-05-04','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (48, 'Riya', 'Shah', 'Female', TO_DATE('1994-02-15','YYYY-MM-DD'), 'riya.shah48@example.com', 7222419355, '117 Sector 62', 'Block A', 'Kochi', 'KL', 'India', 'Aadhaar', '8.36E+11', TO_DATE('2026-02-04','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (49, 'Isha', 'Patel', 'Female', TO_DATE('1977-11-13','YYYY-MM-DD'), 'isha.patel49@example.com', 8963322304, '43 FC Road', NULL, 'Jaipur', 'RJ', 'India', 'VoterID', 'RJ8271337', TO_DATE('2026-04-02','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (50, 'Meera', 'Mishra', 'Female', TO_DATE('1981-05-21','YYYY-MM-DD'), 'meera.mishra50@example.com', 7366804325, '85 Salt Lake Ave', 'Apt 4B', 'Bhopal', 'MP', 'India', 'VoterID', 'MP1114298', TO_DATE('2026-04-09','YYYY-MM-DD'))
INTO GUEST_MASTER_HOSPITALITY VALUES (48, 'Riya', 'Shah', 'Female', TO_DATE('1994-02-15','YYYY-MM-DD'), 'riya.shah48@example.com', 7222419355, '117 Sector 62', 'Block A', 'Kochi', 'KL', 'India', 'Aadhaar', '8.36E+11', TO_DATE('2026-02-04','YYYY-MM-DD'))
SELECT * FROM DUAL;