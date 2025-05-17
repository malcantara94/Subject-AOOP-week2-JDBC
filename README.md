# Subject-AOOP-week2-JDBC



/* code for mysql workbench:

CREATE DATABASE IF NOT EXISTS habit_tracker_db;
USE habit_tracker_db;

CREATE TABLE IF NOT EXISTS habit (
    id INT AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(100) NOT NULL,
    descriptionPRIMARY TEXT
);

CREATE TABLE IF NOT EXISTS habit_log (
    id INT AUTO_INCREMENT PRIMARY KEY,
    habit_id INT NOT NULL,
    date_logged DATE NOT NULL,
    FOREIGN KEY (habit_id) REFERENCES habit(id) ON DELETE CASCADE
);


*/
