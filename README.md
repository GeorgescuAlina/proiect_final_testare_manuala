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
   - **Data Availability:** Ensure that sufficient user data, including preferences, history, and any relevant information, is available and accessible.
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

1. **Implement Personalized Recommendations for Users:**
   - **Algorithm Validation:** Ensure that the personalized recommendation algorithm has been validated and meets the defined accuracy and performance criteria.
   - **User Testing:** Conduct user testing to verify that the personalized recommendations are well-received and effective in a real-world scenario.
   - **Integration with UI:** Confirm that the personalized recommendations have been seamlessly integrated into the user interface and are visually appealing.
   - **Documentation:** Ensure that documentation for the implemented feature, including any necessary user guides or system manuals, is complete.

2. **Introduction of the Product Comparison Option:**
   - **Functionality Testing:** Verify that the product comparison option functions as intended and meets the defined criteria for comparison.
   - **User Testing:** Conduct user testing to ensure that the product comparison feature is user-friendly and aligns with user expectations.
   - **Integration with UI:** Confirm that the product comparison option has been seamlessly integrated into the user interface and provides a smooth user experience.
   - **Documentation:** Ensure that documentation for the implemented feature, including any necessary user guides or system manuals, is complete.

3. **General Exit Criteria for Both Stories:**
   - **Regression Testing:** Perform regression testing to ensure that the new features have not negatively impacted existing functionality.
   - **Code Review:** Conduct a thorough code review to ensure adherence to coding standards and best practices.
   - **Performance Testing:** If applicable, conduct performance testing to ensure that the new features do not negatively impact system performance.
   - **User Acceptance:** Obtain user acceptance and sign-off, confirming that the implemented features meet user expectations and requirements.
   - **Deployment Readiness:** Ensure that the code is ready for deployment and all necessary deployment procedures are documented.

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

4. **Integration Challenges:** Difficulties in integrating the new features with existing systems or databases.

5. **Usability Issues:** Poor user experience due to usability issues in the recommendation or product comparison interfaces.
   

#### 1.1.6 Evaluating entry criteria

The entry criterias defined in the Test Planning phase have been achieved and the test process can continue. 

## 1.2 Test Monitoring and Control

It will be done by generating periodic reports that reflect the current status of the test. It will include:

* Daily test execution progress
  
![image](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/deb1a65a-9b20-487d-a8bc-9254a4ddf901)

![image](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/d414e037-e8e3-49f4-9112-3e9d0ef3ae38)

* Test Execution Metrics

![image](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/59b0b0c1-f35f-4609-b932-17630592e256)


#### Regarding Test Control, we will:

* Prioritizing the testing efforts
* Reorganizing the test environment
* Re-prioritizing the test cases

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

Here are someexample of reported bugs:

![image](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/c90fb0c2-d06e-4bc3-b5e1-40d18e49eeea)

![image](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/cc250edb-89d9-46b8-ad2d-fb8f47a8b7ab)

## 1.7 Test Completion

* Exit criteria was evaluated and passed
* The traceability matrix was generated and can be found here:

Tracebility matrix - Coverage: Stories & Test-Cases & Test Execution Results & Issues

![traceability](https://github.com/GeorgescuAlina/proiect_final_testare_manuala/assets/135150078/54bcf307-96af-422c-85c8-dcf58fb86240)

* TO BE ADDED - Test execution chart was generated, the final report shows.... -> describe the final report
  
![image](https://github.com/GeorgescuAlina/proiect-testare-manuala-it-factory/assets/135150078/0f3e4eab-0455-4a8d-a142-831c7a9058ae)

