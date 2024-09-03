# CMPG324-Project4-35407972

## Testing & RPA

![rpa](https://github.com/user-attachments/assets/9b84c615-ae49-47d6-b4ea-2e8f86858a55)


### What is RPA & Automation?
Robotic Process Automation (RPA) is a technology that utilizes software robots to mimic human actions, automating tasks that involve user interfaces. It helps streamline repetitive and time-consuming processes, allowing human workers to focus on strategic and creative tasks. RPA enhances operational efficiency by automating rule-based tasks, leading to cost savings, increased accuracy, faster task completion, and easy scalability. It revolutionizes business operations by improving productivity and enabling employees to engage in more valuable activities, thereby optimizing overall performance.

### Why do we need Automation in our lives?
SAVE TIME, MONEY, AND MUCH MORE...

### How to use the Automation
This automation reads and manipulates data from the Excel spreadsheet "NWUTechTrendsData" and interacts with the web app called: https://techtrendstelemetryportal.azurewebsites.net/.

### MORE ABOUT RPA AND TESTING
#### Instruction Manual:
To use the available web app: [NWU Tech Trends Telemetry Portal.](https://techtrendstelemetryportal.azurewebsites.net/)

Use the Firefox browser and UiPath Studio Community Edition.

Log in to the web app using the credentials configured in the automation.

The web app contains multiple tabs: HOME, CUSTOMERS, ORDERS, PRODUCTS, and ORDER DETAILS.

Note: Ensure the prerequisites are met before running the automation.

## Read and Create Data from the Excel Spreadsheet

The automation logs into the web app NWU Tech Trends Telemetry Portal using pre-saved credentials.

It navigates through the tabs: Customers, Orders, Products, and Order Details.

For each tab, the automation clicks "Create New" and inputs data from the Excel spreadsheet into the corresponding web fields.

The automation inserts records based on click actions for each tab and updates the data on the web app.

All entered data is displayed in tables under each respective tab: Customers, Orders, Products, and Order Details.

Simultaneously, it updates the Test Result column in the Excel spreadsheet, indicating the success (TRUE) or failure (FALSE) of each operation.

## Edit Data on the Web App and Modify Data

The automation allows editing of records under each tab: Customers, Orders, Products, and Order Details, adding or modifying data as needed.

It captures and loops through data on the web app, making edits, such as updating a customer's title.

All changes are recorded and updated in the Excel spreadsheet, reflecting whether edits were successful.

Delete Data on the Web App

The automation also supports deleting records from any of the tabs: Customers, Orders, Products, and Order Details.

Each tab displays tables of data with a "Delete" option.

Upon clicking "Delete," the automation removes the entire record and updates the Excel spreadsheet to reflect the deletion status.

### LINK TO PROJECT 4 REFERENCE LIST:

