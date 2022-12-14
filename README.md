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
    * [2.7 Validation Requirements](#2.7-validation-requirements) 
    * [2.8 Alerting Requirements](#2.8-alerting-requirements) 

* [3.1 Design Overview](#3.1-design-overview)
    * [3.2 Data](#3.2-data)
    * [3.3 Process Flow](#3.3-process-flow)
* [4.1 Verification](#4.1-verification)
    * [4.2 Functional Requirements Verification](#4.2-functional-requirements-verification) 
    * [4.3 Performance Requirements Verification](#4.3-performance-requirements-verification) 
    * [4.4 Logical Database Requirements Verification](#4.4-logical-database-requirements-verification) 
    * [4.5 System Requirements Verification](#4.5-system-requirements-verification) 
    * [4.6 External System Requirements Verification](#4.6-external-system-requirements-verification) 
    * [4.7 Validation Requirements Verification](#4.7-validation-requirements-verification) 
    * [4.8 Alerting Requirements Verification](#4.8-alerting-requirements-verification) 

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

# 2.7 Validation Requirements <a name="2.7-validation-requirements" />
The validation requirements section will talk about all the requirements for the main points of the validation section of the QA Campaign Service.

***2.7.1*** The QA campaign service validation test shall validate the format of the patron pid field. <br>
***2.7.2*** The QA campaign service validation test shall validate the format of the ancestor pid field. <br>
***2.7.3*** The QA campaign service validation test shall validate the format of the ahnentafel field. <br>
***2.7.4*** The QA campaign service validation test shall validate the format of the ancestor name field. <br>
***2.7.5*** The QA campaign service validation test shall validate the patron pid in the file is the same as the patrons actual pid. <br>
***2.7.6*** The QA campaign service validation test shall validate the ancestor pid in the file is the same as the ancestors actual pid. <br>
***2.7.7*** The QA campaign service validation test shall validate the ahnentafel in the file is the same as the ancestors actual ahnentafel. <br>
***2.7.8*** The QA campaign service validation test shall validate the ancestor name in the file is the same as the ancestor acutal name. <br>
***2.7.9*** The QA campaign service validation test shall validate the patron pid is not empty. <br>
***2.7.10*** The QA campaign service validation test shall validate the patron pid matches FamilySearch correct formatting. <br>
***2.7.11*** The QA campaign service validation test shall validate the ancestor pid is not empty. <br>
***2.7.12*** The QA campaign service validation test shall validate the ancestor pid matches FamilySearch formatting. <br>
***2.7.13*** The QA campaign service validation test shall validate the ahnentafel is not 0. <br>
***2.7.14*** The QA campaign service validation test shall validate the ancestor name is not empty. <br>

<br>

# 2.8 Alerting Requirements <a name="2.8-alerting-requirements" />
The alerting requirements section will talk about all the requirements for alerting for the QA Campaign service.

***2.8.1*** The QA campaign service shall send info alerts to Splunk. <br>
***2.8.2*** The QA campaign service shall send error alerts to Splunk. <br>
***2.8.3*** The QA campaign service shall send speacialized alerts to Splunk. <br>
***2.8.4*** The QA campaign service shall have Splunk document all monitoring of the service. <br>
***2.8.5*** The QA campaign service shall have CloudBees document every detail of the service. <br>
***2.8.6*** The QA campaign service shall have CloudBees notify developers when the service is down. <br>
***2.8.7*** The QA campaign service shall have Dynamax document every detail of the service. <br>
***2.8.8*** The QA campaign service shall have Dynamax notify developers when the service is down. <br>
***2.8.9*** The QA campaign service shall return a Job Id to use for a endpoint call. <br>
***2.8.10*** The QA campaign service shall receive a list of all errors for task with a endpoint call. <br>

<br>

# 3.1 Design Overview <a name="3.1-design-overview" />
This section will go over the way the program's design and workflow will happen.

***3.1.1*** The QA campaign service will call an endpoint to download the campaign data. <br>
***3.1.2*** The QA campaign service will then unzip that file and start doing validation tests on the whole file. <br>
***3.1.3*** The QA campaign service will then complete the validation tests and then call a findrelation endpoint to test the relationships of ancestor and patron. <br>
***3.1.4*** The QA campaign service will grab 20,000 random lines of data and make API calls on those lines of data using multi-thread processing. <br>
***3.1.5*** The QA campaign service will then test teh UI of the campaign pages using WebdriverIO. <br>
***3.1.6*** The QA campaign service will be able to cancel a task at any given point in the process. <br>
***3.1.7*** The QA campaign service will be run in integration, beta, or production at all times. <br>
***3.1.8*** The QA campaign service will send alerts to splunk during the entirity of the process. <br>
***3.1.9*** The QA campaign service will be hosted in AWS and will be a backend to QA service. <br>
***3.1.10*** The QA campaign service will lastly call an endpoint called qamarkedapprove to send the data to marketing if it passed all QA tests. <br>

<br>

# 3.2 Data <a name="3.2-data" />
This section will describe the data that is being used in the service.

***3.2.1*** The QA campaign service shall download a file from an endpoint. <br>
***3.2.2*** The QA campaign service shall delete the the file after the processing has been done. <br>
***3.2.3*** The QA campaign service shall have a data retention policy for the database. <br>
***3.2.4*** The QA campaign service shall store task details in a database.  <br>
***3.2.5*** The QA campaign service shall pass along information and task data to marketing once all the tests are passed. <br>

<br>

# 3.3 Process Flow <a name="3.3-process-flow" />

![Sequence Diagram](https://github.com/grantlouisales/SeniorProjectSRS/blob/main/Sequence%20Diagram.png) 

<br>

# 4.1 Verification <a name="4.1-verification" />
The verification section will go over all of the requirements above and explain how the verification for the requirements will be completed.

# 4.2 Functional Requirements Verification <a name="4.2-functional-requirements-verification" />
This functional requirements verification section will go over the verifications for the main functions of the QA campaign service.

***4.2.1***  The QA campaign service shall verify that validation tests on the email data file will happen. <br>
***4.2.2***  The QA campaign service shall verify that API calls will be made to check valid relationships for the patron. <br>
***4.2.3***  The QA campaign service shall verify that API calls will be made to check valid relationships for the ancestor. <br>
***4.2.4***  The QA campaign service shall verify that campaign landing pages user interfaces will be tested. <br>
***4.2.5***  The QA campaign service shall verify that running validation tasks can be canceled. <br>
***4.2.6***  The QA campaign service shall verify that it will be testable in integration. <br>
***4.2.7***  The QA campaign service shall verify that it will be testable in beta. <br>
***4.2.8***  The QA campaign service shall verify that it will be testable in production. <br>
***4.2.9***  The QA campaign service shall verify that it will log errors to Splunk. <br>
***4.2.10*** The QA campaign service shall have aws kick off unit tests regularly. <br>
***4.2.11*** The QA campaign service shall verify that aws will kick off acceptance tests regularly. <br>

<br>

# 4.3 Performance Requirements Verification <a name="4.3-performance-requirements-verification" />
The performance requirements verification section will talk about all verifications for the requirements regarding the performance of the QA campaign service.

***4.3.1*** The QA campaign service shall verify that it will complete the validation test on the email data file in less than 3 minutes. <br>
***4.3.2*** The QA campaign service shall verify that it will use multi-thread processing to quickly make API calls. <br>
***4.3.3*** The QA campaign service shall verify that it will cancel a task soon after calling the endpoint. <br>
***4.3.4*** The QA campaign service shall verify that it will start a validation task soon after calling the endpoint. <br>
***4.3.5*** The QA campaign service shall verify that it will get the task details soon after calling the endpoint.
***4.3.6*** The QA campaign service shall verify that it will notify developers when performance falls below a determined percentage. <br> 

<br>

# 4.4 Logical Database Requirements Verification <a name="4.4-logical-database-requirements-verification" />
The logical database requirements verification section will talk about all the verifications for the QA campaign service database.

***4.4.1*** The QA campaign service shall verify that it will use a SQL database. <br>
***4.4.2*** The QA campaign service shall verify that it will use the database to retrieve tasks. <br>
***4.4.3*** The QA campaign service shall verify that it will use the database to cancel tasks. <br>
***4.4.4*** The QA campaign service shall verify that it will use the database to start tasks. <br>
***4.4.5*** The QA campaign service shall verify that it will use the database hold information on the campaign task. <br>
***4.4.6*** The QA campaign service shall verify that it will use the database manipulate information on the campaign task. <br>
***4.4.7*** The QA campaign service shall verify that it will use the database to log errors. <br>
***4.4.8*** The QA campaign service database verify that it will shall have a data retention policy. <br>

<br>

# 4.5 System Requirements Verification <a name="4.5-system-requirements-verification" />
The system requirements verification section will talk about all the verifications for the QA campaign service system.

***4.5.1*** The QA campaign service shall verify that it will use multiple threads to process email data. <br>
***4.5.2*** The QA campaign service shall verify that it will be available through all web browsers. <br>

<br>

# 4.6 External System Requirements Verification <a name="4.6-external-system-requirements-verification" />
The external requirements section will talk about all the verifications for the external services needed for the QA campaign service.

***4.6.1*** The QA campaign service shall verify that it will use AWS to host the web service. <br>
***4.6.2*** The QA campaign service shall verify that it will use GitHub for version control. <br>
***4.6.3*** The QA campaign service shall verify that it will use Splunk for quality control. <br>
***4.6.4*** The QA campaign service shall verify that it will use CloudBees to handle integration. <br>
***4.6.5*** The QA campaign service shall verify that it will use PostMan to call the endpoints. <br>
***4.6.6*** The QA campaign service shall verify that it will use JFrog to handle the services artifacts. <br>
***4.6.7*** The QA campaign service shall verify that it will use OKTA for service management. <br>

<br>

# 4.7 Validation Requirements Verification <a name="4.7-validation-requirements-verification" />
The validation requirements section will talk about all the verifications for the validation needed for the QA campaign service.

***4.7.1*** The QA campaign service validation test shall verify the validation of the format of the patron pid field. <br>
***4.7.2*** The QA campaign service validation test shall verify the validation of the format of the ancestor pid field. <br>
***4.7.3*** The QA campaign service validation test shall verify the validation of the format of the ahnentafel field. <br>
***4.7.4*** The QA campaign service validation test shall verify the validation of the format of the ancestor name field. <br>
***4.7.5*** The QA campaign service validation test shall verify the validation of the patron pid in the file is the same as the patrons actual pid. <br>
***4.7.6*** The QA campaign service validation test shall verify the validation of the ancestor pid in the file is the same as the ancestors actual pid. <br>
***4.7.7*** The QA campaign service validation test shall verify the validation of the ahnentafel in the file is the same as the ancestors actual ahnentafel. <br>
***4.7.8*** The QA campaign service validation test shall verify the validation of the ancestor name in the file is the same as the ancestor acutal name. <br>
***4.7.9*** The QA campaign service validation test shall  verify the validation of the patron pid is not empty.  <br>
***4.7.10*** The QA campaign service validation test shall verify the validation of the patron pid matches FamilySearch correct formatting. <br>
***4.7.11*** The QA campaign service validation test shall verify the validation of the ancestor pid is not empty.  <br>
***4.7.12*** The QA campaign service validation test shall verify the validation of the ancestor pid matches FamilySearch formatting. <br>
***4.7.13*** The QA campaign service validation test shall verify the validation of the ahnentafel is not 0.  <br>
***4.7.14*** The QA campaign service validation test shall verify the validation of the ancestor name is not empty.  <br>

<br  

# 4.8 Alerting Requirements Verification <a name="4.8-alerting-requirements-verification" />
The alerting requirements section will talk about all the verifications for the alerting needed for the QA campaign service.

***4.8.1*** The QA campaign service shall verify that it will send info alerts to Splunk. <br>
***4.8.2*** The QA campaign service shall verify that it will send error alerts to Splunk. <br>
***4.8.3*** The QA campaign service shall verify that it will send speacialized alerts to Splunk. <br>
***4.8.4*** The QA campaign service shall verify that it will have Splunk document all monitoring of the service. <br>
***4.8.5*** The QA campaign service shall verify that it will have CloudBees document every detail of the service. <br>
***4.8.6*** The QA campaign service shall verify that it will have CloudBees notify developers when the service is down. <br>
***4.8.7*** The QA campaign service shall verify that it will have Dynamax document every detail of the service. <br>
***4.8.8*** The QA campaign service shall verify that it will have Dynamax notify developers when the service is down. <br>
***4.8.9*** The QA campaign service shall verify that it will return a Job Id to use for a endpoint call. <br>
***4.8.10*** The QA campaign service shall verify that it will receive a list of all errors for task with a endpoint call. <br>