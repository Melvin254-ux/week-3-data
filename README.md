# week-3-data
assignment
Question 1: Create the student Table
SQL
CREATE TABLE student (
    id INTEGER PRIMARY KEY,
    fullName TEXT(100),
    age INTEGER
);
Question 2: Insert at Least 3 Records into the student Table
SQL
INSERT INTO student (id, fullName, age) VALUES (1, 'John Doe', 18);
INSERT INTO student (id, fullName, age) VALUES (2, 'Jane Smith', 19);
INSERT INTO student (id, fullName, age) VALUES (3, 'Emily Johnson', 21);
Question 3: Update the Age of the Student with ID 2 to 20
SQL
UPDATE student
SET age = 20
WHERE id = 2;
These statements will create the student table, insert three records into it, and then update the age of the student with ID 2.
