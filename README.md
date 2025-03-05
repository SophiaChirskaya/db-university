db_university

Q1
SELECT * FROM students
WHERE YEAR (date_of_birth) = 1990

Q2
SELECT * FROM courses
WHERE CFU > 10

Q3
SELECT * FROM students
WHERE YEAR (date_of_birth) > 1995

Q4
SELECT * FROM courses
WHERE year = 1 AND period = "I semestre"

Q5
SELECT * FROM exams
WHERE date = "2020-06-20" AND hour > 14

Q6
SELECT * FROM degrees
WHERE name LIKE "Corso di Laurea Magistrale%"

Q7
SELECT * FROM departments

Q8
SELECT * FROM teachers
WHERE phone IS NULL
