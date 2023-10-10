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



## TABLE OF CONTENTS

[Revision History](#Revision-History)

[1. Introduction](#1.-Introduction)

- [1.1 Purpose](#1.1-Purpose)

- [1.2 Definitions, Acronyms, and Abbreviations](#1.2-Definitions-Acronyms-and-Abbreviations)

- [1.3 References](#1.3-References)

[2. General Description](#2.-General-Description)

- [2.1 User Characteristics](#2.1-User-Characteristics)

- [2.2 Assumptions and Dependencies](#2.2-Assumptions-and-Dependencies)

[3. Specific Requirements](#3.-Specific-Requirements)

- [3.1 Functional Requirements](#3.1-Functional-Requirements)

- [3.2 Non-Functional Requirements](#3.2-Non-Functional-Requirements)

    - [3.2.1 Performance](#3.2.1-Performance)

    - [3.2.2 Reliability](#3.2.2-Reliability)

    - [3.2.3 Availability](#3.2.3-Availability)

    - [3.2.4 Security](#3.2.4-Security)

    - [3.2.5 Interfaces](#3.2.5-Interfaces)

- [3.3 Design Constraints](#3.3-Design-Constraints)

- [3.4 Legal, Copyright, and Other Notices](#3.4-Legal-Copyright-and-Other-Notices)

- [3.5 Other Requirements](#3.5-Other-Requirements)

[4 Other Supporting Documents](#4-Other-Supporting-Documents)

[A. Appendices](#A-Appendices)

<div class="page-break"></div>

## Revision History

| **Date** | **Description** | **Author** | **Comments** |
| --- | --- | --- | --- |
| 2023-10-10 | Version 1 | Dharmit Anghan | Introduction |

<div class="page-break"></div>

## 1. Introduction

Development of the Online Virtual Phone System relies heavily on the Software Requirements Specification (SRS) document. It contains an introduction, a detailed project overview, specific requirements, and supporting data. A thorough project description containing the product concepts, functions, user profiles, and dependencies is given after the introduction, which establishes the context. The explicit requirements are described in the document's core, including interfaces, functionality, performance standards, and design limitations. It also offers appendices that assist the software and its qualities. Throughout the whole lifecycle of the software project, the SRS acts as a dynamic reference, allowing consistency and transparent communication.

### 1.1 Purpose

The primary purpose of this Software Requirements Specification (SRS) document is to provide a detailed overview of the Online Virtual Phone System. It will explain the purpose and features of the system, as well as the interfaces of the system, constraints, and assumptions. This document is intended for both the stakeholders and the developers of the system.

Through this document, the intent is to create an understanding of the system for the stakeholders and developers. The stakeholders will be able to understand the system's purpose and features, while the developers will be able to understand the system's requirements and constraints ultimately leading to delivering a phone system that meets the stakeholders' requirements.

### 1.2 Definitions, Acronyms, and Abbreviations

| **Term** | **Definition, Acronym or Abbreviations** |
| --- | --- |
| SRS | Software Requirement Specification |
| <Term> | <Definition> |
| <Term> | <Definition> |


### 1.3 References

- Project Charter
- Software Requirements Specification Template
- Software Requirements Specification Example

<div class="page-break"></div>

## 2. General Description

_This section of the SRS should describe the general factors that affect 'the product and its requirements. It should be made clear that this section does not state specific requirements; it only makes those requirements easier to understand._

### 2.1 User Characteristics

This subsection of the SRS should describe those general characteristics of the eventual users of the product that will affect the specific requirements. (See the IEEE Guide to SRS for more details).

### 2.2 Assumptions and Dependencies

This subsection of the SRS should list each of the factors that affect the requirements stated in the SRS. These factors are not design constraints on the software but are, rather, any changes to them that can affect the requirements in the SRS. For example, an assumption might be that a specific operating system will be available on the hardware designated for the software product. If, in fact, the operating system is not available, the SRS would then have to change accordingly.

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

< The product shall take initial load time depending on internet connection strength, which also depends on the media from which the product is run. >

#### 3.2.2 Reliability

< The system shall provide RAID V Disk Stripping on all database storage disks. >

#### 3.2.3 Availability

< The system shall provide a contractual agreement with an internet service provider for T3 access with 99.9999% availability. >

#### 3.2.4 Security

< The system shall use secure sockets in all transactions that include any confidential customer information.

The system shall automatically log out all customers after a period of inactivity. >

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
