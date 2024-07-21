# OpenCart
#### Revision History
| Date| Description | Author | Comment |
| :-----: | :---: | :---: | :---: |
| 27.03.2024 | Test Plan for OpenCart Version 3.0 | Andreea Dragastan |OpenCart Version 2.0 (initial version)|
| 03.04.2024 | Added more details for 2.4 Test Implementation  | Ioana Popescu | Test Plan Version 2.1 |
#### Table of Content : 
1. Introduction
    1. Project objective
    2. Functionalities in scope
    3. Functionalities and tests out of scope
2. Test process
    1. Test planning
    2. Test analysis
    3. Test design
    4. Test implementation
    5. Test execution
    6. Test closure
    7. Test monitoring and control
3. Test deliverables
    1. Test plan
    2. Test conditions
    3. Test cases
    4. Daily test summary reports
    5. Traceability matrix
    6. Test case results
    7. Bugs report
    8. Test completion report
4. Schedule

1.Introduction

OpenCart is free open source e-commerce platform for online merchants. OpenCart provides a professional and reliable foundation from which to build a successful online store. This foundation appeals to a wide variety of users; ranging from seasoned web developers looking for a user-friendly interface to use, to shop owners just launching their business online for the first time. OpenCart has an extensive amount of features that gives you a strong hold over the customization of your store. With OpenCart's tools, you can help your online shop live up to its fullest potential.

1.1 Project Objective

The objective of this project is to increase the trust in the quality of the application, to find defects in the live software application, to evaluate the product risks of the application, and to send back to the stakeholders information with regards to the testing process and the level of quality of the application after the improvement process. 

Application under test :
https://demo.opencart.com/admin/

Application documentation :
https://docs.opencart.com/en-gb/introduction/

1.2 Functionalities in scope

For this version of the application the functionalities in the scope of testing are : 

- All the features of Admin Interface module for the Web application which were defined in OpenCart business requirements : Overview, Filter, Image Manager,, Adding Multiple Languages,Creating a Multi-Store,Moving a OpenCart to a New Server,SEO Keywords , SSL Certificates and HTTPS,Basic Security Practices.
- For the testing process we will use : functional testing, positive testing, negative testing, regression testing and retesting.
- The testing process will be focused on the following browsers : Chrome and Mozilla latest versions.

1.3 Functionalities and tests out of scope

  - Non-functional testing like performance, stress, volume testing are out of scope;
  - Test process for mobile application is out of scope;
  - Other browsers except Chrome and Mozilla are out of scope;
  - Automation testing is beyond scope .

2. Test process

  Test planning :
  Roles and responsibilities
  
| Role 1|Alina Maria- Test lead - Will monitor the testing process|
| :-----: | :---: |
| Role 2 | Ana Gavrila- Junior Tester - Will write the test conditions and test cases for Overview, Filter and Image Manager | 
| Role 3 | Boier Alexandru - Senior Tester - Will create the test conditions and test cases for Adding Multiple Languages and Creating a Multi-Store and Moving a OpenCart to a New Server | 
| Role 4 | Giurgiu Alexandru - Tester - Will execute the test cases for Overview, Filter and Image Manager and report the defects | 
| Role 5 | Sabin Bura - Senior Tester -  Will execute the test cases for Adding Multiple Languages and Creating a Multi-Store and Moving a OpenCart to a New Server | 

Entry criteria :

- Functional business specifications are defined ;
- Roles and responsabilities have been allocated ;
- The test environment is up and running ;
- Initial risks were identified ;
- The test plan was created and test process is detailed for the functionalities in scope.

Exit criteria :

- All the test cases were executed ;
- 90% of test cases are passed ;
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

2.2 Test analysis 

- Analyze the business requirements to make sure that we have all the details for creating the test conditions ;
- Write test conditions that will be tested in our testing process.

2.3 Test design

In this phase we will create the test cases based on the previously defined test conditions.

2.4 Test implementation

- Verify if the test environment is up and running ;
- Access to the test environment is given: valid username and valid password ;
- Create test suites (Test cycles) ;
- We prioritize the test cases based on risks and business priority .

2.5 Test execution

- All functional test cases cases created in Test Design phase are executed and we set the test case status(passed/failed) ;
- For the test cases failed we will raise defects ;
- Regression pack has been ran ;
- Retesting for the bugs that are fixed by the developers to validate that they issues are not reproduced .

2.6 Test closure

- Analyze if the exit criteria were met and the testing process can be closed ;
- Generate the traceability matrix ;
- Generate the test completion report .

2.7 Test monitoring and control

In this phase various periodic reports will be generated to reflect the current status of the testing process. In case of major problems, control measures could be taken.

3. Test deliverables

The following test deliverables will be provided by the end of the testing process and sent to the stakeholders in order to create the basis of informed decision : 

- Test plan ;
- Test conditions ;
- Test cases ;
- Daily test summary report ;
- Traceability matrix ;
- Test case results ;
- Bugs report ;
- Test completion report .

4. Schedule

- The testing process will take place over a period of 1.5 months and will involve all the activities defined in the previous section ;
- All the resources will be adapted accordingly in case new testing resources are detected as necessary .















