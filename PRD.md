PRODUCT REQUIREMENT DOCUMENT
•	Product name: Lectra

•	Product Overview:
	Lectra is a smart attendance management system that enables university lecturers to easily record, monitor and review students' attendance records through an efficient, but also user-friendly platform. It's primary objective is to replace and simplify the primitive attendance-taking process by replacing manual paper-based method with a digital platform.

•	Problem Statement:
	During physical lectures, students constantly forge signatures on circulating paper sheets and answer verbal roll calls for their absent friends, making it difficult for lecturers to have accurate records of students' attendance. 

•	Product Goals/Objectives:  
1.	Reduce time spent on taking attendance.
2.	Organization and Management of attendance records.
3.	Quick and Easy retrieval of attendance records.
4.	Prevention of proxy attendance.

•	Success Matrics:
5.	Reduction in Attendance-taking time
6.	Successful Attendance Registration
7.	Attendance record accuracy
8.	Proxy Attendance prevention 
9.	Attendance record modification and tracking
10.	Attendance Deadline enforcement   

•	Target Users:
a.	Primary User: Lecturers
	They will use the platform to;
1.	Record student attendance
2.	Review previous attendance records
3.	Generate attendance report

b.	Secondary User: Management Staff    
•	The platform can also be applied when taking attendance not only during lectures but also during various programmes such as Babcock inter-disciplinary seminar, Hall Worship and so on.

c.	End Participant: Students
•	Students themselves may find the paper-based method of attendance difficult and tedious. Lectra makes it easier and quicker for them to make known their attendance in classes, so as to receive the maximum marks alloted for attendance.

•	Stakeholders:
a.	Primary Stakeholders:
1.	Students
2.	Lecturers

b.	Secondary Stakeholders:
1.	University Management
2.	Heads of Departments
3.	Administrators    

•	User Stories:
1.	As a Lecturer, I want to log into my account so that I can securely access my students' records.
2.	As a Student, I want to log into my account so that I can view my attendance record for each course.
3.	As a Lecturer, I want to generate attendance reports so that I can evaluate students' attendance.
4.	As a Student, I want to see my attendance history for each course.
5.	As a Student, I want to be able to report an incorrect attendance record so that errors can be reviewed and corrected.

•	Functional Requirements:
1.	ID          Requirement
2.	FR-01       Lecturers and Students can register and log in
3.	FR-02       The system allows lecturers to create attendance sessions
4.	FR-03       The system can generate various QR codes for every attendance session
5.	FR-04       The system has a QR-code scanner for the students
6.	FR-05       The system shall record students' attendance 
7.	FR-06       The system will automatically close attendance when the session expires
8.	FR-07       The system shall allow lecturers to edit attendance records
9.	FR-08       The system allows students to view their attendance history
10.	FR-09       The system will prevent duplicate attendance submission from the same device
11.	FR-10       The system will allow lecturers to view attendance reports
12.	FR-11       Lecturers can search up students by their names and matric numbers

•	Non-functional Requirements:
1.	Security - Users accounts and attendance records must be protected by a means of user authentication
2.	Performance - Attendance submission should be processed immediately
3.	Usability - Interface should be simple and easy to use
4.	Availability - Platform should be accessible whenever needed
5.	Scalability - The system should support increasing number of students
6.	Reliability - The system should maintain accurate attendance records

•	Product Features:
1.	User Authentication: Users should be able to log in using the necesssary authorized credentials and also log out successfully.
2.	QR Code-Based Check-in: Instead of lecturers manually handing out a sheet of paper for attendance, a QR code generated for the lecturer, which varies every lecture, can be displayed for students to scan and mark attendance for the day.   
3.	Attendance Session: Here, the attendance sign in and sign out is limited to the first and last 10 minutes of the class. This encourages punctuality to class, prevents students signing for their friends due to lack of time and also students who think that immediately after marking attendance, can boycott the lecture itself.     
4.	Attendance Recording: A fundamental purpose of the application itself, enabling students to be marked present or absent.
5.	Attendance History: Allows lecturers to review previous attendance records.
6.	Attendance Report: The system generates a summarised and comprehensive tabular record of the attendance of all students, also indicating the date and when they were present/absent using checks/crosses.
7.	Search and Filter: This feature makes it easy for the lecturer to easily find the records of any one of his students. 
8.	Student List: Displays students registered for the course.
9.	Record Modification: This feature can be used when a lecturer decides to manually edit the student's record. An example would be in a scenario where after attendance has been taken, a student shows signs of misbehaviour in class and the lecturer chooses to send them out and decides that they were absent for that day.

•	System Scope:
•	In Scope:
1.	User registration and log in.
2.	QR-code generation and scanning
3.	Attendance Session management
4.	Attendance time restrictions
5.	Attendance Modification
6.	Attendance History
7.	Attendance Reports

•	Out of Scope (Future Improvements):
1.	Biometric attendance verification
2.	Facial recognition
3.	Notifications/Student Warnings
4.	Acceptance Criteria:
5.	User Authentication:
6.	Students and Lecturers can log in using valid credentials
7.	Users with incorrect credentials are denied access
8.	Students and lecturers are directed to their respective dashboards
9.	Users can securely log out of their accounts

•	QR-code Generation:
1.	A lecturer can create an attendance session
2.	The system generates a unique QR-code for the session
3.	The QR-code becomes invalid once session is over
4.	Students can scan the QR-code with an in-built scanner in the platform   

•	Attendance Time-restriction:
1.	Lecturers can set an attendance opening/closing time
2.	Students can take attendance within the permitted period
3.	Attendance closes when session expires
4.	Lecturers can manually extend or terminate the session

•	Attendance Manipulation: 
1.	Lecturers can view attendance list for a particular lecture
2.	Lecturers can search for an individual student
3.	Lecturers can change a student's or students' attendance status from present to absent or vice versa
4.	Lecturers can use a short note to state their reason for the modification
5.	System saves updated attendance status
6.	Students will be notified about such modifications along with the reasons

•	Student Attendance History:
1.	Students can access their attendance history
2.	Attendance records are organized according to courses    
3.	Students can view the dates of previous lectures
4.	Students can see whether they were marked Present or Absent
5.	Changes made by lecturers are reflected in the student's attendance history

•	Lecturer Dashboard:
1.	Lecturers can view their assigned courses
2.	Lecturers can create attendance sessions
3.	Lecturers can generate QR codes
4.	Lecturers can view present and absent students
5.	Lecturers can modify attendance records
6.	Lecturers can access attendance summaries

•	Attendance Reports:
1.	Lecturers can view attendance reports for their courses
2.	Reports display the number of present and absent students
3.	Reports show attendance information for individual students
4.	Attendance information is displayed accurately
5.	Lecturers can filter attendance records by date and course

•	Assumptions and Open Questions:
1.	Assumptions:
2.	Students have access to their phones or other devices capable of scanning the QR-code
3.	Lecturers and Students have access to internet connection during attendance sessions
4.	Students have registered for their respective courses
5.	Students and Lecturers will be informed about how to use Lectra
6.	The University will permit use of a digital platform for managing attendance

•	Open Questions:
1.	Should students be allowed to register attendance using only one registered device?
2.	Should lecturers be allowed to edit attendance records after lectures have ended?
3.	Should students receive notifications when their attendance status is changed by the lecturer?
4.	Should students be able to challenge or report an incorrect attendance record?
5.	How long should the attendance records be stored in the system
6.	Should lecturers be required to provide a reason whenever they modify an attendance record?                  




