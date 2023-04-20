# RPA-Project-Bank-Loan-Processing-using-RE-framework
RPA Project Bank Loan Processing using RE framework 

<img src="https://user-images.githubusercontent.com/122998236/229281282-754636b3-c48d-4233-a0c2-657a69e45d5a.jpg" width="800" height="300" />

## Project:		Loan Application processing
## Vertical:		Banking and Finance
## Department:	Loan


Processes such as loan management require a great deal of paperwork, data checks, and dependencies. Today’s customer expects quick, easy access to loan services at the time, place, and channel of their choosing. They seek loan products tailored to their specific needs that are available through their preferred channel and have quick approvals.<br>

Robotic process automation (RPA) has been assisting lenders in gaining a competitive advantage during the loan origination process. RPA’s use in loan management has allowed banks to automate processes.<br>

Simply put, robotic process automation is the technology that replaces human action for repetitive and redundant tasks by extracting and processing structured data. Robots mimic human tasks based on a set of instructions. They can process error-free applications much faster. The ‘bots’ can read an email or invoice, download files to a specific location, copy-paste, scan through data and file it. It is designed specifically for process-oriented industries.<br>

Implementing RPA in loan processing can speed up processes, increase reliability, and reduce labour-intensive tasks by shifting the burden to robots and freeing the workforce to perform more complex tasks. RPA in loan processing can strengthen existing banking mechanisms while also assisting the industry in scaling its growth.

### Steps:
  •	Define the problem statement<br>
  •	PDD<br>
  •	SDD<br>
  •	End to end Automation<br>

<img src="https://user-images.githubusercontent.com/122998236/229280832-fa1c5f4c-e8cd-4b42-bade-8017d9010ee9.jpeg" width="400" height="200" />

## Manual task in banks for Loan application processing:

* In a bank there are many people who apply for a loan. Daily or weekly basis bank receives an Email having data of the customers who want to apply for a loan.

* There is the person in the loan department who is actually going through the mail every day and validates the attachment the mail has valid or not valid .is the data inside the application is proper not proper.
* Is it following the bank standards ?is it following the loan requirement? What is the loan amount they are expecting? And all the details he validates one by one.
* For all the valid records of excel, whichever he finds appropriate, he passes it to a different department where they actually feed all the valid data into the system and they grant the loan. Or they generate a loan id.

## Loan application processing using RPA:

* Robot first opens an email, downloads an attachment which includes data of all customers who apply for a loan through a bank portal. This customer data is available as .xlsx file.
* Customer data then processed by the automation robot to check for data validation. As per eligibility what bank offers, it filters out the loan applicant’s data.
* Those who are eligible for loan, robot fills data in loan application processing form on bank website for them.
* If data is valid, bank generates loan id. Robot writes this number in excel for each applicant. And also updates status of application for other rejected loan applicants in excel.

## Technical Skills
The following technical skills are required to understand and modify this project:

*  UiPath Studio: UiPath Studio is the primary tool used to develop and modify the project. A basic understanding of UiPath Studio is necessary to modify the project code.
*  RE Framework: The project is built on top of UiPath's RE Framework, which is designed to promote reusability, modularity, and maintainability of the code. A good understanding of the RE Framework is necessary to modify and extend the project code.
*  Microsoft Excel: The loan application data is stored in an Excel spreadsheet. A basic understanding of Excel is necessary to modify the loan application data.
*  Email: The project sends email notifications to the applicants regarding the status of their loan application. A basic understanding of email systems is necessary to configure and use this feature.

## Deployment
  To deploy this project in a production environment, follow these steps:

 * Modify the Config.xlsx file to include the production environment settings, such as email server details, credentials, etc.
 * Package the project using UiPath Studio's Package Manager.
 * Deploy the package to the production environment using UiPath Orchestrator or any other deployment tool.
 * Schedule the automation process to run at regular intervals using UiPath Orchestrator or any other scheduling tool.
 * Monitor the automation process using UiPath Orchestrator or any other monitoring tool.

## Conclusion
This project demonstrates how UiPath's RE Framework can be used to automate complex business processes such as loan application processing for a bank. The project can be easily extended to include additional features such as generating reports, integrating with external systems, and more. With proper deployment and monitoring, this project can significantly reduce the time and cost involved in loan application processing for a bank.
