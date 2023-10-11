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
| 2023-10-10 | Version 1.1 | Added function requirement and Reliability | Rutu Barvaliya |

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

(_You may need to refine your scope/purpose defined in the project charter after eliciting requirements with stakeholders_)

The introduction to the Software Requirement Specification (SRS) document should provide an overview of the complete SRS document. While writing this document, please remember that this document should contain all of the information needed by a software engineer to adequately design and implement the software product described by the requirements listed in this document. (Note: the following subsection annotates are largely taken from the IEEE Guide to SRS).

## 1.1 Purpose

_What is the purpose of this SRS and the (intended) audience for which it is written._

## 1.2 Definitions, Acronyms, and Abbreviations

_This subsection should provide the definitions of all terms, acronyms, and abbreviations required to properly interpret the SRS. This information may be provided by reference to one or more appendices in the SRS or by reference to other documents._

## 1.3 References

_This subsection should:_

_(1) Provide a complete list of all documents referenced elsewhere in the SRS, or in a separate, specified document._

_(2) Identify each document by title, report number - if applicable - date, and publishing organization._

_(3) Specify the sources from which the references can be obtained._

_This information may be provided by reference to an appendix or to another document._

<div class="page-break"></div>

# 2. General Description

_This section of the SRS should describe the general factors that affect 'the product and its requirements. It should be made clear that this section does not state specific requirements; it only makes those requirements easier to understand._

## 2.1 User Characteristics

This subsection of the SRS should describe those general characteristics of the eventual users of the product that will affect the specific requirements. (See the IEEE Guide to SRS for more details).

## 2.2 Assumptions and Dependencies

This subsection of the SRS should list each of the factors that affect the requirements stated in the SRS. These factors are not design constraints on the software but are, rather, any changes to them that can affect the requirements in the SRS. For example, an assumption might be that a specific operating system will be available on the hardware designated for the software product. If, in fact, the operating system is not available, the SRS would then have to change accordingly.

<div class="page-break"></div>

# 3. Specific Requirements

This will be the largest and most important section of the SRS. The customer requirements will be embodied within Section 2, but this section will give the D-requirements that are used to guide the project's software design, implementation, and testing.

## 3.1 Functional Requirements

### 3.1.1 Authentication
-	The system shall ask for username and password.
-	The system shall ask for multi-factor authentication.
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
- The system shall allow users to configure Two-Factor Authentication to add an extra layer of security.

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

### 3.1.7 Call History
- The system shall show the number of missed calls to users.
- The system shall maintain incoming and outgoing call history for up to 4 weeks.
- The system shall allow users to retrieve their call history based on date, name, and number.

### 3.1.8 Online Promotions and Rewards
The system shall display all available promotions to the user.
The system shall allow users to select from the available promotions.
The system shall shows rates of promotions in different currencies.

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
-	The system shall send purchase confirmation to the users through email. 

### 3.1.13 Billing Information
-	The system shall display billing information on the application.
-	The system shall send billing information to the users through email.


## 3.2 Non-Functional Requirements

Non-functional requirements may exist for the following attributes. Often these requirements must be achieved at a system-wide level rather than at a unit level. State the requirements in the following sections in measurable terms (e.g., 95% of transactions shall be processed in less than a second, system downtime may not exceed 1 minute per day, > 30-day MTBF value, etc).

This section describes non-functional features of the software project. Specify the requirements as user story.

### 3.2.1 Performance

< The product shall take initial load time depending on internet connection strength, which also depends on the media from which the product is run. >

### 3.2.2 Reliability

#### 3.2.2.1 Error Handling and Recovery 
- The system shall implement robust algorithm for error handling and recovery to enhance user experience at least 99%.

#### 3.2.2.2 Data Backup
- The system shall perform regular back up of call data daily with 99.99% accuracy rate to minimize the data loss in case of system failure/system patch.

#### 3.2.2.3 Logging and Crash Reports 
- The system shall collect logging and crash reports to detect and respond to the system in efficient manner with goal of improving performance and reliability. 


### 3.2.3 Availability

< The system shall provide a contractual agreement with an internet service provider for T3 access with 99.9999% availability. >

### 3.2.4 Security

< The system shall use secure sockets in all transactions that include any confidential customer information.

The system shall automatically log out all customers after a period of inactivity. >

### 3.2.5 Interfaces

##

## 3.3 Design Constraints

###

## 3.4 Legal, Copyright, and Other Notices

###

## 3.5 Other Requirements

Catchall section for any additional requirements.

# 4 Other Supporting Documents

# A. Appendices

Sections of this document are based upon the IEEE Guide to Software Requirements Specification (ANSI/IEEE Std. 830-1984). The SRS templates of Dr. Lawrence Chung (UTD) have also been used as guides in developing this template.