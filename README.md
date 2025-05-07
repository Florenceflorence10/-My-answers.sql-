# -My-answers.sql-

-- Dropping an index
DROP INDEX IdxPhone ON customers;

-- Creating a user
CREATE USER 'bob'@'localhost' IDENTIFIED BY 'S$cu3r3!';

-- Granting privileges
GRANT INSERT ON salesDB.* TO 'bob'@'localhost';

-- Changing password
ALTER USER 'bob'@'localhost' IDENTIFIED BY 'P$55!23';
