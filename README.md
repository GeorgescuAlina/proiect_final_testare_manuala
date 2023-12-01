# Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: https://www.emag.ro/

Application documentation: 

- https://www.emag.ro/help/cum-compari-mai-multe-produse/
- https://www.emag.ro/help/recomandari-clienti/


**The final project will have a section: [Testing section](https://github.com/julai215/itf_final_project_example_and_portofolio/blob/main/Final%20Project/README.md#1-testing-section)**


# 1 Testing section

## 1.1 Test Planning

The Test Plan is designed to describe all details of testing for specific features of the website:

- Implement personalized recommendations for users
- Introduction of the product comparison option

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

#### 1.1.1 Roles assigned to the project and persons allocated

| Job Title                  | Number of Employees |
|----------------------------|---------------------|
| Product Manager            | 1                   |
| Business Analyst           | 1                   |
| UX/UI Designer             | 1                   |
| Software Developer (Frontend) | 2                |
| Software Developer (Backend)  | 2                |
| Quality Assurance Tester   | 1                   |
| Database Administrator     | 1                   |
| System Architect           | 1                   |
| Project Manager             | 1                   |
| Technical Support Engineer  | 1                   |


#### 1.1.2 Entry criteria defined

1. **Implement Personalized Recommendations for Users:**
   - **Algorithm Selection:** Choose and finalize the recommendation algorithm(s) to be implemented.
   - **User Interface Design:** Have the user interface design for presenting recommendations ready and approved.
   - **User Story Acceptance Criteria:** Clearly define and agree upon the acceptance criteria for the user story, outlining what constitutes a successfully implemented personalized recommendation feature.

2. **Introduction of the Product Comparison Option:**
   - **Product Database:** Ensure that a comprehensive and up-to-date product database is available.
   - **User Interface Design:** Have the user interface design for the product comparison feature ready and approved.
   - **Comparison Criteria:** Define and agree upon the criteria for product comparison (e.g., features, specifications) and ensure they are documented.
   - **Backend Support:** Confirm that the backend systems support the retrieval and processing of data required for product comparison.
   - **User Story Acceptance Criteria:** Clearly define and agree upon the acceptance criteria for the user story, outlining what constitutes a successfully implemented product comparison option.

#### 1.1.3 Exit criteria defined

1. Implement Personalized Recommendations for Users:

- **User Testing:** User testing has been conducted, and feedback indicates a positive response to personalized recommendations.
- **Integration with UI:** Personalized recommendations are seamlessly integrated into the user interface and have a visually appealing presentation.
- **Documentation:** Complete documentation, including user guides and system manuals for the personalized recommendation feature.

2. Introduction of the Product Comparison Option:

- **Functionality Testing:** The product comparison option functions as intended, meeting all defined criteria for comparison.
- **User Testing:** User testing confirms that the product comparison feature is intuitive, user-friendly, and aligns with user expectations.
- **Integration with UI:** The product comparison option is seamlessly integrated into the user interface, providing a smooth user experience.
- **Documentation:** Complete documentation, including user guides and system manuals for the product comparison feature.

3. General Exit Criteria for Both Stories:

- **Regression Testing:** Regression testing has been successfully performed, ensuring that new features have not negatively impacted existing functionality.
- **Code Review:** A thorough code review has been conducted, confirming adherence to coding standards and best practices.
- **Performance Testing:** Performance testing, if applicable, has been conducted to ensure that the new features do not negatively impact system performance.
- **User Acceptance:** User acceptance has been obtained, and users have signed off, confirming that the implemented features meet their expectations and requirements.
- **Deployment Readiness:** The code is ready for deployment, and all necessary deployment procedures are documented.


#### 1.1.4 Test scope

1. **Implement Personalized Recommendations for Users:**
   
   - *Tests in Scope:*
     - Integration testing to ensure seamless integration with the existing system.
     - User interface testing to verify the proper display of personalized recommendations.
     - User acceptance testing to validate that the personalized recommendations meet user expectations.

   - *Tests not in Scope:*
     - Security testing 
     - Unit testing 
     - Load testing beyond performance testing scope.

3. **Introduction of the Product Comparison Option:**
   
   - *Tests in Scope:*
     - Functionality testing to ensure that the product comparison feature meets defined criteria.
     - User interface testing to verify a seamless and user-friendly integration.
     - Cross-browser and cross-device testing for consistent behavior.
     - User acceptance testing to confirm alignment with user expectations.

   - *Tests not in Scope:*
     - Performance testing 
     - Security testing 
     - Unit testing 


#### 1.1.5 Risks detected

Project Risks:

1. **Resource Constraints:** Insufficient availability of skilled resources for development, testing, or other project activities.

2. **Timeline Delays:** Unforeseen challenges or scope changes that lead to project timeline delays.

3. **Scope Creep:** Uncontrolled expansion of project scope, leading to increased workload and potential delays.

4. **Communication Breakdown:** Ineffective communication among team members, stakeholders, or between development and testing teams.

5. **Technical Debt:** Accumulation of technical debt due to shortcuts or compromises made during development.

Product Risks:

1. **Algorithm Accuracy:** Inaccuracy or ineffectiveness of the personalized recommendation algorithm.

2. **User Adoption:** Low user adoption of the personalized recommendation or product comparison features.

3. **Data Privacy and Security:** Breach of user data privacy or security vulnerabilities in the recommendation or comparison features.

4. **Integration Risks:** Anticipate potential challenges in seamlessly integrating the new features with existing systems or databases. Assess the risk of encountering difficulties that could impact the overall performance and functionality of the product.

5. **Usability Issues:** Poor user experience due to usability issues in the recommendation or product comparison interfaces.
   

#### 1.1.6 Evaluating entry criteria

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue. 

## 1.2 Test Monitoring and Control

It will be done by generating periodic reports that reflect the current status of the test. It will include:

* Daily test execution overview by status 
  
![image](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/7645c8d8-5f42-4184-aa96-6be7e0436ce0)

#### Test Execution Completion Over Time by Status:

- 6 November 2023: 22.22% tests failed, 77.78% passed.
- 11 November 2023: 100% pass rate.
- 18 November 2023: 100% pass rate.

Analysis: There was an improvement in test execution results over time. Initially, on November 6th, there was a relatively high failure rate with some defects reported, but by November 11th and 18th when the issues were fixed, the pass rate reached 100%.

![image](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/b2877735-9d53-4e2d-9f99-ebb85d3638c7)

#### Zephyr Squad - Test Execution Results by Test Cycle:

- TMGAM-R1: Pass rate 80%, Fail rate 20%.
- TMGAM-R2: Pass rate 60%, Fail rate 20%, Skipped rate 20%.
- TMGAM-R3: Pass rate 100%.
- TMGAM-R4: Pass rate 100%.
- TMGAM-R5: Pass rate 100%.
- TMGAM-R6: Pass rate 100%.

Analysis: Each test cycle has different pass rates. TMGAM-R2 has a skipped rate, and TMGAM-R1 has a relatively lower pass rate compared to the others.

* Test Execution Metrics

![image](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/b5bb651f-bd19-49a4-b43c-08ae29c243da)

#### Test Execution Completion Over Time - Chart:

- 6 November 2023: 9 tests executed.
- 11 November 2023: 10 tests executed.
- 18 November 2023: 10 tests executed.
  
Analysis: The number of executed tests remains consistent from November 11th to 18th, indicating a stable testing effort.

#### Test Execution Results Overall:

- Total number of executed tests in cycles: 29 out of 30 completed.

Analysis: There is one test cycle (out of a total of 30) that is not completed. This incomplete cycle may need attention to ensure comprehensive test coverage.

#### Regarding Test Control, we will:

* Prioritizing the testing efforts
* Reorganizing the test environment
* Re-prioritizing the test cases

In summary, the testing progress has shown improvement over time with a significant increase in the pass rate. The distribution of pass rates across different test cycles suggests variations in the testing effectiveness. The stability in the number of executed tests and the identification of one incomplete cycle highlight areas for potential focus and improvement in the testing process.

## 1.3 Test Analysis

The testing process will be executed based on the above requirements for the NEW graphic interface of OpenCart application. The following test conditions were found:

**Implement personalized recommendations for users**

- Testing the display of at least 5 personalized recommendations.
- Testing the real-time updating of recommendations.
- Testing the functionality of hiding recommendations.
- Verification of the database for storing user history.
- Monitoring the performance of the recommendation system.

**Introduction of the product comparison option**
  
- Testing the addition of products to the comparison list.
- Testing the display of detailed information in the comparison list.
- Testing the removal of products from the comparison list.
- Verification of compatibility across various browsers and devices.
- Testing the storage and synchronization of the comparison list across devices.

## 1.4 Test Design

The stories:


![Story 1](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/827feb0b-b918-4705-9e20-538448af7c83)


![Story 2](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/510a6377-6f03-4956-be69-733cfe607320)


Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases 
are:

**Implement Personalized Recommendations for Users:**

- Displaying and Hiding Recommendations
- Real-time Update Test and Adding a Recommended Product to Cart
- Displaying Recommendations for New Users
- Customizing Recommendations Based on Category
- System Resilience Test in Case of Error

**Introduction of the Product Comparison Option:**

- Adding and Removing Products from the Comparison List
- Displaying an Empty Comparison List
- Displaying Product Comparison Results
- Displaying an Error Message When Adding More Than 5 Products to the Comparison List
- Synchronization Test between Devices

All the testcases can be found in the repository here: [Test_cases_Excel](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/blob/main/Test_Cases.xlsx)
And all a detailed test execution results here: [Test_cases_PDF](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/blob/main/Zephyr%20Squad%20-%20JiraTests.pdf)

Here are some examples of test-cases:

![image](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/1526d6a9-e00c-4cdf-81bf-a74c54844a43)

![image](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/45e015cb-8443-403c-90b0-3c950e386391)


## 1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

* The test cases are written for the story to be tested
* The story was implement and the code was deployed to the testing environment
* The tester is using a stable internet connection (15-20 megabits-per-second Mb/s at a minimum)
* The tester is able to use a laptop or PC with Windows operating system
* The Chrome/Firefox/Safari/Opera browsers are installed

## 1.6 Test Execution

Test cases are executed on the created test Cycle summary, here is a complete report of a test cycle:


![Test Cycle](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/361d0bad-94f3-4d16-8040-2a5494140660)


* Bugs have been created based on the failed tests. 
    * Incorrect display of the number of personalized recommendations (3 instead of 5)
    * Error connecting when attempting to remove a product from the comparison list

A complete example of the bugs can be found in the following PDF files: [bug_1 PDF](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/blob/main/TMGAM-3.pdf) [bug_2 PDF](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/blob/main/TMGAM-4.pdf)

Here are some screenshots of reported bugs:

![image](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/c90fb0c2-d06e-4bc3-b5e1-40d18e49eeea)

![image](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/cc250edb-89d9-46b8-ad2d-fb8f47a8b7ab)

## 1.7 Test Completion

* Exit criteria was evaluated and passed
* Tracebility matrix was generated - Coverage: Stories & Test-Cases & Test Execution Results & Issues

The tracebility matrix below provides a comprehensive overview of the coverage between user stories, test cases, test execution results, and identified issues within a project. It allows stakeholders to quickly assess the alignment between requirements, corresponding test cases, and the current status of test execution. This matrix aids in tracking progress, ensuring that all planned tests have been executed, and providing visibility into any issues that may impact the overall testing and development process. The summary serves as a valuable reference for project teams to make informed decisions, prioritize work, and maintain a transparent and well-coordinated testing effort.

![traceability](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/54bcf307-96af-422c-85c8-dcf58fb86240)

* Test execution charts

Test execution charts offer visual representations of the testing progress and results within a project. These charts include information on the number of test cases executed, passed, failed, and any tests currently in progress. They provide stakeholders with a quick and intuitive overview of the testing status, allowing them to assess the overall health of the project at a glance. Test execution charts help in identifying trends, tracking testing efficiency, and making data-driven decisions. The visual nature of these charts enhances communication and understanding among team members, enabling more effective collaboration and timely response to testing challenges.

![image](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/4825ac3f-88dd-4322-a71d-be6ae5f961be)

* Test execution detailed examples

![image](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/53d14982-8075-4ec8-8fe2-79013545359d)

![image](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/41989b17-94a4-404c-aac8-4ff769d61622)

## 1.7 Conclusions

## Test Results:

- 10 tests were created and executed to validate the new functionalities.
- Approximately 95% of the specific requirements were covered in testing.
- All planned functionalities were successfully tested, except for the Product Comparison Option functionality, where a blocker was reported.
- Two bugs were identified, of which one has been resolved, and one awaits further resolution.

## Impact on Release:

- The identified bugs have a significant impact on the product's production release.
- All critical issues are currently being addressed with remediation plans in place.

## Risks and Mitigations:

- **[Risk]:** The high complexity of the new functionality may lead to the omission of critical testing scenarios.
  **[Mitigation]:** Early involvement of the testing team in the design and specification phase of the functionality to identify and address potential complexities.

- **[Risk]:** Time constraints for testing due to a tight release schedule.
  **[Mitigation]:** Prioritization of tests based on risks and impact and additional involvement of the testing team in the final development phase.

## Lessons Learned:

- It is essential to involve the testing team from the project planning phase.
- Effective communication between development and testing teams is key to success.

## Recommendations for Future Projects:

- Improve communication and collaboration between development and testing teams to ensure a clear understanding of requirements and priorities.
- Implementing an automated regression testing process could enhance testing efficiency.



