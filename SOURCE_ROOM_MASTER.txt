CREATE TABLE ROOM_MASTER_HOSPITALITY (
    RoomID NUMBER,
    RoomType VARCHAR2(50),
    FloorNumber NUMBER,
    BedType VARCHAR2(50),
    BaseRate NUMBER(10,2),
    RoomStatus VARCHAR2(50),
    MaxOccupancy NUMBER,
    Amenities VARCHAR2(500),
    LastCleanedDate DATE
);
INSERT INTO ROOM_MASTER_HOSPITALITY (RoomID, RoomType, FloorNumber, BedType, BaseRate, RoomStatus, MaxOccupancy, Amenities, LastCleanedDate) VALUES (101, 'Deluxe', 1, 'Queen', 3500, 'Occupied', 2, 'WiFi, AC, TV', TO_DATE('2024-05-05','YYYY-MM-DD'));
INSERT INTO ROOM_MASTER_HOSPITALITY (RoomID, RoomType, FloorNumber, BedType, BaseRate, RoomStatus, MaxOccupancy, Amenities, LastCleanedDate) VALUES (102, 'Suite', 1, 'King', 5000, 'Occupied', 4, 'WiFi, AC, TV, MiniBar', TO_DATE('2024-05-07','YYYY-MM-DD'));
INSERT INTO ROOM_MASTER_HOSPITALITY (RoomID, RoomType, FloorNumber, BedType, BaseRate, RoomStatus, MaxOccupancy, Amenities, LastCleanedDate) VALUES (201, 'Standard', 2, 'Double', 2500, 'Occupied', 2, 'WiFi, TV', TO_DATE('2024-05-05','YYYY-MM-DD'));
INSERT INTO ROOM_MASTER_HOSPITALITY (RoomID, RoomType, FloorNumber, BedType, BaseRate, RoomStatus, MaxOccupancy, Amenities, LastCleanedDate) VALUES (202, 'Standard', 2, 'Double', 2500, 'Available', 2, 'WiFi, TV', TO_DATE('2026-04-14','YYYY-MM-DD'));