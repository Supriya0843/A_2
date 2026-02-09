# A_2

# Intern DevOps App
A simple web application built to demonstrate a basic DevOps workflow using GitHub, CI Pipeline, Docker and finally the Deployment.

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
 
 3. Installing the dependencies:
    
        pip install -r requirements.txt
 
 4. Running the application:

        python app.py
 
 5. Accessing the application:
    - http://127.0.0.1:5000/
    
    - http://127.0.0.1:5000/health
 
 

# Running the application using Docker
1. Building Docker image:
   
         docker build -t intern-devops-app .
2. Running Docker container:
   
         docker run -p 5000:5000 intern-devops-app
   
3. Accessing the application:
   - http://127.0.0.1:5000/

   - http://127.0.0.1:5000/health
   
# CI Pipeline explanation
This project uses GitHub Actions for Continuous Integration (CI).

On every push to the main branch, the pipeline automatically installs dependencies and verifies that the Flask application runs successfully.

# Deployed link
 - https://a-2-2.onrender.com
   
 - https://a-2-2.onrender.com/health
