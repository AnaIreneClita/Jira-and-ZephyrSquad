# Testing Project for SwagLabs Demo
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: [SwagLabs Demo](https://www.saucedemo.com/v1/inventory.html)

## Use the following info to log in: 
- user: problem_user
- password: secret_sauce

**Tools used**: Jira, Zephyr Squad.

Functional specifications:
The below **stories** were created in Jira and describes the functional specifications of the User Shopping Experience module, for which the final project is performed upon.

![image](https://github.com/AnaIreneClita/Jira-and-ZephyrSquad/assets/159917083/02f9332c-c8f0-4282-b7fd-e73a42cb322a)
![image](https://github.com/AnaIreneClita/Jira-and-ZephyrSquad/assets/159917083/efcc1a03-d340-41cf-91c2-f581173282cc)



Here you can find the **release** that was created for this project:

![image](https://github.com/AnaIreneClita/Jira-and-ZephyrSquad/assets/159917083/2e76789b-ada4-4f6f-98dd-bc5c16290838)
![image](https://github.com/AnaIreneClita/Jira-and-ZephyrSquad/assets/159917083/0b92464c-f398-4fdc-b078-a48a0b7fe69e)
![image](https://github.com/AnaIreneClita/Jira-and-ZephyrSquad/assets/159917083/e0ce762c-e8a8-4773-ad70-455cf3a1e579)



Testing process

 - The test process was performed based on the standard test process as described below.


# 1.1 Test planning

The Test Plan is designed to describe all details of testing for all the modules from the SwagLabs Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. 

The **test plan** that was created for this project can be found here: [test_plan.docx](https://github.com/user-attachments/files/15841562/test_plan.docx)

The **business requirements** document that was created for this project can be found here: [business_requirements.pdf](https://github.com/user-attachments/files/15826554/business_requirements.pdf)


# 1.1.1. Roles asigned to the project and persons allocated

| Project Manager  | Product Owner   | Software Developer | QA Engineer     |
|------------------|-----------------|---------------------|------------------|
| Jane Doe         | John Doe        | Doe Doe            | Ana Clita       |


# 1.1.2 Entry criteria defined

- Business Requirements Readiness
- Test Plan Readiness
- Roles are Allocated


# 1.1.3 Exit criteria defined

- Functional Coverage
- Performance and Scalability
- Security
- Usability and User Experience
- Cross-Browser and Cross-Device Compatibility
- Regression Testing
- Documentation and Reporting
- Approval and Sign-Off


# 1.1.4 Test scope
## Tests in scope:

1. Functional Testing:

- Product browsing and filtering.
- Adding products to cart and managing cart items.
- Checkout process.
- Payment processing (credit card, PayPal, etc.).
- Order management (viewing orders, order history).

2. Compatibility Testing:

- Testing on various browsers: Chrome, Firefox, Safari, Edge.
- Testing on different devices: Desktop, laptop, tablets, smartphones (iOS, Android).

3. Performance Testing:

- Load testing to ensure the website handles concurrent user traffic.
- Stress testing to determine system stability under peak load conditions.
- Response time testing for critical user actions (e.g., product search, checkout).

4. Security Testing:

- Vulnerability assessment (penetration testing) to identify potential security risks.
- Data encryption testing to ensure customer data security during transactions.
- Authentication and authorization checks for user roles and permissions.

5. Usability Testing:

- User interface (UI) testing to evaluate design consistency and user experience.
- Navigation testing to ensure intuitive browsing and ease of finding products.
- Accessibility testing to verify compliance with WCAG guidelines for users with disabilities.

## Tests not in scope:

1. Physical Product Quality Testing:

- Evaluation of the physical quality of clothing items (e.g., fabric durability, stitching quality).
  
2. Backend System Integration Testing:

- Testing backend integrations with third-party systems.

3. Geolocation-based Pricing Testing:

- Testing pricing variations based on user location.

4. Legacy Browser Compatibility:

- Testing on outdated browsers that are no longer supported by the website.
  
5. Advanced Network Security Testing:

- Deep analysis of network security protocols beyond the website’s scope.

6. Regulatory Compliance Testing:

- Compliance testing with industry-specific regulations (e.g., GDPR, CCPA).

7. Localization and Translation Testing:

- Testing localized versions of the website in different languages.


# 1.1.5 Risks detected

## Project risks:
- Inefficient communication
- Budget overrun
- Lack of resources
- Technology-related risks
- Change in requirements
- Delivery delays

## Product risks:
- Compatibility with Internet Explorer
- Slow loading
- Image quality
- Improper functionality
- Complicated navigation


# 1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.


# 1.2 Test Monitoring and Control
## Reason for the monitoring and control stage:

- The monitoring and control stage in testing is crucial for tracking the progress of testing, identifying deviations from the initial plan, and ensuring that objectives and acceptance criteria are efficiently met. This stage allows the testing team to adapt strategies and activities in real-time based on the results and findings from the testing process.

## How the monitoring and control stage was conducted:

- I implemented the monitoring and control stage using Zephyr for Jira to manage and report testing progress effectively. Here’s how I we managed this stage:
- Defining objectives and KPIs: I established clear testing objectives and key performance indicators (KPIs) to assess the quality and coverage of the tests.
- Planning testing activities: I regularly executed tests to continuously monitor and evaluate the status and progress of testing. I ensured comprehensive test coverage to detect and report defects at an early stage.
- Generating **status report**s: I used Zephyr to generate regular status reports, including test status reports and testing metrics such as the number of planned tests, executed tests, and their outcomes. These reports reflected daily activity and the evolution of testing in a transparent and detailed manner.

![image](https://github.com/AnaIreneClita/Jira-and-ZephyrSquad/assets/159917083/8844b229-2557-44fe-8bc5-b4e636a67ac1)




# 1.3 Test Analysis
The testing process will be executed based on the application requirements.

The following **test conditions** were found:

- Verify That The User Can Filter Search Results By Alphabetical Order
- Verify That The User Can Filter Search Results By Price
- Verify That By Clicking On A Product The Products Details Page Opens Displaying The Correct Information
- Verify That By Clicking On 'Add To Cart' The Product From The Product Listing Page Is Added To Cart
- Verify That The Shopping Cart And Its Content Can Be Accessed
- Verify That The Order Placement Process Can Be Made Successfully
- Verify That By Clicking On 'Add To Cart’ The Product From The Product Details Page Is Added To Cart


# 1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The **test cases** can be accessed here: [test_cases.pdf](https://github.com/userattachments/files/16169603/test_cases.pdf)


# 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

- Testing Environment
- Testing Tools
- Test Data


# 1.6. Test Execution
**Test cases** are executed on the created test Cycle summary: [FinalProject](https://itfclasses.atlassian.net/projects/ANACL?selectedItem=com.thed.zephyr.je__cycle-summary)


Bugs have been created based on the failed tests. The complete **bug reports** can be found here: [bug_reports.pdf](https://github.com/user-attachments/files/16169607/bug_reports.pdf)

The following is a **summary** of the bugs that have been found:

- Filtering not displaying products in alphabetical order (Z-A) - medium priority, low severity
- Filtering not displaying products in price order (low to high) - medium priority, low severity
- Filtering not displaying products in price order (high to low) - medium priority, low severity
- Products details page not opening when products price is clicked - medium priority, low severity
- No products display the correct title - high priority, very high severity
- No products display the correct image - high priority, very high severity
- No products display the correct price - high priority, very high severity
- No products display the correct description - high priority, very high severity
- 'Add to cart' button doesn't change for the second product on the first column - high priority, very high severity
- 'Add to cart' button doesn't change for the second product on the second column - high priority, very high severity
- 'Add to cart' button doesn't change for the third product on the second column - high priority, very high severity
- 'Add to cart' button doesn't work for the second product on the first column - high priority, very high severity
- 'Add to cart' button doesn't work for the second product on the second column - high priority, very high severity
- 'Add to cart' button doesn't work for the third product on the second column - high priority, very high severity
- 'Add to cart' button doesn't work for the first product on the first column - high priority, very high severity
- 'Add to cart' button doesn't work for the third product on the first column - high priority, very high severity
- 'Add to cart' button doesn't work for the first product on the second column - high priority, very high severity
- 'Add to cart' button doesn't change for the first product on the first column - high priority, very high severity
- 'Add to cart' button doesn't change for the third product on the first column - high priority, very high severity
- 'Add to cart' button doesn't change for the first product on the second column - high priority, very high severity
- 'Add to cart' button doesn't work for the first product on the first column - high priority, very high severity
- 'Add to cart' button doesn't work for the third product on the first column - high priority, very high severity
- 'Add to cart' button doesn't work for the first product on the second column - high priority, very high severity
- 'Your Information' fields can't be completed - high priority, very high severity

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.


# 1.7 Test Completion As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

**Traceability matrix** was generated and can be found below. 

![image](https://github.com/AnaIreneClita/Jira-and-ZephyrSquad/assets/159917083/11497091-3132-4000-9d1f-ed33c3291321)
![image](https://github.com/AnaIreneClita/Jira-and-ZephyrSquad/assets/159917083/3b3feae2-bafb-4a57-bc7c-c823b8bf3228)




**Test execution chart** was generated and can be found below.

![Screenshot 2024-07-11 004506](https://github.com/AnaIreneClita/Jira-and-ZephyrSquad/assets/159917083/5a8f4203-e282-4de2-9b37-a59e47754c6a)




The final report shows that a number 7 tests have **failed** of a total of 7.

A number of 24 **total bugs** were found, from which the priority is: 20 of them are high and 4 of them are medium.

The total number of **stories**, both planned and executed, is 2.

The total number of written and executed **tests** is 7.

The number of identified **bugs** is 24.

There are 4 bugs with a severity level of **"medium"**. These bugs are related to product filtering, which doesn't prevent users from viewing basic product details or successfully initiating and completing the purchase process. However, they may affect users by making it cumbersome to access products under certain desired conditions and by limiting the visibility of complete product descriptions. This can potentially mislead users when they intend to make a purchase, risking a sense of deception and a perceived lack of transparency on the website.

There are 20 bugs with a severity level of **"high"**. These bugs directly impact the accurate display of product information and all aspects related to the purchase process. They prevent users from seeing real product information, leading to confusion regarding product titles, descriptions, images, and prices, thus reducing user trust in the website. Additionally, these bugs affect the initiation and completion of the purchase process. They can frustrate users and also bring financial and possibly legal issues to the website.
