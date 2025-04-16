# Jenkins CI/CD Pipeline Project

## Overview
This project demonstrates the implementation of a Continuous Integration and Continuous Deployment (CI/CD) pipeline using **Jenkins**.

The pipeline includes:
- **GitHub integration**: Fetches code from a GitHub repository.
- **Docker**: Uses Docker containers to run Node.js.
- **Jenkinsfile**: A Groovy script that defines the steps in the pipeline, such as fetching the code, building, and testing it.

## Tools & Technologies
- Jenkins
- GitHub
- Docker
- Node.js

## Pipeline Steps
1. **Checkout code from GitHub**
2. **Run Docker container with Node.js**
3. **Execute a shell script to test the Node.js version**

## Screenshots
Below are some screenshots of the pipeline execution:
![alt text](<Screenshot 2025-04-16 121811.png>) ![alt text](<Screenshot 2025-04-16 111842.png>) ![alt text](<Screenshot 2025-04-16 111917.png>) ![alt text](<Screenshot 2025-04-16 113739.png>) ![alt text](<Screenshot 2025-04-16 121059.png>) ![alt text](<Screenshot 2025-04-16 121740.png>)



## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/NamanGit45/Jenkins-cicd-pipeline.git