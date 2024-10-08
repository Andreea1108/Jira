# Testing Project for OpenCart

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice , using a live application.

Application under test : OpenCart.

Tools used: Jira, Zephyr Squad.

#### Revision History
| Date| Description | Author | Comment |
| :-----: | :---: | :---: | :---: |
| 27.07.2024 | Test Plan for OpenCart Version 3.0 | Andreea Dragastan |OpenCart Version 2.0 (initial version)|

#### Table of Content : 
#### 1. Introduction
    1. Project objective
    2. Functionalities in scope
    3. Functionalities and tests out of scope
#### 2. Test process
    1. Test planning
    2. Test analysis
    3. Test design
    4. Test implementation
    5. Test execution
    6. Test closure
    7. Test monitoring and control
#### 3. Test deliverables
    1. Test plan
    2. Epics and stories
    3. Tasks
    4. Test conditions
    5. Test cases
    6. Daily test summary reports
    7. Traceability matrix
    8. Test case results
    9. Bugs report
    
#### 4. Schedule

### 1.Introduction

OpenCart is free open source e-commerce platform for online merchants. OpenCart provides a professional and reliable foundation from which to build a successful online store. This foundation appeals to a wide variety of users; ranging from seasoned web developers looking for a user-friendly interface to use, to shop owners just launching their business online for the first time. OpenCart has an extensive amount of features that gives you a strong hold over the customization of your store. With OpenCart's tools, you can help your online shop live up to its fullest potential.

#### 1.1 Project Objective

The objective of this project is to increase the trust in the quality of the application, to find defects in the live software application, to evaluate the product risks of the application and to send back to the stakeholders information with regards to the testing process and the level of quality of the application after the improvement process. 

Application under test :
https://demo.opencart.com/admin/

Application documentation :
https://docs.opencart.com/en-gb/introduction/

#### 1.2 Functionalities in scope

For this version of the application the functionalities in the scope of testing are : 

- All the features of Admin Interface module, Catalog module, Profiles module and Sales module for the Web application which were defined in OpenCart business requirements : Adding Multiple Languages, Products, Attributes, Options , Adding New Profiles, Applying the profile to a product, Orders, Returns and Gift Vouchers.
- For the testing process we will use : functional testing, positive testing, negative testing, regression testing and retesting.
- The testing process will be focused on the following browsers : Chrome and Mozilla latest versions.

#### 1.3 Functionalities and tests out of scope

  - Non-functional testing like performance, stress, volume testing are out of scope;
  - Test process for mobile application is out of scope;
  - Other browsers except Chrome and Mozilla are out of scope;
  - Automation testing is beyond scope .

### 2. Test process

The test process was performed based on the standard test process as described below.

  #### 2.1 Test planning

The Test Plan is designed to describe all details of testing for all the modules from the OpenCart Demo application.
The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personal responsible for testing, the resources and schedule required to complete testing and the risks associated with the plan. The test plan that was created for this project can be found here : [Test Plan](https://github.com/Andreea1108/Jira/blob/ad00603e68120e0b315f0e436905919b01ed7a7a/Test%20Plan%20OpenCart.docx)

  Roles asigned to the project and persons allocated :
  
| Role 1| Alina Maria- Test lead - Will monitor the testing process |
| :-----: | :---: |
| Role 2 | Ana Gavrila- Junior Tester - Will write the test conditions and test cases for Adding Multiple Languages, Products, Attributes, Options | 
| Role 3 | Andreea Dragastan - Senior Tester - Will create the test conditions and test cases for Adding New Profiles, Applying the profile to a product, Orders, Returns and Gift Vouchers | 
| Role 4 | Giurgiu Alexandru - Tester - Will execute the test cases for Adding Multiple Languages, Products, Attributes, Options and will report the defects | 
| Role 5 | Sabin Bura - Senior Tester -  Will execute the test cases for Adding New Profiles, Applying the profile to a product, Orders, Returns and Gift Vouchers | 

Entry criteria :

- Functional business specifications are defined ;
- Roles and responsabilities have been allocated ;
- The test environment is up and running ;
- Initial risks were identified ;
- The test plan was created and test process is detailed for the functionalities in scope.

Exit criteria :

- All the test cases were executed ;
- 80% of test cases are passed ;
- The remaining defects/bugs have low severity and low priority ;
- The project deadline was reached ;
- The project budget was reached ;

Project risks : 

- The team does not have the proper knowledge and experience for web testing ;
- Test environment not working ;
- Short/tight deadlines ;
- Due to the company changes we might have levers .

Product risks :

 - Taking into account that Admin is  the only module in scope of testing, the rest of them will be at risk of not fulfilling the user needs ;
 - Validation constraints on some of the fields might be too restrictive .

#### 2.2 Test analysis 

- Analyze the business requirements to make sure that we have all the details for creating the test conditions ;
- Write test conditions that will be tested in our testing process : [Test Conditions](https://github.com/Andreea1108/Jira/blob/7b330e0974f6692275286bc8d5dcbf25dc5f7f9a/Test%20conditions.png)

![Test Conditions](https://github.com/Andreea1108/Jira/blob/e5c169df6f1acd55a275edc7eb46873727c3f5b8/Test%20conditions.png)

#### 2.3 Test design

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here : [Test Cases](https://github.com/Andreea1108/Jira/blob/e2190aaccbfc11b837aacdc6d245688356bc330a/Test%20Case-uri.pdf)

#### 2.4 Test implementation

- Verify if the test environment is up and running ;
- Access to the test environment is given: valid username and valid password ;
- Create test suites (Test cycles) ;
- We prioritize the test cases based on risks and business priority .

#### 2.5 Test execution

- Test cases are executed on the created test Cycle summary V1.0 ;
- Bugs have been created based on the failed tests.The complete bug reports can be found here : [Bugs](https://github.com/Andreea1108/Jira/blob/2477378c2e5fbadd58955244b2c8662e3c0b9420/Bug-uri.pdf) ;
- Regression pack has been ran ;
- Retesting for the bugs that are fixed by the developers to validate that they issues are not reproduced .

#### 2.6 Test closure

- Analyze if the exit criteria were met and the testing process can be closed ;
- The traceability matrix was generated and can be found here : [Traceability matrix](https://github.com/Andreea1108/Jira/blob/c380a88eb339cd31b2f7a0b7400dd725db38cfef/Export%20Traceability%20Matrix.xlsx)

Accordingly to the below traceability matrix , we can find the following : 

- 9 stories created;
- 20 test cases : one test case for SAD-10, two test cases for SAD-13, seven test cases for SAD-18, one test case for SAD-35, two test cases for SAD-38, one test case for SAD-43, three test cases for SAD-47, one test case for SAD-54 and one test case for SAD-58.
- 6 bugs found : one bug for test case SAD-40 -> story SAD-38, one bug for test case SAD-30 -> story SAD-18, one bug for test case SAD-22 -> story SAD-18, one bug for test case SAD-24 -> story SAD-18, one bug for test case SAD-53 -> story SAD-47 and one bug for test case SAD-56 -> story SAD-54.

![Daily report](https://github.com/Andreea1108/Jira/blob/c25bd3fd20e483fe19ad502649c463365d4b1aa2/Matrice%201.png)
![Daily report](https://github.com/Andreea1108/Jira/blob/c25bd3fd20e483fe19ad502649c463365d4b1aa2/Matrice%202.png)
![Daily report](https://github.com/Andreea1108/Jira/blob/c25bd3fd20e483fe19ad502649c463365d4b1aa2/Matrice%203.png)
![Daily report](https://github.com/Andreea1108/Jira/blob/c25bd3fd20e483fe19ad502649c463365d4b1aa2/Matrice%204.png)
![Daily report](https://github.com/Andreea1108/Jira/blob/c25bd3fd20e483fe19ad502649c463365d4b1aa2/Matrice%205.png)

- Test execution chart was generated and can be found here : [Test execution](https://github.com/Andreea1108/Jira/blob/b7f5ff9b1070d9682ebcce25b01d4365784a94f8/Test%20Execution.png)

Accordingly to the below test execution, we can find the following : 

- for Admin Interface epic , all the tests were successfully executed ;
- for the other three epics,some of tests were passed and the others failed.

![Test Execution](https://github.com/Andreea1108/Jira/blob/main/Test%20Execution.png)

- Generate the test completion report .

#### 2.7 Test monitoring and control

In this phase various periodic reports will be generated to reflect the current status of the testing process. In case of major problems, control measures could be taken.
The Daily report was generated and can be found here : [Daily Report](https://github.com/Andreea1108/Jira/blob/71dc11734f6f9963d0c3cc2c5421e7f21ed4234e/Daily%20Report.png)

![Daily report](https://github.com/Andreea1108/Jira/blob/main/Daily%20Report.png)

### 3. Test deliverables

The following test deliverables will be provided by the end of the testing process and sent to the stakeholders in order to create the basis of informed decision : 

- Test plan : [Test Plan](https://github.com/Andreea1108/Jira/blob/ad00603e68120e0b315f0e436905919b01ed7a7a/Test%20Plan%20OpenCart.docx)
- Epics and stories : [Epic-uri si Story-uri](https://github.com/Andreea1108/Jira/blob/1047611afaa4ecd2d15af0be700fccfa02241193/Epic-uri%20si%20Story-uri.pdf)
- Tasks : [Tasks](https://github.com/Andreea1108/Jira/blob/2477378c2e5fbadd58955244b2c8662e3c0b9420/Task-uri.pdf)
- Test conditions : [Test Conditions](https://github.com/Andreea1108/Jira/blob/7b330e0974f6692275286bc8d5dcbf25dc5f7f9a/Test%20conditions.png)
- Test cases results : [Test Cases](https://github.com/Andreea1108/Jira/blob/e2190aaccbfc11b837aacdc6d245688356bc330a/Test%20Case-uri.pdf)
- Daily test summary report : [Daily Report](https://github.com/Andreea1108/Jira/blob/71dc11734f6f9963d0c3cc2c5421e7f21ed4234e/Daily%20Report.png)
- Traceability matrix : [Traceability matrix](https://github.com/Andreea1108/Jira/blob/c380a88eb339cd31b2f7a0b7400dd725db38cfef/Export%20Traceability%20Matrix.xlsx)
- Bugs report : [Bugs](https://github.com/Andreea1108/Jira/blob/2477378c2e5fbadd58955244b2c8662e3c0b9420/Bug-uri.pdf)
- Test execution : [Test execution](https://github.com/Andreea1108/Jira/blob/b7f5ff9b1070d9682ebcce25b01d4365784a94f8/Test%20Execution.png)

### 4. Schedule

- The testing process will take place over a period of 1.5 months and will involve all the activities defined in the previous section ;
- All the resources will be adapted accordingly in case new testing resources are detected as necessary .

### Conclusions

Following the testing, I created 20 tests which were successfully executed and all the requirements for the purpose have been covered.
All the defects found, will impact the launch of the product in production because the end user will not be able to place an order for a product, will not be able to set the payment frequency and he will not be able to print the order or return the product , if this is desired.So they can't be fixed later.












