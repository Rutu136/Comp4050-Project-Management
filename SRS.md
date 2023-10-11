# Software Requirements Specification Template

**Software Engineering**

The following annotated template shall be used to complete the Software Requirements Specification (SRS) assignment.

**Template Usage:**

Text contained within angle brackets (`<`, `>`) shall be replaced by your project-specific information and/or details. For example, `<Project Name>` will be replaced with either 'Smart Home' or 'Sensor Network'.

Italicized text is included to briefly annotate the purpose of each section within this template. This text should not appear in the final version of your submitted SRS.

**Acknowledgements:**

Sections of this document are based upon the IEEE Guide to Software Requirements Specification (ANSI/IEEE Std. 830-1984). The SRS templates of Dr. Lawrence Chung (UTD) have also been used as guides in developing this template.


<div class="page-break"></div>

**Project Name:** Online Virtual Phone System

**Version:** 1.0

**Date:** October 09, 2023

**Team Name:** Team Endgame

<div class="page-break"></div>

## Revision History

| **Date** | **Description** | **Author** | **Comments** |
| --- | --- | --- | --- |
| <date> | <Version 1> | <Your Name> | <First Revision> |

<div class="page-break"></div>

## TABLE OF CONTENTS

[1. Introduction](#1.-Introduction)

[1.1 Purpose](#1.1-Purpose)
[1.2 Definitions, Acronyms, and Abbreviations](#1.2-Definitions-Acronyms-and-Abbreviations)

[1.3 References](#1.3-References)

[2. General Description](#2.-General-Description)

[2.1 User Characteristics](#2.1-User-Characteristics)

[2.2 Assumptions and Dependencies](#2.2-Assumptions-and-Dependencies)

[3. Specific Requirements](#3.-Specific-Requirements)

[3.1 Functional Requirements](#3.1-Functional-Requirements)

[3.2 Non-Functional Requirements](#3.2-Non-Functional-Requirements)

[3.2.1 Performance](#3.2.1-Performance)
[3.2.2 Reliability](#3.2.2-Reliability)

[3.2.3 Availability](#3.2.3-Availability)

[3.2.4 Security](#3.2.4-Security)

[3.2.5 Interfaces](#3.2.5-Interfaces)

[3.3 Design Constraints](#3.3-Design-Constraints)

[3.4 Legal, Copyright, and Other Notices](#3.4-Legal-Copyright-and-Other-Notices)

[3.5 Other Requirements](#3.5-Other-Requirements)

[4 Other Supporting Documents](#4-Other-Supporting-Documents)

[A. Appendices](#A-Appendices)

<div class="page-break"></div>

## 1. Introduction

(_You may need to refine your scope/purpose defined in the project charter after eliciting requirements with stakeholders_)

The introduction to the Software Requirement Specification (SRS) document should provide an overview of the complete SRS document. While writing this document, please remember that this document should contain all of the information needed by a software engineer to adequately design and implement the software product described by the requirements listed in this document. (Note: the following subsection annotates are largely taken from the IEEE Guide to SRS).

### 1.1 Purpose

_What is the purpose of this SRS and the (intended) audience for which it is written._

### 1.2 Definitions, Acronyms, and Abbreviations

_This subsection should provide the definitions of all terms, acronyms, and abbreviations required to properly interpret the SRS. This information may be provided by reference to one or more appendices in the SRS or by reference to other documents._

### 1.3 References

_This subsection should:_

_(1) Provide a complete list of all documents referenced elsewhere in the SRS, or in a separate, specified document._

_(2) Identify each document by title, report number - if applicable - date, and publishing organization._

_(3) Specify the sources from which the references can be obtained._

_This information may be provided by reference to an appendix or to another document._

<div class="page-break"></div>

## 2. General Description

### 2.1 User Characteristics

The users for the product will fall into one of two categories: administrator or user. 

The users will be adults, located at various locations across the globe with various levels of internet strength and reliability. Given the geographic diversity of the users, not everyone will speak the same language. The users will be using the product for both professional and personal use. As such the user may be an individual or a business, requiring extensions to reach multiple departments within the business. Users are expected to have varying levels of technical literacy. 

Administrators will be IT professionals with extensive knowledge and training and strong techinical literacy. These users will be located in Canada with a strong, reliable internet connection. 

### 2.2 Assumptions and Dependencies

It is assumed all users of the system will have the ability to connect to the internet with adequate speeds to allow for full functionality of the application. 

All users should have the necessary hardware and operating systems to support the app. We will accommodate operating systems from 2015-present day. Any operating systems that date back past 2015 will be incompatible. Hardware components such as a mobile device, desktop, speakers and microphones are assumed to be provided by the user.

Each user will have the ability to make a payment digitally via credit card or PayPal using CAD as the currency of choice. Should the user prefer an alternative currency it is assumed that the third party chosen to manage and route the transactions will be responsible for the conversion and any inform the user of any fees imposed by the users bank. 

While not all users will be fluent in English, it is assumed the users will be familar enough with one of the 4 languages provided to navigate the app without too much difficulty. 

The app will depend on the use of third party services to manage payment. As such, agreements must be made between the Online Virtual Phone System and the chosen third party.

<div class="page-break"></div>

## 3. Specific Requirements

This will be the largest and most important section of the SRS. The customer requirements will be embodied within Section 2, but this section will give the D-requirements that are used to guide the project's software design, implementation, and testing.

### 3.1 Functional Requirements

This section describes specific features of the software project. Specify the requirements as user story.

…

<

Sell Configured to Ordered Products.

The system shall display all the products that can be configured.

The system shall allow the user to select the product to configure.

The system shall display all the available components of the product to configure

\>

…

### 3.2 Non-Functional Requirements

Non-functional requirements may exist for the following attributes. Often these requirements must be achieved at a system-wide level rather than at a unit level. State the requirements in the following sections in measurable terms (e.g., 95% of transactions shall be processed in less than a second, system downtime may not exceed 1 minute per day, > 30-day MTBF value, etc).

This section describes non-functional features of the software project. Specify the requirements as user story.

#### 3.2.1 Performance

The system shall handle all calls up a predefined maximum, determined by the administrators. 

The system shall record and display the system load in real time to the administrators.

The app startup time shall not exceed 3 seconds. 

The system audio quality shall meet a minimum mean opinion score (MOS) of 4. 

The system will provide voice calls with latency exceeding no more than 150ms.  

#### 3.2.2 Reliability

< The system shall provide RAID V Disk Stripping on all database storage disks. >

#### 3.2.3 Availability

< The system shall provide a contractual agreement with an internet service provider for T3 access with 99.9999% availability. >

#### 3.2.4 Security

The system will ensure a newly created password meets an adequate level of complexity.

The system shall store end-to-end encrypted passwords.

The system shall screen for incoming scam calls (ie. AI generated calls). 

The system shall not store any payment information nor will the system store any personal information in the form of cookies, etc.

Voice calls will be fully secure with end-to-end encryption. 

#### 3.2.5 Interfaces

##

### 3.3 Design Constraints

###

### 3.4 Legal, Copyright, and Other Notices

### 3.5 Other Requirements

Catchall section for any additional requirements.

## 4 Other Supporting Documents

# A. Appendices

Appendices may be used to provide additional (and hopefully helpful) information. If present, the SRS should explicitly state whether the information contained within an appendix is to be considered as a part of the SRS's overall set of requirements.

_Example Appendices could include (initial) conceptual documents for the software project, marketing materials, minutes of meetings with the customer(s), etc._
