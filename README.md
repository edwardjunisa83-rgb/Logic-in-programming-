<img width="375" height="214" alt="image" src="https://github.com/user-attachments/assets/b681cd00-78c0-43b8-8071-2a96e356de5e" />

# PRO101_ASSIGNMENT 1_EDWARD HINDOWA JUNISA - 905006622
Flowchart and pseudocodes data
LIMKOKWING UNIVERSITY OF
CREATIVE TECHNOLOGY
SIERRA LEONE
DEPARTMENT OF INFORMATION AND COMMUNICATION TECHNOLOGY
PROG101 – PRINCIPLES OF
PROGRAMMING LOGIC AND DESIGN
ASSIGNMENT REPORT
DESIGNING A LOGICAL SOLUTION FOR COMMUNITY WASTE
COLLECTION AND MANAGEMENT IN SIERRA LEONE
DETAIL
INFORMATION
Selected Community Problem
Proposed System
Poor Waste Collection and Disposal
Community Waste Collection and Management System (CWMS)
Lecturer
Student Name
Elijah Fullah
Edward Hindowa Junisa
Student ID
Programme
905006622
____________________________
Submission Date
____________________________
BLUE • GOLD • WHITE EDITION
Page 1
PROG101 | Edward Hindowa Junisa | 905006622
TABLE OF CONTENTS
• 1. Introduction and Project Background
• 2. Problem Description and Analysis
• 3. Background and Community Impact
• 4. Proposed Solution
• 5. Computational Thinking Process
• 6. Algorithm Design
• 7. Pseudocode
• 8. Flowchart Design
• 9. Logical Design
• 10. Functional Modules and Functions
• 11. Expected Outputs and Sample Scenarios
• 12. Open Source Software Justification
• 13. Digital Public Goods Justification
• 14. Sustainable Development Goal Alignment
• 15. GitHub Repository and Version Control
• 16. Conclusion
• 17. References
Page 2
PROG101 | Edward Hindowa Junisa | 905006622
1. INTRODUCTION AND PROJECT BACKGROUND
Waste management is an important public service that helps maintain clean, healthy and safe communities. In
Sierra Leone, some communities experience challenges with regular waste collection, improper disposal of
rubbish, blocked drainage systems and limited public awareness of proper waste disposal practices.
Poor waste management can contribute to environmental pollution, unpleasant surroundings, flooding risks and
the spread of diseases.
This project proposes a Community Waste Collection and Management System (CWMS). The system is a logical
computer-based solution designed to organize waste collection requests, record community information, assign
collection workers, monitor collection activities and provide useful reports.
The project is designed using programming logic and computational thinking. It demonstrates algorithms,
pseudocode, flowcharts, decision structures, repetition structures, variables, constants, Boolean logic, functions
and modular design.
The system is intended as a proposed solution and not a claim that a fully operational application has already been
deployed.
2. PROBLEM DESCRIPTION AND ANALYSIS
2.1 The Community Problem
The selected problem is poor waste collection and disposal in Sierra Leone communities. Some households and
businesses may experience irregular collection services. Waste can accumulate around homes, markets, streets
and public spaces when collection arrangements are unreliable.
In some areas, people may dispose of rubbish in open spaces or drainage channels because convenient collection
services are unavailable or poorly coordinated.
2.2 Who Is Affected?
• Households and families.
• Market women and traders.
• Schoolchildren and teachers.
• Business owners.
• Waste collection workers.
• Local councils and community leaders.
• People living near waste disposal locations.
2.3 Why Does the Problem Exist?
1. Poor organization of collection schedules.
2. Inadequate waste collection facilities.
3. Limited communication between residents and collectors.
4. Lack of reliable records of collection requests.
5. Insufficient public awareness.
6. Limited monitoring of collection activities.
7. Inadequate coordination of available resources.
2.4 Why Is a Logical Computer Solution Needed?
A simple digital system can improve the organization of collection activities. Instead of depending entirely on verbal
communication or handwritten records, residents and collection administrators can use structured information. The
system can record requests, identify collection locations, assign workers and update the status of each request.
Page 3
PROG101 | Edward Hindowa Junisa | 905006622
3. BACKGROUND AND COMMUNITY IMPACT
Waste management is connected to public health, environmental protection and community development. When
waste is not properly collected, it may create unpleasant surroundings and contribute to environmental problems.
Plastic waste and other materials can block drainage channels, while decomposing rubbish can attract pests.
The proposed Community Waste Collection and Management System will help organize information and improve
communication between residents and waste collection administrators.
3.1 Expected Community Impact
• Improve the organization of waste collection.
• Help residents report uncollected waste.
• Reduce missing or duplicated collection records.
• Support better planning of collection routes.
• Improve communication between residents and administrators.
• Encourage responsible waste disposal.
• Provide information for community planning.
3.2 Beneficiaries
The main beneficiaries are households, traders, schools, businesses, waste collection workers, local authorities
and the wider community.
4. PROPOSED SOLUTION
The proposed solution is a Community Waste Collection and Management System (CWMS). The system will allow
a resident or authorized operator to submit a waste collection request. The administrator will review the request,
check the location and availability of collection workers, and assign a suitable worker. After collection, the request
status will be updated.
4.1 Main Features
1. Resident registration.
2. Waste collection request submission.
3. Location recording.
4. Request validation.
5. Worker assignment.
6. Collection status updates.
7. Collection history.
8. Administrative reporting.
4.2 System Users
Resident: Submits a collection request and checks its status.
Administrator: Reviews requests and assigns collection workers.
Collection Worker: Receives assigned tasks and updates collection status.
5. COMPUTATIONAL THINKING PROCESS
Computational thinking is a problem-solving approach that breaks a complex problem into smaller parts and
develops logical steps for solving them. The project applies four major computational thinking concepts.
Page 4
PROG101 | Edward Hindowa Junisa | 905006622
5.1 Decomposition
The waste management problem is divided into smaller tasks:
• Register residents.
• Receive collection requests.
• Validate submitted information.
• Check worker availability.
• Assign collection tasks.
• Update request status.
• Generate reports.
5.2 Pattern Recognition
The system identifies repeated activities, such as residents submitting requests, administrators assigning workers
and workers completing collections. Recognizing these patterns makes it easier to design reusable procedures.
5.3 Abstraction
The system focuses on important information needed for waste collection, including resident name, contact
number, community or location, waste type, request date and collection status. Unnecessary information is
excluded from the main collection process.
5.4 Algorithm Design
An algorithm is a sequence of clear instructions used to solve a problem. The project uses an algorithm to receive
requests, validate information, assign workers and update collection records.
6. ALGORITHM DESIGN
6.1 Step-by-Step Algorithm
Algorithm: Community Waste Collection Management
1. Start.
2. Display the main menu.
3. Ask the user to select an operation.
4. If the user selects registration, collect resident information.
5. Validate the resident information.
6. Save valid resident information.
7. If the user selects a collection request, collect waste and location details.
8. Validate the request details.
9. Save the request.
10. Check whether a collection worker is available.
11. If a worker is available, assign the worker.
12. If no worker is available, mark the request as pending.
13. Update the collection status when the task is completed.
14. Generate a report when requested.
15. Ask whether the user wants another operation.
16. If yes, return to the main menu.
Page 5
PROG101 | Edward Hindowa Junisa | 905006622
17. If no, end the system.
7. PSEUDOCODE
7.1 Main System Pseudocode
BEGIN
    DISPLAY "COMMUNITY WASTE MANAGEMENT SYSTEM"
    SET continueSystem = TRUE
    WHILE continueSystem = TRUE
        DISPLAY "1. Register Resident"
        DISPLAY "2. Submit Waste Request"
        DISPLAY "3. Assign Collection Worker"
        DISPLAY "4. Update Collection Status"
        DISPLAY "5. Generate Report"
        DISPLAY "6. Exit"
        INPUT choice
        IF choice = 1 THEN
            CALL RegisterResident()
        ELSE IF choice = 2 THEN
            CALL SubmitRequest()
        ELSE IF choice = 3 THEN
            CALL AssignWorker()
        ELSE IF choice = 4 THEN
            CALL UpdateStatus()
        ELSE IF choice = 5 THEN
            CALL GenerateReport()
        ELSE IF choice = 6 THEN
            SET continueSystem = FALSE
        ELSE
            DISPLAY "Invalid selection"
        END IF
    END WHILE
    DISPLAY "Thank you for using the system"
END
7.2 Resident Registration Pseudocode
BEGIN RegisterResident
    INPUT residentName
    INPUT phoneNumber
    INPUT community
    IF residentName is empty OR
       phoneNumber is empty OR
       community is empty THEN
        DISPLAY "Please complete all required fields"
    ELSE
        SAVE residentName
        SAVE phoneNumber
        SAVE community
        DISPLAY "Registration successful"
    END IF
END
7.3 Waste Request Pseudocode
BEGIN SubmitRequest
    INPUT residentID
    INPUT wasteType
    INPUT collectionLocation
    IF residentID is valid AND
       wasteType is not empty AND
       collectionLocation is not empty THEN
        SET requestStatus = "Pending"
        SAVE request
        DISPLAY "Request submitted successfully"
    ELSE
        DISPLAY "Invalid request details"
    END IF
END
Page 6
PROG101 | Edward Hindowa Junisa | 905006622
7.4 Worker Assignment Pseudocode
BEGIN AssignWorker
    CHECK availableWorkers
    IF availableWorkers > 0 THEN
        ASSIGN worker to request
        SET requestStatus = "Assigned"
        DISPLAY "Worker assigned successfully"
    ELSE
        SET requestStatus = "Pending"
        DISPLAY "No worker available"
    END IF
END
7.5 Collection Status Pseudocode
BEGIN UpdateStatus
    INPUT requestID
    IF requestID exists THEN
        INPUT newStatus
        IF newStatus = "Completed" OR
           newStatus = "In Progress" THEN
            UPDATE requestStatus
            DISPLAY "Status updated successfully"
        ELSE
            DISPLAY "Invalid status"
        END IF
    ELSE
        DISPLAY "Request not found"
    END IF
END
8. FLOWCHART DESIGN
A flowchart is a graphical representation of an algorithm. It uses standard symbols to show the sequence of
operations and decisions.
8.1 Main System Flowchart
   <img width="1212" height="1297" alt="713378735-e3338cc4-eb13-4496-8f5b-13134e14c955" src="https://github.com/user-attachments/assets/6f9390a8-5143-4588-8631-d902ec29b70a" />
<img width="1212" height="1297" alt="Colorful Menu Management Flowchart" src="https://github.com/user-attachments/assets/e3338cc4-eb13-4496-8f5b-13134e14c955" />            
Page 7
PROG101 | Edward Hindowa Junisa | 905006622
8.2 Flowchart Symbol Legend
Symbol
Name
Purpose
Oval
Rectangle
Terminator
Process
Start or end
Processing or action
Parallelogram
Input/Output
Enter or display data
Diamond
Decision
Yes/No condition
Arrow
Cylinder
Flow line
Database
Direction of process
Store information
8.3 Suggested Flowchart Colours
• Blue: Start and end symbols.
• Gold: Processing steps.
• Yellow: Decision symbols.
• Green: Successful operations.
• Red: Errors or rejected information.
• Black: Arrows and connecting lines.
10. LOGICAL DESIGN
Logical design explains how information enters the system, how it is processed and what output is produced.
9.1 Input
• Resident name.
• Phone number.
• Community name.
• Waste type.
• Collection location.
• Request date.
• Worker information.
9.2 Processing
1. Validates resident information.
2. Checks collection request details.
3. Stores valid requests.
4. Checks worker availability.
5. Assigns workers.
6. Updates collection status.
7. Generates reports.
9.3 Output
• Registration confirmation.
• Collection request number.
Page 8
PROG101 | Edward Hindowa Junisa | 905006622
• Request status.
• Worker assignment confirmation.
• Completed collection records.
• Administrative reports.
9.4 Variables
Variable
Data Type
residentName
phoneNumber
String
String
Description
Resident's name
Contact number
community
wasteType
String
String
Community location
Type of waste
requestID
availableWorkers
Integer
Integer
Unique request number
Number of available workers
requestStatus
continueSystem
String
Boolean
Current request status
Controls system repetition
9.5 Constants
Constant
Meaning
MAX_MENU_OPTION
STATUS_PENDING
6
"Pending"
STATUS_ASSIGNED
STATUS_COMPLETED
"Assigned"
"Completed"
9.6 Decision Structures
Decision structures allow the system to select an action based on a condition.
IF availableWorkers > 0 THEN
    ASSIGN worker
ELSE
    DISPLAY "No worker available"
END IF
9.7 Repetition Structures
A WHILE loop allows the main menu to repeat until the user selects Exit.
WHILE continueSystem = TRUE
    DISPLAY main menu
    INPUT choice
END WHILE
9.8 Boolean Logic
Boolean values are TRUE or FALSE.
IF residentName is not empty AND
   phoneNumber is not empty THEN
   DISPLAY "Valid registration"
END IF
The AND operator ensures that both conditions must be true.
Page 9
PROG101 | Edward Hindowa Junisa | 905006622
10. FUNCTIONAL MODULES AND FUNCTIONS
Modular design divides a large system into smaller independent parts.
Module
Function
Responsibility
Registration
Request
RegisterResident()
SubmitRequest()
Registers residents
Records collection requests
Validation
ValidateDetails()
Checks submitted information
Assignment
AssignWorker()
Assigns available workers
Status
Reporting
UpdateStatus()
GenerateReport()
Updates collection progress
Produces collection reports
Exit
ExitSystem()
10.1 Advantages of Modular Design
• Makes the system easier to understand.
• Reduces repetition of instructions.
• Makes testing easier.
• Simplifies maintenance.
Ends the system
• Allows different functions to be improved independently.
11. EXPECTED OUTPUTS AND SAMPLE SCENARIOS
The following examples demonstrate the expected behaviour of the proposed system. They are illustrative sample
outputs, not results from a deployed application.
Scenario 1: Successful Resident Registration
Input: Resident Name: Mariama Kamara; Phone Number: 076123456; Community: Allen Town.
COMMUNITY WASTE MANAGEMENT SYSTEM
Resident registration successful!
Resident Name: Mariama Kamara
Community: Allen Town
Status: Registered
Scenario 2: Successful Waste Request
Input: Resident ID: 001; Waste Type: Household Waste; Location: Allen Town.
Waste collection request submitted.
Request ID: 001
Waste Type: Household Waste
Location: Allen Town
Status: Pending
Scenario 3: Worker Available
Input: Available Workers: 3.
Worker availability confirmed.
Collection worker assigned.
Request Status: Assigned
Scenario 4: No Worker Available
Input: Available Workers: 0.
Page 10
PROG101 | Edward Hindowa Junisa | 905006622
No collection worker is currently available.
Request Status: Pending
Scenario 5: Collection Completed
Input: Request ID: 001; New Status: Completed.
Collection status updated successfully.
Request ID: 001
Status: Completed
11.1 Testing Table
Test
Input or Condition
1
2
Complete resident details
Empty resident name
Expected Result
Registration successful
Error message
3
4
Valid collection request
Invalid request details
Request saved
Request rejected
5
6
Worker available
No worker available
Worker assigned
Request remains pending
7
8
Existing request ID
Invalid menu option
Status can be updated
Error message
9
Exit selected
System ends
12. OPEN SOURCE SOFTWARE JUSTIFICATION
Open Source Software is software whose source code is made available under a licence that permits users to
inspect, use, modify and redistribute it under the licence terms.
12.1 Why the Proposed Solution Should Be Open Source
The Community Waste Collection and Management System can benefit from an open-source approach because it
encourages transparency, collaboration and improvement.
12.2 Benefits to Sierra Leone
1. Lower development costs: Communities and organizations can adapt existing open-source tools.
2. Local innovation: Sierra Leonean developers can contribute improvements.
3. Transparency: Technical teams can inspect how the system works.
4. Education: Students can study and learn from the project.
5. Collaboration: Developers and community organizations can work together.
12.3 Potential Community Contributions
Residents can provide feedback about collection problems. Local developers can improve the design, while
community organizations can help with awareness and testing.
13. DIGITAL PUBLIC GOODS JUSTIFICATION
Digital Public Goods (DPGs) are digital resources such as software, data, standards and content that can
contribute to sustainable development when they meet recognized openness and other relevant safeguards.
The proposed system could become a Digital Public Good if it is developed and maintained under an appropriate
open licence, follows relevant standards and includes safeguards for privacy and responsible data use.
Page 11
PROG101 | Edward Hindowa Junisa | 905006622
13.1 Accessibility
A simple interface could allow residents and administrators to use the system with basic digital skills.
13.2 Openness
Publishing the software under an appropriate open-source licence can allow other communities to inspect and
adapt it.
13.3 Public Benefit
The system could help communities organize waste collection and improve environmental management.
13.4 Privacy and Security
Personal information such as phone numbers and residential details should be protected. Access should be limited
to authorized users, and unnecessary personal information should not be published.
14. SUSTAINABLE DEVELOPMENT GOAL ALIGNMENT
SDG 11 – Sustainable Cities and Communities
The system supports cleaner and more organized communities through improved waste collection coordination.
SDG 3 – Good Health and Well-being
Better waste management can contribute to healthier surroundings and reduce some environmental health risks.
SDG 6 – Clean Water and Sanitation
Responsible waste disposal can help reduce rubbish entering drainage channels and water environments.
SDG 12 – Responsible Consumption and Production
The system can encourage responsible waste handling, separation and recycling practices.
15. GITHUB REPOSITORY AND VERSION CONTROL
GitHub is an online platform used to store, manage and collaborate on software projects. Git is a version control
system that tracks changes made to project files.
15.1 Proposed Repository Name
PROG101_Assignment1_EdwardHindowaJunisa_905006622
15.2 Proposed Repository Structure
Community-Waste-Management/
|
|---- README.md
|
|---- Report/
|     |---- Assignment_Report.pdf
|
|---- Algorithms/
|     |---- Main_Algorithm.txt
|
|---- Pseudocode/
|     |---- System_Pseudocode.txt
|
|---- Flowcharts/
|     |---- Main_Flowchart.png
|
|---- Screenshots/
|     |---- Repository_Screenshot.png
|
|---- Documentation/
      |---- System_Description.txt
Page 12
PROG101 | Edward Hindowa Junisa | 905006622
15.3 Example Git Commands
git init
git add .
git commit -m "Initial project documentation"
git add Flowcharts/
git commit -m "Add system flowchart"
git add Pseudocode/
git commit -m "Add system pseudocode"
git push
15.4 Required GitHub Evidence
1. GitHub repository.
2. Repository URL.
3. Git commit history.
4. README.md file.
5. Repository screenshot.
Important: These are submission steps, not evidence already created. Create the repository using your own
GitHub account and insert your actual repository URL and screenshots before submission.
16. CONCLUSION
The Community Waste Collection and Management System is a proposed logical solution to poor waste collection
and disposal in Sierra Leone communities.
The project demonstrates how computational thinking can be used to understand a community problem and
develop a structured solution.
Through algorithms, pseudocode, flowcharts, variables, decision structures, repetition structures, Boolean logic,
functions and modular design, the project explains how a computerized waste collection system could operate.
The proposed system can improve the organization of collection requests, support worker assignment, provide
useful records and encourage responsible waste management.
The project also demonstrates the value of Open Source Software, Digital Public Goods and the Sustainable
Development Goals in addressing community challenges.
In conclusion, technology and logical problem-solving can contribute to cleaner, healthier and more sustainable
communities in Sierra Leone.
17. REFERENCES
1. Limkokwing University of Creative Technology, Sierra Leone. (2026). PROG101: Principles of Programming
Logic and Design – Individual Assignment Brief.
2. United Nations. (2015). Transforming Our World: The 2030 Agenda for Sustainable Development.
3. United Nations Development Programme. Sustainable Development Goals.
4. Open Source Initiative. The Open Source Definition.
5. GitHub Documentation. Git and GitHub Guides.
6. Digital Public Goods Alliance. Digital Public Goods Standard.
END OF REPORT
