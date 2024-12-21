# CS50x Final Project: JustDoIt - To-Do List Application  

Managing daily tasks can be challenging, especially when it comes to remembering small errands or planning simple activities. The primary purpose of this project is to simplify task management through an easy-to-use To-Do list application. Whether it’s remembering to book a trip or complete household chores, creating a list helps prioritize and accomplish these tasks efficiently. The **JustDoIt** application provides an intuitive interface to keep track of your tasks and ensures you stay organized.

---

## Features  

**JustDoIt** is a web-based To-Do list application with the following functionalities:  

1. **User Registration**: Only registered users can access the app's features.  
2. **Password Management**: Users can change their password by providing the current one for security.  
3. **Add Tasks**: Easily add new items to the To-Do list.  
4. **Edit Tasks**: Modify tasks after they are added.  
5. **Mark as Done**: Remove completed tasks from the list.  

---

## Prerequisites  

Before running the application, ensure the following software and dependencies are installed on your system. Follow these step-by-step instructions to set up your environment (instructions are tailored for Debian-based systems like Ubuntu):  

```bash
# Update and upgrade system packages
sudo apt update && sudo apt upgrade  

# Install Python and its development tools
sudo apt-get install python3 python3-dev  

# Install pip (Python package manager)
sudo apt-get install python3-pip  

# Install Flask and additional dependencies
pip3 install Flask Flask-Session cs50  

# Install SQLite3 for database management
sudo apt install sqlite3  

# Install code styling tools
sudo pip3 install style50  
sudo apt-get install astyle  

# Upgrade styling tools for the latest features
sudo pip install --upgrade style50

```
 
## Documentation and References

    Python Documentation
    Flask Documentation
    SQLite Documentation
    CS50 Library Documentation
    Style50 Documentation

## Recommended Development Environment

Visual Studio Code is an excellent editor for working with this project. It offers features such as debugging, syntax highlighting, intelligent code completion, and Git integration, making it a great tool for efficient development.
Cloning the Repository

## To clone the project repository, ensure Git is installed:

# Install Git (if not already installed)
sudo apt-get install git  

# Clone the repository
git clone https://github.com/Aiprogrammer2305/CS50x-Final-Project-JustDoIt---To-Do-List-Web-Application.git  

## Code Style Testing

Ensure the code adheres to clean coding principles. Navigate to the project directory and run the following command:

style50 *.py  

Example Output:

Results generated by style50 v2.7.5  
::::::::::::::  
app.py  
::::::::::::::  
Looks good!  
But consider adding more comments!  

## Deployment

To run the application locally, execute the following commands:

# Set the Flask app environment variable
export FLASK_APP=app.py  

# Start the Flask server
flask run  

The application will be available at http://127.0.0.1:5000.
## Project Structure

    Static Files: CSS, JavaScript, and images are stored in the static directory.
    HTML Templates: Located in the templates directory, these define the structure and layout of the web pages.
    Core Application Files:
        app.py: Contains the main logic and routes for the application.
        helpers.py: Includes utility functions for error checking and session management.
        done.db: SQLite database storing user data and task information.
        requirements.txt: Lists all Python dependencies required to run the app.

## Technologies Used

    Python 3: Backend programming language
    Flask: Web framework for Python
    SQLite: Database management system
    HTML5 and CSS: Frontend design
    Bootstrap: CSS framework for responsive design
    CS50 Library: Simplifies Python programming for this project

## Author

Himanshu Ganesh Warulkar
