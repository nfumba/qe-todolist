  # 1. Introduction 

    The Test Plan Outlines the scope , resources , and schedule of all testing activities. It identifies the items and features to be tested; types of testing. It contains a detailed testing objective specific to particular system, the testing aproach , test environment , test conditions and the test plan.

# 2. Scope

Future Requirements for mobile testing

# 3. Out of Scope 

Futre requirement number 9

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

 Performance Testing

Performing testing is conducted to detect issues related to:

memory consumption
power utilization
network connectivity
operating in the background
switching between applications
memory leakage

 **5.1 Interrupt Testing**

This testing type examines how an application reacts to interruption and resumes to its previous state. There are numerous reasons that can potentially interrupt the operation of an app, such as getting a phone call, messages, notifications, battery low, etc. 

**5.2**  Usability Testing

Usability testing is performed to check whether the application is easy to use and understand for the end-user.

**5.3** Installation and Launch testing

Installation testing aims to detect whether there are any issues during the installation, uninstallation, and updating process. Once the application has been installed, a QA engineer also checks the launching process. 


**5.4** Functional Testing

All the functions and features of the application are tested to verify whether they operate according to the specification.

**5.5** Security testing

Security testing is conducted to find the application vulnerabilities and prevent data breaches.

**5.6** Regression testing

Regression testing is a re-execution of tests that had been done before the code changes. Its purpose is to verify whether a new functionality has affected the existing one.

2.3 Pass/Fail Conditions

All the conditions when tests pass or fail are defined and described.

# 5.5. Automation Testing: 

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

