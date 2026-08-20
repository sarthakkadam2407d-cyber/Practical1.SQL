Student, Teacher and Course Database 📌 Project Overview This is a simple SQL database practice project containing three tables:

student — stores student information and marks teacher — stores teacher information and subjects course — stores course information and fees The project demonstrates basic SQL operations such as:

Creating tables using CREATE TABLE Adding records using INSERT INTO Retrieving records using SELECT Using comments to organize SQL code 🗂️ Database Structure Student ├── studentId ├── name └── marks

Teacher ├── teacherId ├── name └── subject

Course ├── courseId ├── courseName └── fee

There are currently no foreign-key relationships between the three tables.

🧑‍🎓 Student Table The student table stores student details.

Column Data Type Description studentId INT Student ID name VARCHAR(20) Student name marks INT Student marks

Sample Data Student ID Name Marks 1 rahul 56 2 cattt 59 3 meoww 58

👨‍🏫 Teacher Table The teacher table stores teacher information.

Column Data Type Description teacherId INT Teacher ID name VARCHAR(20) Teacher name subject VARCHAR(20) Subject taught

Sample Data Teacher ID Name Subject 1 Asha Math 2 Ravi Science

📚 Course Table The course table stores available courses and their fees.

Column Data Type Description courseId INT Course ID courseName VARCHAR(20) Course name fee INT Course fee

Sample Data Course ID Course Name Fee 101 Java 5000 102 SQL 3000

🔍 Fetching Data The project uses SELECT statements to display all records:

SELECT * FROM student; SELECT * FROM teacher; SELECT * FROM course;

SELECT * retrieves all columns and rows from the specified table.

🚀 How to Run Open MySQL Workbench, MySQL Command Line, or another SQL editor. Run the CREATE TABLE statements. Execute the INSERT INTO statements to add sample records. Execute the SELECT statements to view the data. Expected Tables student teacher course

🎯 Learning Objectives This project is useful for beginners learning:

SQL syntax Table creation Data insertion Data retrieval Basic database structure CREATE TABLE INSERT INTO SELECT SQL comments 🛠️ Technologies Database: MySQL Language: SQL Project Type: Beginner SQL Practice Project ⚠️ Possible Improvements For a more realistic database design, the tables could be improved by adding:

PRIMARY KEY constraints NOT NULL constraints UNIQUE constraints FOREIGN KEY relationships A relationship between students and courses A relationship between teachers and courses For example:

studentId INT PRIMARY KEY

could be used to uniquely identify each student.

📄 License This project is intended for educational and learning purposes.
