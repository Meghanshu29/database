create database assisgnment;
use assisgnment;
-- Create the Registration table
CREATE TABLE Registration (
    ID INT PRIMARY KEY AUTO_INCREMENT,
    Name VARCHAR(255) NOT NULL,
    Email VARCHAR(255) NOT NULL,
    DateOfBirth DATE
);

-- CRUD Operations

-- Create operation
INSERT INTO Registration (Name, Email, DateOfBirth) VALUES ('meghanshu jain', 'meghanshujain29@example.com', '2000-05-17');

-- Read operation
SELECT * FROM Registration;

-- Update operation
UPDATE Registration SET Email = 'meghanshujain29@example.com' WHERE ID = 1;

-- Delete operation
DELETE FROM Registration WHERE ID = 1;
-- Read operation
SELECT * FROM Registration;

