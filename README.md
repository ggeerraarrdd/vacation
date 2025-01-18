# VRTechnologies

A prototype information system for data sourcing, data quality assurance and business intelligence

## Description

> [!NOTE]
> ALL CONTENTS IN THIS REPO ARE FOR EDUCATIONAL PURPOSES ONLY.

_VRTechnologies_ is a prototype information system for data sourcing and quality assurance at a fictional start-up company in the home sharing industry. It was developed using MS Access and VBA.

The features of the system are based on business requirements as captured in the following user stories:

1. "As a data analyst, I want to see on a graphic user interface the data scraped from home sharing platforms like Airbnb of a property whose street address has not been identified by other data analysts so that I can find and enter its location."
2. "As a QA analyst, I want to see on a graphic user interface the STR property addresses that have been submitted by data analysts so that I can inspect their accuracy, correct any mistakes and pass/fail their overall quality."
3. "As an implementation project manager, I want to see on a dashboard the data sourcing progress for my customers so that I can efficiently schedule the implementation timelines of my portfolio."
4. "As an implementation project manager, I want toe able to alert the operations manager via a notification system so that I can escalate any critical implementation issues that I observe from the data analyst and QA teams."
5. "As an operations manager, I want to see KPI of individual data and QA analysts on a dashboard so that I can track their performance."
6. "As an operations manager, I want to manage systems access so that users can open only the dashboards they need to perform their job."

All user stories were implemented except for #4 and #6, which is partially implemented without live data.

![Screenshot](/docs/vrt01.jpg)

More screenshots below.

## Table of Contents

* [Description](#description)
* [Features](#features)
* [Project Structure](#project-structure)
* [Prerequisites](#prerequisites)
* [Getting Started](#getting-started)
  * [Dependencies](#dependencies)
  * [Installation](#installation)
  * [Configuration](#configuration)
  * [Usage](#usage)
* [Author(s)](#authors)
* [Version History](#version-history)
  * [Release Notes](#release-notes)
  * [Initial Release](#initial-release)
* [Future Work](#future-work)
* [License](#license)
* [Contributing](#contributing)
* [Acknowledgments](#acknowledgments)
* [Screenshots](#screenshots)

## Features

* Data Entry System - Allows business users to input and save property location details
* QA Review Dashboard - Interface for QA analysts to review submitted property addresses
* Quality Validation Framework - Tools for correcting errors while ensuring data integrity
* Implementation Progress Dashboard - Visual tracking of data sourcing progress by customer
* Performance Analytics Dashboard - Displays KPIs for business users
* Customer Portfolio Management - Tools for tracking implementation timelines and progress
* Batch Processing Capability - Ability to handle multiple property entries efficiently

## Project Structure

* NA

## Prerequisites

Before you begin, ensure you have met the following requirements:

* [Microsoft Access 2021](https://www.microsoft.com/en-us/microsoft-365/access) (other versions untested)
* Windows 11 (other versions untested)

## Getting Started

### Dependencies

* None

### Installation

1. **Download the file**

    You do not need to clone the repo. Simply download `vrtechnologies.accdb`.

### Configuration

* None

### Usage

1. **Open `vrtechnologies.accdb` on MS Access**

    Click the `Enable Content` button if you get the following message:

    ```text
    SECURITY WARNING Some active content has been disabled. Click for more details.
    ```

2. **Pre-login process**

    * In the Navigation Pane and under Forms, double click `frm_1_login`.

    * Go to `Home > Views` to make sure you are in "Form View". Otherwise change to that view.

3. **Log in**

    * The system as prototyped presumes four business users: Operations Manager, Data Analyst, QA Analyst and Implementation Project Manager.

    * For their user stories, click on any of the tabs numbered 1-6. There are yellow buttons labeled with the business user whose system requirements are captured by the user story in one of tabs. Click the button to populate the form fields with their login credentials.

    * You can also click any of the yellow buttons below the login form.

    * **Note:** Some of the forms require certain user info to function properly. So you might encounter an error if you open them without first going through the login process, which normally you would not be able to do with a real-world system. Closing all open forms and going back to the login page should resolve most errors.

## Author(s)

* [@ggeerraarrdd](https://github.com/ggeerraarrdd/)

## Version History

### Release Notes

* See [https://github.com/ggeerraarrdd/vacation/releases](https://github.com/ggeerraarrdd/vacation/releases)

### Initial Release

The [initial realease](https://github.com/ggeerraarrdd/vacation/releases/tag/v1.0.0) of _VRTechnologies_ was submitted as a final project for [IS 421: Systems Analysis and Design](https://www.cdm.depaul.edu/academics/pages/courseinfo.aspx?Subject=IS&CatalogNbr=421) (DePaul University, 2023).

## Future Work

No ongoing development.

## License

* [MIT License](https://github.com/ggeerraarrdd/large-parks/blob/main/LICENSE)

## Contributing

This project is not accepting contributions at this time. It is intended solely for personal learning and exploration. However, feel free to clone the repository and use it as a learning resource.

## Acknowledgments

* The sprawling, seemingly inexhaustible ecosystem of StackOverflow [Q&As](https://meta.stackoverflow.com/questions/267822/if-stack-overflow-doesnt-have-threads-what-the-heck-should-they-be-called), Medium articles and online tech how-to boutiques—too many to mention here separately
* Charlie Nuttelman's 3-course series [Excel/VBA for Creative Problem Solving Specialization](https://www.coursera.org/specializations/excel-vba-creative-problem-solving) on Coursera helped me cracked VBA.
  
## Screenshots

![Screenshot](/docs/vrt02.jpg)
_After login, the dashboard for an operations manager._

![Screenshot](/docs/vrt03.jpg)
_The GUI for data sourcing by a data analyst._

![Screenshot](/docs/vrt04.jpg)
_The GUI for data quality assurance by a QA analyst._

![Screenshot](/docs/vrt05.jpg)
_The dashboard for KPI of data and QA analysts for use by an operations manager._
  
![Screenshot](/docs/vrt06.jpg)
_The customer dashboard for use by an implementation project manager._

## Frontispiece

Screenshot of Login page of _VRTechnologies_. Image taken from the database application interface (Personal Collection, 2023). In the public domain.
