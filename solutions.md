[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15213591&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

DOCUMENTATION:
1.  Select Your Operating System (OS):
I use Linux. Debian Distro

2. Install a Text Editor or Integrated Development Environment (IDE):

I installed vscode that I installed using terminal with the command: 

- sudo apt-get install wget gpg
- wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg
- sudo install -D -o root -g root -m 644 packages.microsoft.gpg /etc/apt/keyrings/packages.microsoft.gpg
- echo "deb [arch=amd64,arm64,armhf signed-by=/etc/apt/keyrings/packages.microsoft.gpg] https://packages.microsoft.com/repos/code stable main" |sudo tee /etc/apt/sources.list.d/vscode.list > /dev/null
- rm -f packages.microsoft.gpg
- sudo apt install apt-transport-https
- sudo apt update
- sudo apt install code


3. Set Up Version Control System:
 - I set up git and initialized it using git init command
  - I had already created a github account, link: https://github.com/ericksaddam


4. Install Necessary Programming Languages and Runtimes:
    - Linux comes with python preinstalled. so no need in install
5. Install Package Managers:
   If applicable, install package managers like pip (Python).
Linux comes with python preinstalled. so no need in install
6. Configure a Database (MySQL):
    - sudo apt update
    - sudo apt install mysql-server
    - sudo mysql_secure_installation
    - sudo nano /etc/mysql/mysql.conf.d/mysqld.cnf and configured memory and cache settings
7. Set Up Development Environments and Virtualization (Optional):
  - I did python -m venv myvenv
8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   - I installed rainbow extension to help in syntax highlighting
   - I installed git extension for version control
   - I installed pylint extension for linting.

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
