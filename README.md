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

<br>

# 1.1 Purpose <a name="1.1-purpose"/>
- The QA campaign service will be used by FamilySearch to automate the process of campaign email data. This data includes ancestor information and will be used to determine stale data, valid relationship between patron and ancestor, and valid campaign landing pages.

<br>

# 1.2 Scope <a name="1.2-scope"/>
The scope of the QA campaign service will be a java web service. This will allow the backend developers to use this with their programs.

## 1.2.1 Product<a name="1.2.1-product" />
The product that the SRS will describe:

- QA Campaign Service

<br>

## 1.2.2 Product's Functionality<a name="1.2.2-Product's-Functionality" />
The functionality of the QA campaign service:

- The qa campaign service will automate the process of quality assurance on the email data for FamilySearch campaigns.

<br>

## 1.2.3 Included Core Features <a name="1.2.3-core-features" />
The core features of the QA campaign service:

- Validation test on email data file.
- API calls to check valid relationship between patron and ancestor.
- User Interface testing on campaign landing pages.
- Cancelation of QA tasks.
- All features can be done in integration, beta, and production.

<br>

# 1.3 Overview <a name="1.3-overview" />
The overview for the QA campaign service will work with internal family search services.

## 1.3.1 Product perspective <a name="1.3.1-product-perspective" />
This will be a list of interfaces the QA campaign service will interact with as well as other product perspectives.

<br>

### 1.3.1.1 System Interfaces <a name="1.3.1.1-system-interface" />
The system interfaces will be the programs or applications it will run on.

- The QA campaign service will run on webservices.
- The QA campaign service will connect to Family Search authentication services.

<br>

### 1.3.1.2 User Interfaces <a name="1.3.1.2-user-interface" />
The user interfaces will be what the user will see.

- The QA campaign service will use postman to call the endpoints.
- The QA campaign service will use Splunk to visualize the data results of the service.

<br>

### 1.3.1.3 Hardware Interfaces <a name="1.3.1.3-hardware-interface" />
The hardware for the QA campaign service will be:

- Any computer.

<br>

### 1.3.1.4 Software Interfaces <a name="1.3.1.4-software-interface" />
The software interfaces will be the language or programs used for the service.

- Operating Systems:
    - The QA campaign service shall be able to use windows operating systems.
    - The QA campaign service shall be able to use  Mac operating systems.
    - The QA campaign service shall be able to use linux operating systems.

<br>

### 1.3.1.5 Memory <a name="1.3.1.5-memory" />
This will talk about proper memory handling for the QA campaign service.

- The QA campaign service shall download a file from a database.
- The QA campaign service shall delete the file after use.
- The QA campaign service shall have a memory retention plan.

<br>

### 1.3.1.6 Operations <a name="1.3.1.6-operations" />
- Operations by the user shall include:
    - Validation test on email data file.
    - API calls to check valid relationship between patron and ancestor.
    - User Interface testing on campaign landing pages.
    - Cancelation of QA tasks.
    - All features can be done in integration, beta, and production.
