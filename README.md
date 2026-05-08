# 📱 Urban Lunch | Mobile QA Testing Project

## 🎯 Project Goals


This project showcases my QA process applied to a mobile application environment, focusing on functional validation, exploratory testing, usability analysis, UI consistency, and bug reporting.

The application tested was **Urban Lunch**, an Android app that allows users to order food from different restaurants and collect their orders at pickup locations across the city.

During the testing process, I validated the main user flows, compared the application against business requirements and Figma layouts, and identified defects capable of impacting usability, interaction quality, and overall user experience.

## 🧪 Testing Scope

The testing process covered:

Functional Testing:
Validation of all major application flows according to requirements.
UI/UX Validation:
Comparison between implemented screens and Figma layouts.

Exploratory Testing:
Additional exploratory analysis to identify unexpected behaviors outside predefined scenarios.

Localization Testing:
Validation of text consistency and language correctness.

Regression Mindset:
Verification that fixes and interactions between features did not introduce additional issues.

### 🛠️ Tools & Technologies Used:

* Android Emulator (Pixel 5)
* Jira (Bug Reporting)
* Google Sheets
* Figma
* Android APK
* VS Code

## 📋 Test Documentation


My methodology involves test scenarios, expected results, execution status, pass/fail validations, and bug tracking links in Jira. U can see more about the complete checklist used during testing rigth here: 

👉 [https://docs.google.com/spreadsheets/d/1u6UzTsbyEf4-CdjX9T1ZTCsnZIzTeD_YjCSpsrT8doE/edit?gid=287334773#gid=287334773](https://docs.google.com/spreadsheets/d/1u6UzTsbyEf4-CdjX9T1ZTCsnZIzTeD_YjCSpsrT8doE/edit?gid=287334773#gid=287334773)


Requirements:
[https://practicum-content.s3.us-west-1.amazonaws.com/new-markets/qa-sprint-5/PT-BR/V8/PRT_v8_refactored.pdf](https://practicum-content.s3.us-west-1.amazonaws.com/new-markets/qa-sprint-5/PT-BR/V8/PRT_v8_refactored.pdf)

Figma Layouts:
[https://www.figma.com/design/ho8vAomcV9lxesAH1ofqvh/Urban.Lunch-PT?node-id=0-1&node-type=canvas&t=5OE7d0poF6oRMWMx-0](https://www.figma.com/design/ho8vAomcV9lxesAH1ofqvh/Urban.Lunch-PT?node-id=0-1&node-type=canvas&t=5OE7d0poF6oRMWMx-0)


## 🐞 Bugs Found and Business Impact

During execution, I identify multiple defects across different areas of the application. And some defects had direct impact on usability and user confidence. I would like to highlight some of the most critical issues capable of causing real business impact:
### 1- Localization Defect

A confirmation button was displayed in Spanish instead of Portuguese:

> "Recibi el pedido"

Although considered a minor issue functionally, localization defects reduce product credibility and negatively affect user experience.


### 2- Feedback Flow Defect

The feedback submission interaction required two clicks instead of one.

Potential business impact:

* Reduced user engagement
* Frustration during interaction
* Increased abandonment probability
* Poor UX perception



### 3- UI and Requirement Deviations

Some feedback messages and interface elements did not fully match the expected requirements or Figma design.

Potential impact:

* Inconsistent user experience
* Reduced accessibility and usability
* Misalignment between product and design teams

> Remember that you can access all bug reports in the project [CHECKLIST!](https://docs.google.com/spreadsheets/d/1u6UzTsbyEf4-CdjX9T1ZTCsnZIzTeD_YjCSpsrT8doE/edit?gid=287334773#gid=287334773)




## 🧠 Conclusion
This project was executed with a product-oriented QA mindset, focusing not only on technical validation but also on how the application experience could impact real users and the business itself. 

During testing, I analyzed interface consistency, interaction fluidity, localization quality, and overall UX behavior to identify issues that could affect user trust, usability, and product credibility beyond purely functional defects.

Overall, the goal was to go beyond basic validation and ensure that the application delivers a reliable, consistent, and user-centered experience, aligning both with functional requirements and real user expectations.
