# <center> Use Case: @ Home Testing Application</c>

**Tyra Oberholzer**

**August 16, 2020**

**Actors**
* Users
* Teachers
* Students
* Tests
* Programmer

**Triggers**
* Teacher has issues uploading test to application.
* Student has issues taking test.
* Teacher has issues pushing test to specific student.

**Pre-Conditions**
* Teachers must have an account in order to upload a test.
* Students must have an account in order to take test and/or see their grades.
* There must be a test uploaded in order to take a test.

**Post-Conditions**
* Teachers are able to submit tests and/or look at students grades.
* Students are able to take tests and/or look at their grades.

**Normal Flow**
1. The user select whether they are a teacher or student.
1. After selection the student/teacher creates an account.
1. The user can now log on at any point.
1. Once the teacher is logged on they will have the option to submit a test, push a test to a student, and/or look at a student's grades.
1. If the teacher is trying to submit or push a test the system will prompt for the teachers ID and password. 
1. If the teacher is trying to look at their student's grades the system will prompt them for their credentials.
1. Once the student is logged on they will have the ability to look at previous test grades or take a test the teacher has pushed.
1. If the student clicks on the test to take it the system will prompt them for their student credential, which is their login information.
1. Once the teacher and/or student have completed they will exit the application.

**Alternate Flow**
* The teacher has an issue uploading a test
	1. The teacher selects the 'Select for help' button.
	1. Once selected it notifies the programmer of the issue.
	1. The programmer looks into issue and fixes.
	1. Email is sent to teacher to notify the issue is fixed.
* Student has an issue taking a test.
	1. The student selects the button 'Select for help'.
	1. It sends an alert to the teacher
		1. Then looks to see if the error is on their side.
		1. If no the teacher clicks the select for help button.
		1. Which alerts the programmer of the error.
		1. Fixes the issue.
		1. Email is sent to the teacher stating issue is fixed.
