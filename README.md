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
    * [1.4.4 Quality Assurance Characteristics](#1.4.4-quality-assurance-characteristics) 
    * [1.4.5 Metrics](#1.4.5-metrics) 
    * [1.4.6 Security Risks](#1.4.6-security-risks) 


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

### 1.4.4 Quality Assurance Characteristics <a name="1.4.4-quality-assurance-characteristics" />
The QA campaign service will have unit tests that will keep the code coverage percentage about 70%.

<br>

### 1.4.5 Metrics <a name="1.4.5-metrics" />
The QA campaign service will follow the Family Search metrics to make sure the service does
not fall below performance expectations.

<br>

### 1.4.6 Security Risks <a name="1.4.6-security-risks" />
Since the QA campaign service will be a 3rd tier service there will be little to no security risks. The security risks for the QA campaign service will be:
- Outdated Operating Systems
- Weak passwords

<br>


# 2.1 Requirements <a name="2.1-requirements" />