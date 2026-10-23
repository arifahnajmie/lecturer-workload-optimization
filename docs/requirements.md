# Requirements

## Functional requirements (what the system must DO)
- **FR1:** The system shall allow the staff administrator to upload workload data of lecturer 
- **FR2:** The system shall display the information of lecturers teaching hours, credit hours and course assignments.
- **FR3:** The system shall manage the group by lecturers based on workload characteristics using K-Means clustering.
- **FR4:** The system shall generate a proposed teaching assignments using Genetic Algorithm (GA) while respecting predefined workload limits.
- **FR5:** The system shall display workload comparisons before and after optimization.

## Non-functional requirements (how the system must PERFORM)
- **NFR1:** The system shall display the workload distribution within 3 seconds for a dataset of up 50 lecturers under defined test conditions.
- **NFR2:** The system shall allow only authenticated staff administrators to upload or modify the lecturer workload data.
- **NFR3:** The system shall allow a new staff administrator to upload a valid dataset and initiate optimization within 5 minutes based on the instructions given.
