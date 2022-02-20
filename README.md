## 2022 - TIC4302 Assignment 2

The repository for the second assignment.

Release date: February 18th 2022 18.00 PM

Deadline date: February 24th 2022 23.59 PM

Score: 40% Theory and 60 % App

### Please find guideline for the theory part

Answer the question by give this [ and ] in your answer option. Example for the answer B:

A one  
[B] two  
C three  

### Please find the guideline for the app part

The code repository is updated with vulnerable components and vulnerabilities. 
Embed DevSecOps process like SCA, SAST and Secret Scanning in the pipeline to improve the security posture of the application.

Guidelines:
* Exclude the app directory in secret scanning since the database.sql may trigger some secrets
* Try using pyraider/safety to check for vulnerable software components/packages in the project
* Perform a static code analysis using bandit
* Fix the medium issues raised by Bandit
* Make sure logs for safety and bandit on the CI\CD pipeline are generated
* Submit the logs with doing this: 
  - Download the artifact from Github Actions page
  - Unzip or extract the logs file artifact
  - Upload or commit the logs file into Github repository in the `logs` directory with this name `safety.log` and `bandit.log` 

PS: You may check the Zoom recording from 4th and 5th classes for detailed guidance.
