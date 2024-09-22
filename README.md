CREATE TABLE IF NOT EXISTS stpauls (
    id INT AUTO_INCREMENT PRIMARY KEY,
    first_name VARCHAR(100) NOT NULL,
    second_name VARCHAR(100) NOT NULL,
    surname VARCHAR(100) NOT NULL,
    email VARCHAR(255) NOT NULL UNIQUE,
    phone_number VARCHAR(15) NOT NULL,
    course_done VARCHAR(100) NOT NULL,
    year_of_study VARCHAR(10) NOT NULL,
    password VARCHAR(255) NOT NULL,
    image LONGTEXT DEFAULT NULL,
    last_email_sent DATETIME DEFAULT NULL -- New column to store the timestamp of the last sent email
);
  run this sql in phpmy admin to create table 

  made with ❤ by Peter Wanguya
