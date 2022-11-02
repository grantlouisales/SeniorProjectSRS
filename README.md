# QA Campain Service Software Requirements Specification

<br>

## **Author: Grant Ales**

<br>

## **Table of Contents**
* [1.1 Purpose](#1.1-purpose)
* [1.2 Scope](#1.2-scope)
    * [1.2.1 Product](#1.2.1-product)
    * [1.2.2 Product's Functionality](#1.2.2-Product's-Functionality)
    * [1.2.3 Included Core Features](#1.2.3-core-features) 
* [1.3 Overview](#1.3-overview) 
* [1.4 Workflow](#1.4-workflow) 
    * [1.4.1 Coding](#1.4.1-coding) 
    * [1.4.2 Design](#1.4.2-design) 
    * [1.4.3 Learning Model](#1.4.3-learning-model) 
    * [1.4.4 Architecture](#1.4.4-architecture)
    * [1.4.5 Quality Assurance Characteristics](#1.4.5-quality-assurance-characteristics) 
    * [1.4.6 Metrics](#1.4.6-metrics) 
    * [1.4.7 Security Risks](#1.4.7-security-risks) 
* [1.5 User Profiles](#1.5-user-profiles) 
* [2.1 User Profiles](#2.1-requirements) 
* [2.2 Functional Requirements](#2.2-functional-requirements) 
* [2.3 Performance Requirements](#2.3-performance-requirements) 
* [2.4 Logical Database Requirements](#2.4-logical-database-requirements) 
* [2.5 System Requirements](#2.5-system-requirements) 
* [2.6 External System Requirements](#2.6-external-system-requirements) 




<br>

# 1.1 Purpose <a name="1.1-purpose"/>
- The QA campaign service will be used by FamilySearch to automate the process of campaign email data. This data includes ancestor information and will be used to determine stale data, valid relationships between patron and ancestor, and valid campaign landing pages.

<br>

# 1.2 Scope <a name="1.2-scope"/>
The scope of the QA campaign service will be a java web service. This will allow the backend developers to use this to test the email data that was populated by their backend services.

## 1.2.1 Product<a name="1.2.1-product" />
The product that the SRS will describe:

- QA Campaign Service

<br>

## 1.2.2 Product's Functionality<a name="1.2.2-Product's-Functionality" />
The functionality of the QA campaign service:

- The qa campaign service will automate the process of quality assurance on the email data for FamilySearch global campaigns.

<br>

## 1.2.3 Included Core Features <a name="1.2.3-core-features" />
The core features of the QA campaign service:

- Validation test on email data file.
- API calls to check valid relationships between patron and ancestor.
- User Interface testing on campaign landing pages.
- Cancelation of QA tasks.
- Endpoint to get status using the job id.
- All features can be done in integration, beta, and production.

<br>

# 1.3 Overview <a name="1.3-overview" />
The overview for the QA campaign service will be that it will follow a list of standards and expectations. Things to know about the service:
- The QA campaign service will only be used Quality Assurance means.
- The QA campaign service will be a 3rd tier Family Search service.
- The QA campaign service will be using a SQL database.
- The QA campaign service will only be used by Family Search.
- The QA campaign service will use AWS to host the web service.
- The QA campaign service will use Github for version control.

<br>

# 1.4 Workflow <a name="1.4-workflow"/>
The workflow of the QA campaign service will be the standards to be followed.

### 1.4.1 Coding <a name="1.4.1-coding" />
The language the QA campaign service will be coded in:

- Java

<br>

### 1.4.2 Design <a name="1.4.2-design" />
The designs used for the QA campaign service will be:
- flowcharts
- pseudocode
- structure charts
- class diagrams

<br>

### 1.4.3 Learning Model <a name="1.4.3-learning-model" />
The learning models that will be used are:
- Confluence
- Springboot documentation
- Java documentation
- Peers
- Baeldung

<br>

### 1.4.4 Architecture <a name="1.4.4-architecture" />
The QA campaign service will have meetings with the organizations architectual design council to help form the architecture of the service. 

The QA campaign service will have code reviews with other developers to ensure efficiency is at a professional level.

<br>


### 1.4.5 Quality Assurance Characteristics <a name="1.4.5-quality-assurance-characteristics" />
The QA campaign service will have unit tests that will keep the code coverage percentage about 70%.

<br>

### 1.4.6 Metrics <a name="1.4.6-metrics" />
The QA campaign service will follow the Family Search metrics to make sure the service does
not fall below performance expectations.

<br>

### 1.4.6 Security Risks <a name="1.4.7-security-risks" />
Since the QA campaign service will be a 3rd tier service there will be little to no security risks. The security risks for the QA campaign service will be:
- Outdated Operating Systems
- Weak passwords

<br>

# 1.5 User Profiles <a name="1.5-user-profiles"/>
The QA campaign service users will be the QA and backend teams for the global campaigns team.

<br>

# 2.1 Requirements <a name="2.1-requirements" />
The requirements will be what the QA campaign service must include. This section will have the details for the service regarding the functions of the service, the performance of the service, the database actions used for the service, and the system requirements for the service.

<br>

# 2.2 Functional Requirements <a name="2.2-functional-requirements" />
This functional requirements section will go over the main functions of the QA campaign service.

***2.2.1***  The QA campaign service shall do a validation test on the email data file. <br>
***2.2.2***  The QA campaign service shall make API calls calls to check valid relationships for the patron. <br>
***2.2.3***  The QA campaign service shall make API calls calls to check valid relationships for the ancestor. <br>
***2.2.4***  The QA campaign service shall test campaign landing pages user interfaces. <br>
***2.2.5***  The QA campaign service shall cancel running validation tasks. <br>
***2.2.6***  The QA campaign service shall be testable in integration. <br>
***2.2.7***  The QA campaign service shall be testable in beta. <br>
***2.2.8***  The QA campaign service shall be testable in production. <br>
***2.2.9***  The QA campaign service shall log errors to Splunk. <br>
***2.2.10*** The QA campaign service shall have aws kick off unit tests regularly. <br>
***2.2.11*** The QA campaign service shall have aws kick off acceptance tests regularly. <br>


<br>

# 2.3 Performance Requirements <a name="2.3-performance-requirements" />
The performance requirements section will talk about all the requirements regarding the performance of the QA campaign service.

***2.3.1*** The QA campaign service shall complete the validation test on the email data file in less than 3 minutes. <br>
***2.3.2*** The QA campaign service shall use multi-thread processing to quickly make API calls. <br>
***2.3.3*** The QA campaign service shall cancel a task soon after calling the endpoint. <br>
***2.3.4*** The QA campaign service shall start a validation task soon after calling the endpoint. <br>
***2.3.5*** The QA campaign service shall get the task details soon after calling the endpoint.
***2.3.6*** The QA campaign service shall notify developers when performance falls below a determined percentage. <br> 

<br>

# 2.4 Logical Database Requirements <a name="2.4-logical-database-requirements" />
The logical database requirements section will talk about all the requirements for the QA campaign service database.

***2.4.1*** The QA campaign service shall use a SQL database. <br>
***2.4.2*** The QA campaign service shall use the database to retrieve tasks. <br>
***2.4.3*** The QA campaign service shall use the database to cancel tasks. <br>
***2.4.4*** The QA campaign service shall use the database to start tasks. <br>
***2.4.5*** The QA campaign service shall use the database hold information on the campaign task. <br>
***2.4.6*** The QA campaign service shall use the database manipulate information on the campaign task. <br>
***2.4.7*** The QA campaign service shall use the database to log errors. <br>
***2.4.8*** The QA campaign service database shall have a data retention policy. <br>

<br>

# 2.5 System Requirements <a name="2.5-system-requirements" />
The system requirements section will talk about all the requirements for the QA campaign service system.

***2.5.1*** The QA campaign service shall use multiple threads to process email data. <br>
***2.5.2*** The QA campaign service shall be available through all web browsers. <br>

<br>

# 2.6 External System Requirements <a name="2.6-external-system-requirements" />
The external requirements section will talk about all the requirements for external services needed for the QA campaign service.

***2.6.1*** The QA campaign service shall use AWS to host the web service. <br>
***2.6.2*** The QA campaign service shall use GitHub for version control. <br>
***2.6.3*** The QA campaign service shall use Splunk for quality control. <br>
***2.6.4*** The QA campaign service shall use CloudBees to handle integration. <br>
***2.6.5*** The QA campaign service shall use PostMan to call the endpoints. <br>
***2.6.6*** The QA campaign service shall use JFrog to handle the services artifacts. <br>
***2.6.7*** The QA campaign service shall use OKTA for service management. <br>

<br>