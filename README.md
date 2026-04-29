# 7.CI-CD-Pipeline-to-Deploy-Node.js-Application

#  CI/CD Pipeline to Deploy Node.js Application (Without CodeBuild)

##  Project Overview
This project demonstrates a **CI/CD pipeline for deploying a Node.js application automatically** using AWS services and GitHub.

Instead of manual deployment, the application is deployed on EC2 whenever code is pushed to GitHub.

---

##  Objective
To:
- Automate application deployment  
- Reduce manual effort  
- Enable continuous integration and delivery  

---

##  AWS Services Used

- AWS CodePipeline – Automates deployment workflow  
- AWS CodeDeploy – Deploys app to EC2  
- :contentReference[oaicite:2]{index=2} – Hosts Node.js application  
- :contentReference[oaicite:3]{index=3} – Source code repository  

---

##  Architecture Flow

GitHub → CodePipeline → CodeDeploy → EC2 → Application Live

---

##  Features

- ✅ Auto deployment on `git push`  
- ✅ No CodeBuild (cost optimized)  
- ✅ Direct deployment to EC2  
- ✅ Fast and simple CI/CD pipeline  

---

1. VS Code Project Setup

•  App7.js

   <img width="1110" height="397" alt="Screenshot 2026-04-29 165944" src="https://github.com/user-attachments/assets/7c9bfc05-8710-44d8-bed7-17c3b2e056dd" />

•  package.json 

<img width="978" height="668" alt="Screenshot 2026-04-29 170142" src="https://github.com/user-attachments/assets/06224dce-1c9a-4466-a154-b1a1a842657e" />

•  http://localhost:4000

<img width="910" height="190" alt="Screenshot 2026-04-29 170258" src="https://github.com/user-attachments/assets/fe321ea8-995a-4094-9653-af89d213f517" />

2. Git Commands in Terminal
•  git commit 
•  git push

<img width="1328" height="542" alt="Screenshot 2026-04-29 170437" src="https://github.com/user-attachments/assets/d3c5da35-2672-48b8-850a-b880abd34720" />

3.EC2 terminal showing:
•	node -v 
•	npm -v

<img width="1234" height="668" alt="Screenshot 2026-04-29 170543" src="https://github.com/user-attachments/assets/30f2b0b2-6901-4f26-98ec-500baaee021e" />

4.CodeDeploy running:

<img width="1329" height="284" alt="Screenshot 2026-04-29 170745" src="https://github.com/user-attachments/assets/cdddb17e-7a9a-43da-86dc-d04d282b6af8" />

5. Application Deployment Output on AWS EC2

   <img width="1238" height="444" alt="Screenshot 2026-04-29 170909" src="https://github.com/user-attachments/assets/db47916b-475f-4062-b107-d03800b1661b" />

## Conclusion
This project shows how to build a cost-effective CI/CD pipeline without CodeBuild, making deployment faster and automated.
