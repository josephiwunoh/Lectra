# Product Requirements Document (PRD)

**Project Title:** Lectra  
**Product Name:** Lectra

---

## 1. Product Overview

Lectra is a smart attendance management system that enables university lecturers to easily record, monitor and review students' attendance records through an efficient, user-friendly platform. Its primary objective is to replace and simplify the primitive attendance-taking process by replacing the manual paper-based method with a digital platform.

## 2. Problem Statement

### 2.1 The Problem

During physical lectures, students constantly forge signatures on circulating paper sheets and answer verbal roll calls for their absent friends, making it difficult for lecturers to have accurate records of students' attendance.

### 2.2 Who Has This Problem

- **Lecturers:** Need accurate attendance records and a reliable way to record and review students' attendance.
- **Students:** May find the paper-based attendance process difficult and tedious, and need a simple way to make their attendance known.
- **University management and programme administrators:** May need attendance to be recorded during lectures and other university programmes.

### 2.3 Evidence and Current Observations

The current problem identified for Lectra is the ease with which students can forge signatures on circulating attendance sheets or answer verbal roll calls for absent friends. This makes manual attendance records difficult to verify and maintain accurately.

### 2.4 Why the Current Process Falls Short

- Paper-based attendance relies on signatures that can be forged.
- Verbal roll calls allow students to answer for absent friends.
- Lecturers may find it difficult to maintain accurate and organized attendance records using the manual process.
- Retrieving and reviewing previous attendance records can be tedious.

## 3. Product Goals and Objectives

1. Reduce time spent on taking attendance.
2. Organize and manage attendance records.
3. Enable quick and easy retrieval of attendance records.
4. Prevent proxy attendance.

## 4. Success Metrics

1. Reduction in attendance-taking time.
2. Successful attendance registration.
3. Attendance record accuracy.
4. Proxy attendance prevention.
5. Attendance record modification and tracking.
6. Attendance deadline enforcement.

## 5. Target Users

### 5.1 Primary User: Lecturers

Lecturers will use the platform to:

1. Record student attendance.
2. Review previous attendance records.
3. Generate attendance reports.

### 5.2 Secondary User: Management Staff

The platform can also be applied when taking attendance not only during lectures but also during various programmes such as Babcock Inter-disciplinary Seminar, Hall Worship, and so on.

### 5.3 End Participants: Students

Students themselves may find the paper-based method of attendance difficult and tedious. Lectra makes it easier and quicker for them to make known their attendance in classes, so as to receive the maximum marks allotted for attendance.

## 6. Stakeholders

### 6.1 Primary Stakeholders

1. Students.
2. Lecturers.

### 6.2 Secondary Stakeholders

1. University Management.
2. Heads of Departments.
3. Administrators.

## 7. User Stories

1. As a Lecturer, I want to log into my account so that I can securely access my students' records.
2. As a Student, I want to log into my account so that I can view my attendance record for each course.
3. As a Lecturer, I want to generate attendance reports so that I can evaluate students' attendance.
4. As a Student, I want to see my attendance history for each course.
5. As a Student, I want to be able to report an incorrect attendance record so that errors can be reviewed and corrected.

## 8. Functional Requirements

| ID | Requirement |
|---|---|
| FR-01 | Lecturers and Students can register and log in. |
| FR-02 | The system allows lecturers to create attendance sessions. |
| FR-03 | The system can generate various QR codes for every attendance session. |
| FR-04 | The system has a QR-code scanner for the students. |
| FR-05 | The system shall record students' attendance. |
| FR-06 | The system will automatically close attendance when the session expires. |
| FR-07 | The system shall allow lecturers to edit attendance records. |
| FR-08 | The system allows students to view their attendance history. |
| FR-09 | The system will prevent duplicate attendance submission from the same device. |
| FR-10 | The system will allow lecturers to view attendance reports. |
| FR-11 | Lecturers can search for students by their names and matric numbers. |

## 9. Non-Functional Requirements

1. **Security:** User accounts and attendance records must be protected by means of user authentication.
2. **Performance:** Attendance submission should be processed immediately.
3. **Usability:** The interface should be simple and easy to use.
4. **Availability:** The platform should be accessible whenever needed.
5. **Scalability:** The system should support an increasing number of students.
6. **Reliability:** The system should maintain accurate attendance records.

## 10. Product Features

### 10.1 User Authentication

Users should be able to log in using the necessary authorized credentials and also log out successfully.

### 10.2 QR Code-Based Check-in

Instead of lecturers manually handing out a sheet of paper for attendance, a QR code generated for the lecturer, which varies every lecture, can be displayed for students to scan and mark attendance for the day.

### 10.3 Attendance Session

Attendance sign-in and sign-out are limited to the first and last 10 minutes of the class. This encourages punctuality to class, prevents students signing for their friends due to lack of time, and discourages students who think that immediately after marking attendance, they can boycott the lecture itself.

### 10.4 Attendance Recording

A fundamental purpose of the application itself, enabling students to be marked present or absent.

### 10.5 Attendance History

Allows lecturers to review previous attendance records.

### 10.6 Attendance Report

The system generates a summarised and comprehensive tabular record of the attendance of all students, also indicating the date and when they were present or absent using checks and crosses.

### 10.7 Search and Filter

This feature makes it easy for the lecturer to find the records of any one of their students.

### 10.8 Student List

Displays students registered for the course.

### 10.9 Record Modification

This feature can be used when a lecturer decides to manually edit a student's record. An example would be a scenario where, after attendance has been taken, a student shows signs of misbehaviour in class and the lecturer chooses to send them out and decides that they were absent for that day.

## 11. System Scope

### 11.1 In Scope

1. User registration and log in.
2. QR-code generation and scanning.
3. Attendance session management.
4. Attendance time restrictions.
5. Attendance modification.
6. Attendance history.
7. Attendance reports.

### 11.2 Out of Scope (Future Improvements)

1. Biometric attendance verification.
2. Facial recognition.
3. Notifications and student warnings.

## 12. Acceptance Criteria

### 12.1 User Authentication

1. Students and Lecturers can log in using valid credentials.
2. Users with incorrect credentials are denied access.
3. Students and lecturers are directed to their respective dashboards.
4. Users can securely log out of their accounts.

## 13. Minimum Viable Product (MVP) Features

### 13.1 QR-Code Generation

1. A lecturer can create an attendance session.
2. The system generates a unique QR code for the session.
3. The QR code becomes invalid once the session is over.
4. Students can scan the QR code with an in-built scanner in the platform.

### 13.2 Attendance Time Restriction

1. Lecturers can set an attendance opening and closing time.
2. Students can take attendance within the permitted period.
3. Attendance closes when the session expires.
4. Lecturers can manually extend or terminate the session.

### 13.3 Attendance Manipulation

1. Lecturers can view the attendance list for a particular lecture.
2. Lecturers can search for an individual student.
3. Lecturers can change a student's or students' attendance status from present to absent or vice versa.
4. Lecturers can use a short note to state their reason for the modification.
5. The system saves the updated attendance status.
6. Students will be notified about such modifications along with the reasons.

### 13.4 Student Attendance History

1. Students can access their attendance history.
2. Attendance records are organized according to courses.
3. Students can view the dates of previous lectures.
4. Students can see whether they were marked Present or Absent.
5. Changes made by lecturers are reflected in the student's attendance history.

### 13.5 Lecturer Dashboard

1. Lecturers can view their assigned courses.
2. Lecturers can create attendance sessions.
3. Lecturers can generate QR codes.
4. Lecturers can view present and absent students.
5. Lecturers can modify attendance records.
6. Lecturers can access attendance summaries.

### 13.6 Attendance Reports

1. Lecturers can view attendance reports for their courses.
2. Reports display the number of present and absent students.
3. Reports show attendance information for individual students.
4. Attendance information is displayed accurately.
5. Lecturers can filter attendance records by date and course.

## 14. Assumptions and Open Questions

### 14.1 Assumptions

1. Students have access to their phones or other devices capable of scanning the QR code.
2. Lecturers and Students have access to an internet connection during attendance sessions.
3. Students have registered for their respective courses.
4. Students and Lecturers will be informed about how to use Lectra.
5. The University will permit the use of a digital platform for managing attendance.

### 14.2 Open Questions

1. Should students be allowed to register attendance using only one registered device?
2. Should lecturers be allowed to edit attendance records after lectures have ended?
3. Should students receive notifications when their attendance status is changed by the lecturer?
4. Should students be able to challenge or report an incorrect attendance record?
5. How long should the attendance records be stored in the system?
6. Should lecturers be required to provide a reason whenever they modify an attendance record?
