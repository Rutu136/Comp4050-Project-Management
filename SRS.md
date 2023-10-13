<center><H1>
<br></br>
<br></br>
<br></br>
Online Virtual Phone System
<br></br>
Software Requirements Specification Template
<br></br>
Version 1.1
<br></br>
October 09, 2023
<br></br>
<br></br>
<br></br>
Team Endgame
<br></br>
<br></br>
<br></br>
<br></br>
<br></br>
<br></br>
</H1>
</center>

<div style="page-break-after: always;"></div>

## Revision History

| **Date** | **Version** | **Description** | **Author** |
| --- | --- | --- | --- |
| 2023-10-09 | Version 1.0 | Converted to markdown format | Dharmit Anghan |
| 2023-10-09 | Version 1.1 | Added Introduction, purpose, definitions, and references | Dharmit Anghan |
| 2023-10-10 | Version 1.2 | Added function requirement and Reliability | Rutu Barvaliya |
| 2023-10-12 | Version 1.3 | Added safety/performance requirements and general description | Breanna Brown |
| 2023-10-13 | Version 1.4 | Added Availability | Dharmit Anghan |

<div style="page-break-after: always;"></div>

<center><H1>TABLE OF CONTENTS</H1></center>

[1. Introduction](#1-introduction)

- [1.1 Purpose](#11-purpose)
- [1.2 Definitions, Acronyms, and Abbreviations](#12-definitions-acronyms-and-abbreviations)
- [1.3 References](#13-references)

[2. General Description](#2-general-description)

- [2.1 User Characteristics](#21-user-characteristics)

- [2.2 Assumptions and Dependencies](#22-assumptions-and-dependencies)

[3. Specific Requirements](#3-specific-requirements)

- [3.1 Functional Requirements](#31-functional-requirements)
    - [3.1.1 Authentication](#311-authentication)
    - [3.1.2 User Account Management](#312-user-account-management)
    - [3.1.3 Search Functionality](#313-search-functionality)
    - [3.1.4 Call Processing](#314-call-processing)
        - [3.1.4.1 Call Dialing](#3141-call-dialing)
        - [3.1.4.2 Call Routing/Park](#3142-call-routing-park)
        - [3.1.4.3 Call Forwarding](#3143-call-forwarding)
        - [3.1.4.4 Voicemail Setup](#3144-voicemail-setup)
        - [3.1.4.5 Call Queue](#3145-call-queue)
        - [3.1.4.6 Call Back](#3146-call-back)
        - [3.1.4.7 Calling Functionality](#3147-calling-functionality)
    - [3.1.5 Save/Edit Contacts](#315-save-edit-contacts)
    - [3.1.6 Allow to Customize Contact List](#316-allow-to-customize-contact-list)
    - [3.1.7 Call History](#317-call-history)
    - [3.1.8 Online Promotions and Rewards](#318-online-promotions-and-rewards)
    - [3.1.9 Plan Detail](#319-plan-detail)
    - [3.1.10 Plan Purchase](#3110-plan-purchase)
    - [3.1.11 Payment Options](#3111-payment-options)
    - [3.1.12 Email Confirmation](#3112-email-confirmation)
    - [3.1.13 Billing Information](#3113-billing-information)

- [3.2 Non-Functional Requirements](#32-non-functional-requirements)

    - [3.2.1 Performance](#321-performance)
    - [3.2.2 Reliability](#322-reliability)
        - [3.2.2.1 Error Handling and Recovery](#3221-error-handling-and-recovery)
        - [3.2.2.2 Data Backup](#3222-data-backup)
        - [3.2.2.3 Logging and Crash Reports](#3223-logging-and-crash-reports)
    - [3.2.3 Availability](#323-availability)
    - [3.2.4 Security](#324-security)
    - [3.2.5 Interfaces](#325-interfaces)

- [3.3 Design Constraints](#33-design-constraints)

- [3.4 Legal, Copyright, and Other Notices](#34-legal-copyright-and-other-notices)

- [3.5 Other Requirements](#35-other-requirements)

[4 Other Supporting Documents](#4-other-supporting-documents)

[A. Appendices](#a-appendices)


<div style="page-break-after: always;"></div>

# 1. Introduction

Development of the Online Virtual Phone System relies heavily on the Software Requirements Specification (SRS) document. It contains an introduction, a detailed project overview, specific requirements, and supporting data. A thorough project description containing the product concepts, functions, user profiles, and dependencies is given after the introduction, which establishes the context. The explicit requirements are described in the document's core, including interfaces, functionality, performance standards, and design limitations. It also offers appendices that assist the software and its qualities. Throughout the whole lifecycle of the software project, the SRS acts as a dynamic reference, allowing consistency and transparent communication.

## 1.1 Purpose

The primary purpose of this Software Requirements Specification (SRS) document is to provide a detailed overview of the Online Virtual Phone System. It will explain the purpose and features of the system, as well as the interfaces of the system, constraints, and assumptions. This document is intended for both the stakeholders and the developers of the system.

Through this document, the intent is to create an understanding of the system for the stakeholders and developers. The stakeholders will be able to understand the system's purpose and features, while the developers will be able to understand the system's requirements and constraints ultimately leading to delivering a phone system that meets the stakeholders' requirements.

## 1.2 Definitions, Acronyms, and Abbreviations

| **Term** | **Definition, Acronym or Abbreviations** |
| --- | --- |
| SRS | Software Requirement Specification |
| OS | Operating System |
| GUI | Graphical User Interface |
| MFA | Multi-Factor Authentication | 
| OVPS | Online Virtual Phone System |

## 1.3 References

- Project Charter
- Software Requirements Specification Template
- Software Requirements Specification Example
- IEEE Guide to Software Requirements Specification (ANSI/IEEE Std. 830-1984)


<div style="page-break-after: always;"></div>

# 2. General Description

## 2.1 User Characteristics

The users for the product will fall into one of two categories: administrator or user. 

The users will be adults, located at various locations across the globe with various levels of internet strength and reliability. Given the geographic diversity of the users, not everyone will speak the same language. The users will be using the product for both professional and personal use. As such the user may be an individual or a business, requiring extensions to reach multiple departments within the business. Users are expected to have varying levels of technical literacy. 

Administrators will be IT professionals with extensive knowledge and training and strong techinical literacy. These users will be located in Canada with a strong, reliable internet connection. 

## 2.2 Assumptions and Dependencies

It is assumed all users of the system will have the ability to connect to the internet with adequate speeds to allow for full functionality of the application. 

All users should have the necessary hardware and operating systems to support the app. We will accommodate operating systems from 2015-present day. Any operating systems that date back past 2015 will be incompatible. Hardware components such as a mobile device, desktop, speakers and microphones are assumed to be provided by the user.

Each user will have the ability to make a payment digitally via credit card or PayPal using CAD as the currency of choice. Should the user prefer an alternative currency it is assumed that the third party chosen to manage and route the transactions will be responsible for the conversion and any inform the user of any fees imposed by the users bank. 

While not all users will be fluent in English, it is assumed the users will be familar enough with one of the 4 languages provided to navigate the app without too much difficulty. 

The app will depend on the use of third party services to manage payment. As such, agreements must be made between the Online Virtual Phone System and the chosen third party.


<div style="page-break-after: always;"></div>

# 3. Specific Requirements

This will be the largest and most important section of the SRS. The customer requirements will be embodied within Section 2, but this section will give the D-requirements that are used to guide the project's software design, implementation, and testing.

## 3.1 Functional Requirements

### 3.1.1 Authentication
-	The system shall ask for username and password.
-	The system shall ask for multi-factor authentication(MFA).
-	The system shall support face/biometric authentication in mobile application.
-	The system shall check for humans by providing a puzzle or captcha.

### 3.1.2 User Account Management
- The system shall allow users/clients to easily create new accounts.
- The system shall provide a smooth onboarding process to guide users through the initial setup.
- The system shall allow users to update their personal information.
- The system shall allow users to set visibility level for their personal information.
- The system shall define different user roles.
- The system shall assign different levels of permission to each role to control what actions users can perform within the system.
- The system shall allow users to delete or deactivate their accounts if they wish to discontinue using the services.
- The system shall allow users to configure multi-factor authentication(MFA) to add an extra layer of security.

### 3.1.3 Search Functionality
- The system shall support searching for contact information by typing the recipient's name.
- The system shall support searching by partial or full keywords.
- The system shall support searching by digits.
- The system shall provide auto suggestions when searching by the recipient's name.
- The system shall sort the search results in ascending order.
- The system shall enable users to navigate between the search results.
- The system shall notify users when no matching results are found in the search.
- The system shall retain search history for 7 days.
- The system shall display only up to 15 matching results on the current screen.

### 3.1.4 Call Processing

#### 3.1.4.1 Call Dailing
- The system shall allow users to dial a number directly from their contact list.
- The system shall allow users to dial a number by typing it on the number keypad.
- The system shall allow users to copy and paste phone numbers into the dialing screen.

#### 3.1.4.2 Call Routing/Park
- The system shall perform call routing for incoming calls to business phone numbers.
- The system shall allow clients to configure their business phone numbers, including operation hours, department numbers, and pre-recorded scripts.

#### 3.1.4.3 Call Forwarding
- The system shall allow business phone users to set up call forwarding rules.
- The system shall support up to two additional devices, in addition to the primary device, for call forwarding.

#### 3.1.4.4 Voicemail Setup
- The system shall allow all users to set up their voicemail script.
- The system shall store voicemail for 30 days, they shall be automatically deleted.
- The system shall allow users to save/store voicemails with a total size of up to 1 GB.

#### 3.1.4.5 Call Queue
- The system shall allow users to place call back request if there are more than 10 calls ahead of them on the bussiness line.
- The system shall allow business phone number clients to configure the distribution of calls.

#### 3.1.4.6 Call Back
- The system shall allow business phone users to access call back information that was requested by their clients.

#### 3.1.4.7 Calling Functionality
- The system shall allow users to type extension or department where they would like to reach.
- The system shall allow users to dial the number directly from their contact list.

### 3.1.5 Save/Edit Contacts
- The system shall allow users to enter email addresses.
- The system shall allow users to enter company information.
- The system shall allow users to enter the company's URL/Website link.
- The system shall allow users to enter their business/home address.

### 3.1.6 Allow to Customize Contact List
- The system shall allow users to create a favorite contact list.
- The system shall allow users to save/mark/create an emergency contact list.
- The system shall allow users to tag contact and group them together.
- The system shall allow users to enter a phone number in the blacklist.
- The system shall allow users to enter a phone number in spam.

<div style="page-break-after: always;"></div>

### 3.1.7 Call History
- The system shall show the number of missed calls to users.
- The system shall maintain incoming and outgoing call history for up to 4 weeks.
- The system shall allow users to retrieve their call history based on date, name, and number.

### 3.1.8 Online Promotions and Rewards
- The system shall display all available promotions to the user.
- The system shall allow users to select from the available promotions.
- The system shall shows rates of promotions in different currencies.

### 3.1.9 Plan Detail
- The system shall provide detailed information on all the available plans.
- The system shall allow users to do comparision between different plans.

### 3.1.10 Plan Purchase
- The system shall allow users to confirm plan purchase.
- The system shall activate the purchased plan as soon as the payment goes through.

### 3.1.11 Payment Options 
- The system shall present all available options for payment.
- The system shall allow users to select the payment method for order.
- The system shall allow users to enter payment details.

### 3.1.12 Email Confirmation
- The system shall send purchase confirmation to the users through email. 

### 3.1.13 Billing Information
- The system shall display billing information on the application.
- The system shall send billing information to the users through email.
- The system shall send bill showing all charges incurred during a defined billing period.
- The system console shall display a user's bill for any billing period.
- The system shall shows sum of all charges for all calls incurred during the relevant billing period.
- The system shall shows all detail in bill including the duration of the call, the number dialed, the day of the week and the time of the day, the rate per minute for the call, and the charge for the call. 
- The system shall allow administrator to change amounts charged for call by adding or editing billing plans.
- The system shall issue bill immediately to a users in case of cancellation of services.
- The system shall generate warning in the bills in case of users have outstanding balance.

<div style="page-break-after: always;"></div>

## 3.2 Non-Functional Requirements

Non-functional requirements may exist for the following attributes. Often these requirements must be achieved at a system-wide level rather than at a unit level. State the requirements in the following sections in measurable terms (e.g., 95% of transactions shall be processed in less than a second, system downtime may not exceed 1 minute per day, > 30-day MTBF value, etc).

This section describes non-functional features of the software project. Specify the requirements as user story.

### 3.2.1 Performance

#### 3.2.1.1 Load management 
- The system shall handle all calls up a predefined maximum, determined by the administrators. 
- The system shall record and display the system load in real time to the administrators.

#### 3.2.1.2 System Speed
- The app startup time shall not exceed 3 seconds. 

#### 3.2.1.3 Audio Quality
- The system audio quality shall meet a minimum mean opinion score (MOS) of 4. 
- The system will provide voice calls with latency exceeding no more than 150ms.  

### 3.2.2 Reliability

#### 3.2.2.1 Error Handling and Recovery 
- The system shall implement robust algorithm for error handling and recovery to enhance user experience at least 99%.

#### 3.2.2.2 Data Backup
- The system shall perform regular back up of call data daily with 99.99% accuracy rate to minimize the data loss in case of system failure/system patch.

#### 3.2.2.3 Logging and Crash Reports 
- The system shall collect logging and crash reports to detect and respond to the system in efficient manner with goal of improving performance and reliability. 


### 3.2.3 Availability

- The system shall be available 24/7 with 99.99% uptime.
- The system shall be available on all major operating systems (Windows, MacOS, Linux, iOS, Android).
- The system shall be available in 4 languages (English, French, Spanish, Mandarin).
- The system shall be available in 3 methods of payments (Credit Card, PayPal, Use of third party applications if implemented).



### 3.2.4 Security

#### 3.2.4.1 Passwords and sensitive data
- The system will ensure a newly created password meets an adequate level of complexity.
- The system shall store end-to-end encrypted passwords.
- The system shall not store any payment information nor will the system store any personal information in the form of cookies, etc.

#### 3.2.4.2 Voice call security 
- The system shall screen for incoming scam calls (ie. AI generated calls). 
- Voice calls will be fully secure with end-to-end encryption. 

### 3.2.5 Interfaces

##

<div style="page-break-after: always;"></div>

## 3.3 Design Constraints

###

## 3.4 Legal, Copyright, and Other Notices

###

## 3.5 Other Requirements

Catchall section for any additional requirements.


<div style="page-break-after: always;"></div>

# 4 Other Supporting Documents

# A. Appendices

Sections of this document are based upon the IEEE Guide to Software Requirements Specification (ANSI/IEEE Std. 830-1984). The SRS templates of Dr. Lawrence Chung (UTD) have also been used as guides in developing this template.