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
