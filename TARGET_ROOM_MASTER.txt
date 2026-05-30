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