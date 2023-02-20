# Table of Contents

1. Introduction
2. Scope 
3. Reference Document
4. Detailed Test Approach

    Test Strategy
    Test Schedule 
    Problem Severity Classification
    Test Resources 
    Pass/Fail Criteria
    Environment
    Test Cases and Test Scenarios
    Tools and Defect Tracking
    Final Test Report 
    Exit Criteria
    
# 1. Introduction 

    The Test Plan Outlines the scope , resources , and schedule of all testing activities. It identifies the items and features to be tested; types of testing. It contains a detailed testing objective specific to particular system, the testing aproach , test environment , test conditions and the test plan.

# 2. Scope
The scope of this test plan is to ensure that the Todo application meets all of its technical, functional and business requirements. The purpose of this document is to describe overall test plan and strategy of testing Todo application.The approach described in this document provides the framework for all the testing related to Todo Application. This document will also be updated as required with the requirement updates.We will also need to make sure that all the expected results are achieved.

# 3. Out of Scope 

The requirements listed in the future implimentation will not be tested with build/Release.

# 4. Test Objectives

The general objectives are to test the correctness  of the content of the data entered into the Application, and any error conditions. The quality objectives of testing Todo Application are to ensure complete validation of business and software requirements: 

Verify software requirements are complete and accurate

Identify testing standards and procedures that will be used while testing Todo Application

Prepare and document test scenarios and test cases 
Manage defect tracking process
Finalize the project for release 

# Reference Documents

README.md file

# 5. Detailed Test Approach

Detailed testing phases and methodologies are mentioned below. We will follow all protocols of each phase and we aim to achieve the highest results.

   # 5.1 Requirement Analysis 
   
   Requirements analysis is critical to the success or failure of a systems or software project so we have to verify, validate and confrm each requirement. Requirements must be validated on the basis of User Experience, User Interface, How to test the requirements, Requiremnts are up to date. 

**We will Analyze the following Requirements**

1. Application must be able to deploy in docker
2. Multiple users should be able to view the shared public todo list (no live updates, only on refresh)
3. Todo list items should persist after browser refresh
4. Todo items should not be able to be empty
5. Should be able to add todo items
6. Should be able to delete todo items
7. Should be able to edit todo items

   # 5.2 Design Testing 
   
   Test all the designs and verify that all the designs are correct as per the requirements. 
   
   # 5.3 Functionality Testing 
   
   Test the functional requirements and determine every function of the software is acting in accordance with the pre-determined requirements and tasks.For TodoList Application we will perform testing of the data input and output via the front end, Field used in the page for submitting or Updating information from user. Functional testing is extended to the types given below

   # 5.3.1 Testing the link

   - Testing if the link to ToDoList is accessable to users
   
   # 5.3.2 Testing of the forms on the web pages: 
    - Forms are used to get information from users and to keep interaction with them. 
    - The following should be checked on the forms: 
        > Check for the default values of felds.

        > Check all the validations on each feld. 

        > Wrong inputs to the felds in the forms. 
        
        > Options to create forms, if any, form delete, view or modify the forms. 

        > Check that no empty forms are created. 

        > There are different feld validations, all the above validations should be checked in a manual or an automated way.

 # 5.3.3 API Testing:

Set of procedures to verify the expected functionality, reliability, and security and ensure the correct interaction between backend and frontend. To validate the logic of the build architecture within a short amount of time. Each api test consists of some test actions mentioned below. Further details of API Testing will be covered in API Test Plan  

- Verify the endopoints accordingly 
    
- Verify required request headers and their correct values 

    - Add item : POST request
    - Update item : POST request
    - Delete item : GET requste
- Verify response payload Verify correct HTTP status code and response headers 

- Verify expected result and correct application state Verify correct performance sanity

# 5.4. Automation Testing: 

Automate all the implemented functinlaities of the ToDoList Application . Creation of the automation test cases. Details of Automation testing will be discussed and covered inside the Test Plan of automation testing. 
 
- Analysis of test cases which are possible to be automated 
- Plan the test cases and how to execute all the test cases.  
- write the logic for how to validate the test. 
- Write the pass/fail criteria agaist each test case. run and actually verify the test. 
- Integrate all the test cases of each feature/module

# 6. Test Strategy 

The overall strategy of this testing initiative is manual, black box testing. We are testing the data, interface part and implemented system in detail. Follow the testing phases and techniques mentioned inside “Detailed Test Approach”. 

Some of the test specifcations use test data which needs to be set-up in the test environment prior to executing the test cases. 

For each level of testing, a separate test plan is prepared with the following set of deliverables: 
- Test Cases/Test Sceanrios 
- Features to be tested 
- Items to be tested 
- Pass / Fail criteria 
- Bugs cycle 
- Automation 
- Expected Results 
- Actual Results


**Test Schdeule** 

The test schedule is the timeline of acceptance testing activities and deliverable dates. 

Testing activities are mentioned below. 
- Requirement Analysis. 
- Design Testing 
- Develop test scenarios 
- Develop test cases 
- Review scenarios/test cases for accuracy, completeness and sequence (confrm test data is correct) 
- Integration testing 
- Regression Testing 
- Functionality Testing (Front End)
- Integration Test 
- UAT Testing 
- Automation Testing 

**Problem/Bug Severity Classifcation:** 

The identifed severity for each problem implies a general reward for resolving it, and a general risk for not addressing it, in the current release. 
- Severity 1 - Crash or High impact problems that often prevent a user/host from correctly completing an experience/booking. - 
- Severity 2 - Moderate to high frequency problems with the functionality/UI or UX impact 
- Severity 3 - Either moderate problems with low frequency or low problems with moderate frequency; these are minor annoyance problems faced by a number of participants. 
- Severity 4 - Low impact problems faced by few participants; there is low risk of not resolving these problems. Reward for resolution is typically exhibited in increased user satisfaction.

# 7. Test Resources 
Here is the list of resources with the roles those will work on Todo Application 

1. Jane Doe - QE Lead
2. Valentine - QE Specialist

# 8. Pass/Fail Criteria: 
The expected results/pass criteria will be mentioned against each testcase. 

# 9. Environment 

Start testing on a Test server once a certain level is achieved, then move to PreProduction and give the fnal approval at PreProduction. 

# 10. Test Cases and Test Scenarios 
- Verify if user can successfully add ToDo Item
- Verify if user can successfully delete ToDo Item 
- Verify if the list persist after refresh 
- Veryfy if the list can NOT be empty 
- Very if the app can be deployed in Docker 
- Verify if proper errors are retunerd
- Verify if link is accessable 
 
 # 11. Tools and defect Tracking 
 
 Jira wil be used for defect reporting and issue bugs/defects management and traceability. 
 
 # 12. Final Test Report 
 
 Test closure reports shall be generated for each testing phase as the testing phase gets completed. 
 
 # 13. Exit Criteria 
 
 All the test cases and test scenarios must be passed. 

