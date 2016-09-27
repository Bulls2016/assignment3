Assessment item 3
Asg 3 - Dynamic Testing
Value: 40%
Due date: 23-Sep-2016
Return date: 20-Oct-2016
Submission method options
Alternative submission method
Task
Assignment 3 revolves around developing and testing a small application.

You will be provided with some initial requirement and design documentation describing a small application. You will also be provided with some interface files defining the domain objects. These will be available in the Assignment 2 directory of the Resources section of the subject's Interact site.

Your task is to develop and test the required classes to support a use case. Your development should take place within a version control system using appropriately sized, commented, and timely commits.

You must then identify and specify user acceptance tests for that use case, and carry out and report on those tests

Please note that the focus in this assignment is on the process and techniques applied, not the complexity of the code. It is recognised that the process applied is ‘way over the top’ for the size of problem addressed.

Also note that it is recognised that standard practice is to specify user acceptance tests before development activities occur. Unfortunately the semester timetable makes this impractical.
 

Tasks

1. Version Control (10 marks)

Establish an individual version control repository for the assignment. Follow version control best practice during your implementation and testing of the required code modules. All code should be under version control from the beginning of the assignment.

2. Unit Testing (35 marks)

Implement the modules required to support your chosen use case according to the provided design. Use a unit test framework to comprehensively test your implementations as you develop them. Use stubs, fake, or mock objects as appropriate to isolate the class under test.

Commit your code changes to the version control system with every new addition of functionality (method or class implementation)

2. Integration Testing (35 marks)

Integrate your modules to support your chosen use case. Provide integration tests to check interaction between control, entity, and service classes without requiring GUI inputs.

Once again commit your code changes with every increment of functionality.

3. User Acceptance Tests (UAT). (20 marks)

On the basis of the requirement and design documentation identify some use case scenarios and test cases which can be used to check correct functionality in the implemented use case. Specify user acceptance test procedures, test data, and expected results for the most critical aspects of use case functionality. A template for a UAT will be available in the Assignment 1 directory of the Resources section of the subject's Interact site.

Commit your UAT specifications to version control.

Once the use case has been implemented, carry out the user acceptance tests you specified. Use the test data and procedures specified and check that it meets stated acceptance criteria. Report on the success or otherwise of the test.

Commit the completed test reports to your version control system.

 

Submit:

A text file containing the URL to your development repository. Indicate in the text file where in the repository source code and UAT documents can be found.

 

Rationale
This assignment is motivated by the following subject learning outcomes:

apply knowledge and skills to effectively utilize version control (Learning Outcome 2);
identify the purpose and limitations of software testing (Learning Outcome 4);
design and implement an appropriate suite of software tests to support the complete system development life cycle (Learning Outcome 5);
The intent of the assignment is to articulate taught concepts and skills in the context of developing a suite of unit, integration, and user acceptance tests for a small application.

Marking criteria
Unit Testing (35 marks)

Criteria
High Distinction 
Distinction
Credit
Pass
Fail
How well does the student design and implement an appropriate suite of software tests in the context of unit testing?
Comprehensive coverage

Tests are independent and repeatable

Each test tests only one thing
 
Dependencies supplied by mock objects.
 
Well-structured test code. Asserts separated from actions
 
Clear and meaningful naming convention

Well organised and navigable
 
 
 
 
Thorough coverage

Tests are independent and repeatable
Each test tests only one thing
 
Dependencies supplied by mock objects
 
Well-structured test code. Asserts separated from actions
 
Good coverage
 
Tests are independent and repeatable

Each test tests only one thing
 
Dependencies supplied by mock objects.
 
 
Adequate coverage

Tests are independent and repeatable

Each test tests only one thing
 	
 
Inadequate coverage

Test dependent on order of testing

Tests conflate multiple outcomes.
 
  

Integration Testing (35 marks)

Criteria
High Distinction 
Distinction 
Credit
Pass
Fail
How well does the student design and implement an appropriate suite of software tests in the context of integration testing?
Comprehensive coverage

Independent and repeatable

Each test tests only one thing

Only some low level integration testing carried out.
 
Dependencies supplied by mock objects as required.

Considerable low level integration testing carried out.

Integration progression apparent.
Well-structured test code. Asserts separated from actions

Integration testing up to system operation level carried out.
 
Clear and meaningful naming convention.
 
Well organised and navigable
 
Thorough coverage

Independent and repeatable

Each test tests only one thing

Only some low level integration testing carried out
 
Dependencies supplied by mock objects as required.

Considerable low level integration testing carried out.

Integration progression apparent.
Well-structured test code. Asserts separated from actions

Integration testing up to system operation level carried out.
 
 
Good coverage

Independent and repeatable

Each test tests only one thing

Only some low level integration testing carried out
 
Dependencies supplied by mock objects as required.

Considerable low level integration testing carried out.

Integration progression apparent.
 
 
Adequate coverage

Independent and repeatable

Each test tests only one thing

Only some low level integration testing carried out
 
 
Inadequate coverage

Test dependent on order of testing

Tests conflate multiple outcomes.

No real integration testing performed.
 
 
 

User Acceptance Testing (20 marks)

Criteria
Fail
Pass
Credit
Distinction
High Distinction
How well does the student design and implement an appropriate suite of software tests in the context of UAT?
 
Acceptance tests specified at
‘use case scenario’ level, and at system operation level.

Tests normal, major alternate and abnormal execution flows

Test data for normal, major alternate, and abnormal flows supplied.

Acceptance criteria clear.

Test results reported quantitatively.

Clear and meaningful naming convention

Tests well organised and navigable
 
 
Acceptance tests specified at
‘use case scenario’ level

Tests normal, major alternate and abnormal execution flows

Test data for normal, major alternate, and abnormal flows supplied.

Acceptance criteria clear.

Test results reported quantitatively.
 
Acceptance tests specified at
‘use case scenario’ level
 
Tests normal and major alternate flows
 
Test data for normal and major alternate flows supplied.
 
Acceptance criteria clear.

Test results reported qualitatively.
 
Acceptance tests specified at
‘use case scenario’ level.
 
Only tests normal flow.
 
Test data for normal flow supplied.
 
Acceptance criteria clear.
 
Test results reported qualitatively.
 
 
Test results reported quantitatively.
 
Acceptance tests specified generally.
 
No test data specified.
 
Acceptance criteria are poorly worded and hard to understand

Acceptance criteria are vague and ambiguous

Test results generalized and reported qualitatively.
 
 

Version Control (10 marks)

Criteria
High Distinction 
Distinction 
Credit
Pass
Fail
How well does the student apply knowledge and skills to effectively utilize version control?
Tests committed to version control following the testing of each module.
 
All commits clearly and thoroughly commented
 
 
Tests committed to version control following the testing of each module.
 
 
Tests committed to version control at the end of each section of the assignment.
 
 
All tests committed to version control once at the end of test development.
 
 
No evidence version control was used.
 
 

 

 

Presentation
There are two aspects to the presentation of this assignment.

The first is a text file submitted through Turnitin which details where the version control repository for the assignment can be found, and where in that repository various assessable elements can be found. This document must be in Microsoft word compatible format, or a PDF.

The second aspect of the assignment is presented as a functional code repository containing the complete development history and code for the assignment. You should clearly comment the update which represents the point at which you submit the assignment.

It is critical that you do not delete the repository until after you have received your mark for thre assignment.


 

Requirements
As per the CSU Referencing Policy, each assessment item must indicate the style of referencing required for each task. Students should be directed to a single Guide that supports the required referencing style for each assessment task. For those tasks requiring the use of APA, students should be directed to the CSU Referencing website at http://student.csu.edu.au/study/referencing-at-csu 
Referencing requirements must be reflected in marking criteria

For this assessment you are required to use APA referencing to acknowledge the sources that you have used in preparing your assessment. Please refer to the CSU referencing guide http://student.csu.edu.au/study/referencing-at-csu. In addition a very useful tool for you to use that demonstrates how to correctly use in text referencing and the correct way to cite the reference in your reference list can be found at https://apps.csu.edu.au/reftool/apa-6
 