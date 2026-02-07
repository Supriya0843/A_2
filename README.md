# A_2

# Intern DevOps App
A simple web application built to demonstarte a basic DevOps workflow using GitHub, CI Pipeline, Docker and finally the Deployment.

# Objective
Building a small web application, automate testing with GitHub actions, containerizing it using Docker, and deploying it online using Render.

# Tech Stack
- Python
- Flask
- Docker
- GitHub Actions (CI)

# Running the application locally
 1. Cloning the repository:

        git clone "github-repo-url"
 
 2. Creating virtual environment and activating:
    
        python -m venv venv

        venv\Scripts\activate
 
 4. Installing the dependencies:
    
        pip install -r requirements.txt
 
 6. Running the application:

        python app.py
 
 8. Accessing the application
 
 

# Running the application using Docker
1. Building Docker image:
   
         docker build -t intern-devops-app .
3. Running Docker container:
   
         docker run -p 5000:5000 intern-devops-app
5. Accessing the application
# CI Pipeline explanation
This project uses GitHub Actions for Continuous Integration (CI).

# Deployed link
