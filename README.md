                                                                                                           Guvi Zen Library Management System

This project involves the design and implementation of a database model for managing users, students, mentors, topics, tasks, and attendance within the Guvi Zen platform. The database is designed using MySQL, with tables representing various entities and their relationships.

Database Schema: 

The database model includes the following tables:
1. Users
Stores information about all the users of the platform.


2. Students
Contains information specific to students.

3. Mentors
Contains information specific to mentors.


4. Topics
Stores information about the topics covered in the platform.

5. Tasks
Contains information about tasks assigned to topics.

6. Attendance
Records attendance details of users for specific sessions.

Relationships:

Students & Mentors: Each student and mentor is associated with a unique user via the user_id field.
Topics: Topics are assigned to mentors, and the relationship is managed through the mentor_id field.

Tasks: 
Each task is linked to a specific topic using the topic_id field.
Attendance: '
Attendance records are associated with both users and topics, linking through user_id and topic_id fields, respectively.
