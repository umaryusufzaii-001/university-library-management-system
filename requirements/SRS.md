# Software Requirements Specification (SRS)

## 1. Introduction

### 1.1 Purpose
This document describes the functional and non-functional requirements of the University Library Management System.

### 1.2 Scope
The system will manage books, members, borrowing, returns, reservations, and overdue notifications.

### 1.3 Intended Users
- Students
- Library staff
- Library administrator

## 2. Functional Requirements

**FR-01: Book Management**
The system shall allow authorized staff to add, update, search, and manage book records.

**FR-02: Member Management**
The system shall maintain student membership records.

**FR-03: Borrowing**
The system shall record book borrowing transactions.

**FR-04: Returns**
The system shall record returned books and update their availability.

**FR-05: Reservations**
The system shall allow students to request reservations for books.

**FR-06: Overdue Management**
The system shall identify overdue books.

**FR-07: Notifications**
The system shall support overdue notifications for members.

## 3. Non-Functional Requirements

- Usability: The interface should be easy to understand.
- Security: Only authorized users should access restricted functions.
- Reliability: Records should be maintained accurately.
- Performance: Common searches should return results efficiently.
- Maintainability: The system design should support future updates.

## 4. Assumptions and Constraints

The system assumes that users have valid membership details and library staff maintain accurate book records. The project is limited to analysis, specification, modelling, and prototype design.

## 5. External Interface Requirements

- User interface for students and library staff.
- Database interface for book and member records.
- Notification interface for overdue alerts.

## 6. Future Enhancements

- Online fine payment.
- Mobile application.
- Integration with university student records.
