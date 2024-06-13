# Testing Project for SwagLabs Demo
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: [SwagLabs Demo](https://www.saucedemo.com/v1/inventory.html)

Tools used: Jira, Zephyr Squad.

Functional specifications:
The below stories were created in Jira and describes the functional specifications of the User Experience module, for which the final project is performed upon.

![image](https://github.com/AnaIreneClita/Jira/assets/159917083/e297db49-35bf-44fd-919e-30aae487a533)

![image](https://github.com/AnaIreneClita/Jira/assets/159917083/74f9e9fd-5b55-4634-86e9-bb826d46f188)


Here you can find the release that was created for this project:

![image](https://github.com/AnaIreneClita/Jira/assets/159917083/316215d5-2f11-4e54-ad48-d695287b533d)
![image](https://github.com/AnaIreneClita/Jira/assets/159917083/816d8dd6-999e-4f93-bda9-6b170cbf9ddf)
![image](https://github.com/AnaIreneClita/Jira/assets/159917083/e5eec503-30ac-4fde-a931-97eb6e5f43d1)


Testing process
The test process was performed based on the standard test process as described below.

# 1.1 Test planning

The Test Plan is designed to describe all details of testing for all the modules from the SwagLabs Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here (inserati link catre documentul cu planul de testare)

# 1.1.1. Roles asigned to the project and persons allocated

| Project Manager  | Product Owner   | Software Developer | QA Engineer     |
|------------------|-----------------|---------------------|------------------|
| Jane Doe         | John Doe        | Doe Doe            | Ana Clita       |

# 1.1.2 Entry criteria defined

- Documentation Review
- Environment Setup
- Feature Completeness
- Content Readiness
- User Permissions
- Accessibility and Compatibility
- Testing Tools and Data

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
Tests in scope:

1. Functional Testing:

- Product browsing and filtering.
- Adding products to cart and managing cart items.
- Checkout process (guest checkout, registered user checkout).
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

Tests not in scope:

1. Physical Product Quality Testing:

- Evaluation of the physical quality of clothing items (e.g., fabric durability, stitching quality).
  
2. Backend System Integration Testing:

- Testing backend integrations with third-party systems (e.g., ERP, CRM).

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

Project risks:
- Inefficient communication
- Budget overrun
- Lack of resources
- Technology-related risks
- Change in requirements
- Delivery delays

Product risks:
- Compatibility
- Slow loading
- Image quality
- Improper functionality
- Complicated navigation

# 1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

# 1.2 Test Monitoring and Control
(inserati aici motivul pentru care a fost facuta etapa de monitorizare si control si respectiv cum s-a facut aceasta etapa. Aici veti insera de asemenea si raportul de status (test status report) din zephyr - test metrics - primul din lista care sa reflecte activitatea si evolutia testarii. Recomand aici sa executati teste aproape in fiecare zi ca sa vada angajatorul implicarea voastra in testare)

![image](https://github.com/AnaIreneClita/Jira/assets/159917083/5dd2a7c1-fab8-408b-90c3-806b017d38b0)


# 1.3 Test Analysis
The testing process will be executed based on the application requirements.

The following test conditions were found:
- Access filtering options
- Apply filters
- Filtering results are displayed
- Selecting a product for additional details
- ‘Add to Cart’ button visibility on product listing page
- ‘Add to Cart’ button visibility on product details page
- Product list page ‘Add to Cart’ button functionality
- Product details page ‘Add to Cart’ button functionality
- Product addition from product details page
- Access to shopping cart and viewing of added products
- Successful purchase and order placement  

# 1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here (inserati linkul catre fisierul cu testele, in format pdf, word sau csv)

# 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

(inserati lista de elemente care sunt evaluate in etapa de implementare)

# 1.6. Test Execution
Test cases are executed on the created test Cycle summary: [FinalProject](https://itfclasses.atlassian.net/projects/ANACL?selectedItem=com.thed.zephyr.je__cycle-summary)

Bugs have been created based on the failed tests. The complete bug reports can be found here: [bug_reports.pdf](https://github.com/user-attachments/files/15820914/bug_reports.pdf)


The following is a summary of the bugs that have been found:
- Filtering not displaying products in alphabetical order (Z-A) - low priority, medium severity
- Filtering not displaying products in price order (low to high) - low priority, medium severity
- Filtering not displaying products in price order (high to low) - low priority, medium severity
- Products details page not opening when products price is clicked - low priority, medium severity
- No products display the correct title - urgent priority, high severity
- No products display the correct image - urgent priority, high severity
- No products display the correct price - urgent priority, high severity
- No products display the correct description - urgent priority, high severity
- 'Add to cart' button doesn't change for the second product on the first column - urgent priority, high severity
- 'Add to cart' button doesn't change for the second product on the second column - urgent priority, high severity
- 'Add to cart' button doesn't change for the third product on the second column - urgent priority, high severity
- 'Add to cart' button doesn't work for the second product on the first column - urgent priority, high severity
- 'Add to cart' button doesn't work for the second product on the second column - urgent priority, high severity
- 'Add to cart' button doesn't work for the third product on the second column - urgent priority, high severity
- 'Add to cart' button doesn't work for the first product on the first column - urgent priority, high severity
- 'Add to cart' button doesn't work for the third product on the first column - urgent priority, high severity
- 'Add to cart' button doesn't work for the first product on the second column - urgent priority, high severity
- 'Add to cart' button doesn't change for the first product on the first column - urgent priority, high severity
- 'Add to cart' button doesn't change for the third product on the first column - urgent priority, high severity
- 'Add to cart' button doesn't change for the first product on the second column - urgent priority, high severity
- 'Add to cart' button doesn't work for the first product on the first column - urgent priority, high severity
- 'Add to cart' button doesn't work for the third product on the first column - urgent priority, high severity
- 'Add to cart' button doesn't work for the first product on the second column - urgent priority, high severity
- 'Your Information' fields can't be completed - urgent priority, high severity

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

# 1.7 Test Completion As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

[forward_traceability.xlsx](https://github.com/user-attachments/files/15821441/forward_traceability.xlsx)

Test execution chart was generated and can be found below.

![image](https://github.com/AnaIreneClita/Jira/assets/159917083/dd9a31f1-d572-413b-a81b-3acd3765dfca)

The final report shows that a number 8 tests have failed of a total of 12.

A number of 24 total bugs were found, from which the priority is: 20 of them are high and 4 of them are medium.

(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)
