# Simple Flask To-Do App

This is a simple To-Do web application built using Flask for the backend, and Nginx for serving static files. The application allows users to add, edit, and delete tasks.
# Set Up Environment
Create a virtual environment and activate it (optional, for local development without Docker).

Commands:

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
# Running the Application with Docker
Build and run the Docker containers using Docker Compose.

Commands: 
docker-compose build
docker-compose up

# Accessing the Application
Nginx Proxy (Default): Open your browser and go to http://localhost
Flask Application Directly: Open your browser and go to http://localhost:5000

# Stopping the Application
To stop the application, press CTRL+C in the terminal where docker-compose up is running, or use:

Command:
docker-compose down