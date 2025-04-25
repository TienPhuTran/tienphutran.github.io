---
title: "Project: Approval System - Web App"
excerpt: "<a href='https://github.com/NhatPham123tm/SoftwareDesign_Project' target='_blank'>GitHub Repository Link</a><br/>
            Create a system for form submission with a hierarchical approval workflow.<br/>
            <iframe width='400' height='225' src='https://www.youtube.com/embed/F-2NI3qfZ-k' frameborder='0' allowfullscreen></iframe>"
collection: portfolio
---

<iframe width="500" height="300" src="https://www.youtube.com/embed/F-2NI3qfZ-k" frameborder="0" allowfullscreen></iframe>



<br>
**[GitHub Repository Link](https://github.com/NhatPham123tm/SoftwareDesign_Project)**

![Approval System](/images/approval_system.png)

 * Working as a team to build a submission approval system.
 * Submission System: Using HTML/CSS to build a website for users to submit the forms. Using Django to build a backend for data submission. Form data will be stored in PostgreSQL and retrieved for further actions, such as modification. When a User or Employee require the PDF of the submission form, APIs will be called to retrieve the database and add them to LaTeX. A subprocess will be called to convert LaTeX to PDF. 
 * Approval System: Using Django to build workflow rules to assign form reviews to sub-units based on the
customized hierarchy. For example, in the pending forms, the trigger will be called to add assigned forms to the target user. By default, forms will be sent to the head of different departments based on their types. The head of the department can do review jobs, and they can also be delegated to another manager in other departments or the same department's employees. Using HTML/CSS to build a 
dynamic website for employee features. 
 * Collaborating with another team to integrate and expand the service using Django and React.
 * Tools Used: Django, React, LaTeX, PostgreSQL, HTML/CSS