# VRTechnologies

A prototype information system for data sourcing and data quality assurance

## Description

_VRTechnologies_ is a prototype information system for data sourcing and quality assurance at a fictional start-up company in the home sharing industry. It was developed using MS Access and VBA.

The features of the system are based on business requirements as captured in the following user stories:

1. "As a data analyst, I want to see on a graphic user interface the data scraped from home sharing platforms like Airbnb of a property whose street address has not been identified by other data analysts so that I can find and enter its location."
2. "As a QA analyst, I want to see on a graphic user interface the STR property addresses that have been submitted by data analysts so that I can inspect their accuracy, correct any mistakes and pass/fail their overall quality."
3. "As an implementation project manager, I want to see on a dashboard the data sourcing progress for my customers so that I can efficiently schedule the implementation timelines of my portfolio."
4. "As an implementation project manager, I want toe able to alert the operations manager via a notification system so that I can escalate any critical implementation issues that I observe from the data analyst and QA teams."
5. "As an operations manager, I want to see KPI of individual data and QA analysts on a dashboard so that I can track their performance."
6. "As an operations manager, I want to manage systems access so that users can open only the dashboards they need to perform their job."

All user stories were implemented except for #4 and #6, which is partially implemented without live data.

![Screenshot](/images/vrt01.jpg)

More screenshots below.

## Disclaimer

ALL CONTENTS IN THIS REPO ARE FOR EDUCATIONAL PURPOSES ONLY.

## Getting Started

### Dependencies

* None

### Usage

1. Clone it!

    ```bash
    git clone https://github.com/ggeerraarrdd/vacation.git
    ```

2. Go into the project directory and open `vrtechnologies.accdb` on MS Access.

3. Click the `Enable Content` button if you get the following message:

    ```text
    SECURITY WARNING Some active content has been disabled. Click for more details.
    ```

4. In the Navigation Pane and under Forms, double click `frm_1_login`.

5. Go to Home > Views to make sure you are in "Form View". Otherwise change to that view.

### Logging In

The system as prototyped supports four business users: Operations Manager, Data Analyst, QA Analyst and Implementation Project Manager.

For their user stories, click on any of the tabs numbered 1-6. There are yellow buttons labeled with the business user whose system requirements are captured by the user story in one of tabs. Click the button to populate the form fields with their login credentials.

You can also click any of the yellow buttons below the login form.

### Note

Some of the forms require certain user info to function properly. So you might encounter an error if you open them without first going through the login process, which normally you would not be able to do with a real-world system. Closing all open forms and going back to the login page should resolve most errors.

## Author(s)

* [@ggeerraarrdd](https://github.com/ggeerraarrdd/)

## Version History

### Release Notes

* See [https://github.com/ggeerraarrdd/vacation/releases](https://github.com/ggeerraarrdd/vacation/releases)

### Initial Release

The [initial realease](https://github.com/ggeerraarrdd/vacation/releases/tag/v1.0.0) of _VRTechnologies_ was submitted as the final project for [IS 421: Systems Analysis and Design](https://www.cdm.depaul.edu/academics/pages/courseinfo.aspx?Subject=IS&CatalogNbr=421) (DePaul University, 2023).

### Future Work

No ongoing development.

## License

* [MIT License](https://github.com/ggeerraarrdd/large-parks/blob/main/LICENSE)

## Acknowledgments

* Too many StackOverflow [Q&As](https://meta.stackoverflow.com/questions/267822/if-stack-overflow-doesnt-have-threads-what-the-heck-should-they-be-called), Medium articles and online tech how-to boutiques to mention but Charlie Nuttelman's 3-course series [Excel/VBA for Creative Problem Solving Specialization](https://www.coursera.org/specializations/excel-vba-creative-problem-solving) on Coursera helped me cracked VBA.
  
## Screenshots

![Screenshot](/images/vrt02.jpg)
*After login, the dashboard for an operations manager.*

![Screenshot](/images/vrt03.jpg)
*The GUI for data sourcing by a data analyst.*

![Screenshot](/images/vrt04.jpg)
*The GUI for data quality assurance by a QA analyst.*

![Screenshot](/images/vrt05.jpg)
*The dashboard for KPI of data and QA analysts for use by an operations manager.*
  
![Screenshot](/images/vrt06.jpg)
*The customer dashboard for use by an implementation project manager.*
