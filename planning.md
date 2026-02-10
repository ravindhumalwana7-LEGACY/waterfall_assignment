# Phrase 1:Planning
## Problem statement
Manually allocating hostel rooms is inefficient, time consuming and has high chance for human errors.

One of the biggest problem is data redundancy. Data redundancy leads to overbooking or underutiliazing space in hostel rooms. Inwhich the oppourtunity for a student to suitable accommodation is lost.

Another problem is administrative staff could spend excessive amount of time to cater student preferences. 

Also lack of real time update and access for students to check their room allocation. Without real time visibility into room status the administration struggles to manage student intake. Students also face unnecessary delays and uncertainity during the entrollment process.



## Objective
### 1. Automate allocation
Replacing the manual processes with an automated system that assigns rooms vased on student criteria.

### 2. Completely eliminate redundancy
 
Implementation of a relational database management system and create a single database to prevent double booking and ensure all accomodations are accounted for.

### 3. Automated notifications

Send emails to the students when they successfully register for hostel accomodations and when a room is successfully allocated. Also notify whether the student is eligible for hostel facilities according to university regulations and rules.

## Scope
User authentication: Secure login portals to apply and manage by the students and administrators.

Attribute based allocation: Assigns rooms to students based on medical needs and dividing the students into different hostel wings based on gender. Assigning rooms based on same departments.

Real time hostel information: The administration must have the ability to monitor oocupancy levels, inventory and available sloths in the hostel.

Online payment processing: Easy gateway to do online registration payment. Also should record student information and payment details. 

## Assumptions and constraints 
### Assumptions
Every student has a device and connectivity to do the online registration.

Unique identifier: As every student has a unique university id number it can be used as a primary key in the database.


User Literacy: It is assumed that both students and administrative staff possess basic computer literacy and can navigate a web-based interface with minimal training.

### Constraints
#### Technical Constraints:

The system must be compatible with modern web browsers.

The backend must be developed using lightweight, open-source technologies to avoid high licensing costs.

#### Security & Privacy Constraints:

The system must strictly follow data protection protocols to ensure student information (especially gender and contact details) is not accessible to unauthorized users.

#### Hardware Constraint:

The system must be able to run efficiently on existing university servers without requiring an expensive hardware upgrade.