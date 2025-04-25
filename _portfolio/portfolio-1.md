---
title: "Project: Approval System - Web App"
excerpt: "Create a system for form submission with a hierarchical approval workflow.<br/><iframe width='400' height='225' src='https://www.youtube.com/embed/F-2NI3qfZ-k' frameborder='0' allowfullscreen></iframe>"
collection: portfolio
---

<iframe width="500" height="300" src="https://www.youtube.com/embed/F-2NI3qfZ-k" frameborder="0" allowfullscreen></iframe>



<br>
**[GitHub Repository Link](https://github.com/NhatPham123tm/SoftwareDesign_Project)**

![Approval System](/images/approval_system.png)

 * Working as a team to build a submission approval system.
 * Submission System: UsingHTML/CSS to build a website for user to submmit the forms. Using Django to build backend for data submission. Form data will be stored in PostgreSQL and retrieved for further actions such as modifying. When User or Employee require the PDF of submission form APIs will be called to retrive the database and add them to Latex. A subproccess will be called to convert LaTeX to PDF.
 * Approval System: Using Django to build workflow rules to assign form reviews to sub-units based on the
customized hierarchy. For example, the pending forms, the trigger will be called to add assign forms to target user. In default, forms will be send to the head of different departments based on their types. The head of department can do review jobs, and they can also be delegate to another managers in other departments or same department employess. Using HTML/CSS to build a
dynamic website for employee feature.
 * Collaborating with another team to integrate and expand the service using Django and React.
 * Tools Used: Django, React, Latex, PostgreSQL, HTML/CSS
