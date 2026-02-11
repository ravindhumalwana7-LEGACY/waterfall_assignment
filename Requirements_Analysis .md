# Phrase 2: Requirements Analysis
## Functional Requirements

The system shall allow students to create a profile containing their name, student ID, gender, department, and academic year.

The system must verify that each Student ID is unique to prevent data redundancy.

The system shall provide secure login portals for students and administrators.

The system shall filter available rooms based on the student's Gender to ensure they are placed in the correct hostel building.

The system shall attempt to group students from the same Department together within the same floor or section of the building.

The system shall prioritize room assignment based on the academic year giving like first year students priority for on-campus hostels.

## Non-Functional Requirements
The system must be minimalistic in design.

A student should be able to complete the hostel registration within 5 minutes.

The interface for the system must have a responsive design. Adjusting its design for smartphones and desktops.

The system should be able to handle about 500 registrations during high tracffic enrollment periods.

The system must do a automated daily backup of the database to an external database to prevent data loss.

The student information must only be visible to authorized administrative  staff.

The system must function with the existing university dacilities and resources.

## Use Cases
### Case 1: Student Room Registration
1. Student logins to the portal.

2. Then enters profile details. Details about student ID, gender, department and academic year.

3. System validate and verify student ID.

4. Then the system successfully registers the student profile into the database.

5. A notification is sent to the student about registration details and status.

### Case 2: Administration Registration Approval
1. When the system registers the student profile into the database, the administration is notified.

2. Then the administration filters out the students according to university rules and regulations.

3. After, the  eligible students granted  accomandation.
4. Then the system assigns the rooms to students according to gender, department and academic year.

5.Room status is updated, and the student is notified.
