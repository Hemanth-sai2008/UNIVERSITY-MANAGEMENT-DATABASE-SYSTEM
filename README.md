# University Academic Management Database System

A DBMS capstone project that organizes university academic records in a relational database using MySQL.

**Aditya University · School of Computing · Department of Artificial Intelligence and Machine Learning**  
**Batch:** 8 | **Academic year:** 2026–2027

## Project overview

The system manages departments, students, faculty, courses, enrollments, examinations, and results. Related records are connected through primary and foreign keys to support consistent storage and academic reporting.

The project report covers requirement analysis, database design, an ER diagram, relational schemas, normalization up to Third Normal Form (3NF), and SQL implementation.

## Tools used

- MySQL 8.0
- MySQL Workbench
- SQL for database definition, data manipulation, and queries

## Database tables

| Table | Purpose |
| --- | --- |
| Department | Stores department information. |
| Student | Stores student details and department associations. |
| Faculty | Stores faculty details and department associations. |
| Course | Stores course details, credits, and faculty and department associations. |
| Enrollment | Records student enrollments in courses. |
| Exam | Stores examination details for courses. |
| Result | Records students' examination marks and grades. |

## Repository files

| File | Contents |
| --- | --- |
| [DBMS Review - 1.pptx](<DBMS Review - 1.pptx>) | Review 1 presentation. |
| [DBMS Reivew - 2.pptx](<DBMS Reivew - 2.pptx>) | Review 2 presentation. |
| [DBMS Report.docx](<DBMS Report.docx>) | Project documentation. |
| [DBMS_32_SQL_Queries.zip](DBMS_32_SQL_Queries.zip) | 32 SQL files extracted from Section 9 of the report, with the query text unchanged. |

## SQL queries

The ZIP contains files numbered `Q01.sql` through `Q32.sql`, covering:

- Data retrieval, filtering, sorting, and distinct values.
- Inner joins, left joins, and joins across multiple tables.
- Aggregate functions including `COUNT`, `AVG`, `MAX`, `MIN`, and `SUM`.
- Grouping and filtering groups using `GROUP BY` and `HAVING`.
- Create, read, update, and delete (CRUD) operations on student records.
- Views for consolidated student results and enrollments.

## How to use the SQL files

1. Download and extract `DBMS_32_SQL_Queries.zip`.
2. Open MySQL Workbench and connect to your MySQL server.
3. Prepare the project's database tables and sample data, then select that database as the default schema.
4. Open the required `.sql` file and execute it.
5. Review the result or execution message in MySQL Workbench.

The ZIP contains the 32 demonstration queries from Section 9. It does not include the complete database creation and sample-data scripts referenced in the report; these are prerequisites for running the queries.

Run `Q26.sql` through `Q29.sql` in order for the student CRUD demonstration. These queries insert, retrieve, update, and delete the demonstration student. Run `Q30.sql` before `Q31.sql`, because Q31 queries the view created by Q30.

## Team members

| Roll number | Name |
| --- | --- |
| 25B11AI494 | K. Hemanth Sai Venkata Vidya Sagar |
| 25B11AI281 | M. Ravi Teja |
| 25B11AI084 | B. Ganesh |
| 26B21AI080 | N. Subbarao |

## Project guide

**Dr. P. Kishorekumar**  
Associate Professor, Department of Artificial Intelligence and Machine Learning, Aditya University.

## Future enhancements

- A web or mobile interface for managing academic records.
- Attendance, fee, and timetable management.
- Role-based access for administrators, faculty, and students.
- Automated academic reports and database backups.
