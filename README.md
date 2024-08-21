[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15301054&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 


    Introduction
This document provided a step-by-step guide to setting up a development environment. The setup included installing Windows 11, Visual Studio Code (VS Code), Git, Python, pip, MySQL, Docker (optional), and configuring various extensions and plugins for an enhanced coding experience.

Operating System: Windows 11 Installation
Steps:
The Windows 11 download page was visited.
The installation media tool was downloaded.
The tool was run, and the on-screen instructions were followed to create a bootable USB drive or upgrade the current system.
The computer was restarted, and it booted from the USB drive for a clean installation.
The prompts were followed to complete the Windows 11 installation.

IDE Installation: Visual Studio Code (VS Code)
Steps:
The VS Code download page was visited.
The appropriate version for Windows was selected and the installer was downloaded.
The installer was run, and the prompts were followed to install VS Code.
VS Code was launched after installation.

Version Control: Git Installation and Configuration
Steps:
The Git download page was visited.
The installer for Windows was downloaded.
The installer was run, and the prompts were followed to install Git.
Git Bash was opened, and the user name and email were configured:
sh
Copy code
git config --global user.name "Abigael Jeruto"
git config --global user.email "jeruto37@gmail.com"
GitHub Setup:
GitHub was visited and an account was created.
A new repository was created.
A local Git repository was initialized and pushed to GitHub:

mkdir my-project
cd my-project
git init
touch README.md
git add README.md
git commit -m "Initial commit"
git remote add origin https://github.com/AbbieMutzie/my-project.git
git push -u origin master


Programming Languages: Python Installation
Steps:
The Python download page was visited.
The installer for the latest version of Python was downloaded.
The installer was run, and the option to add Python to the PATH was checked.
The prompts were followed to complete the installation.

Package Managers: pip Installation
Steps:
Since pip is installed by default with Python, the following command was run to ensure it was installed and updated:
sh
Copy code
python -m ensurepip --upgrade

Database Configuration: MySQL Installation
Steps:
The MySQL download page was visited.
The MySQL Installer for Windows was downloaded.
The installer was run, and the prompts were followed to install MySQL.
MySQL was configured as needed during the installation process.

Development Environments: Docker Installation (Optional)
Steps:
The Docker download page was visited.
Docker Desktop for Windows was downloaded.
The installer was run, and the prompts were followed to install Docker.
Docker Desktop was launched and the initialization steps were followed.

Extensions and Plugins: VS Code Extensions
Recommended Extensions:
Python: For Python development.
GitLens: Enhances Git capabilities.
Prettier: Code formatter.
Docker: Support for Docker.
Steps:
VS Code was opened.
The Extensions view was accessed by clicking the Extensions icon in the Activity Bar on the side of the window.
The desired extensions were searched for and "Install" was clicked.

Challenges and Solutions
Challenges:
Issue: Difficulty in setting up Git and GitHub integration.

Solution: The official documentation and tutorials for Git and GitHub were followed. SSH keys were correctly configured for secure authentication.
Issue: Python not recognized in command line.

Solution: It was ensured that Python was added to PATH during installation. Python was manually added to PATH if necessary.
Issue: MySQL installation errors.

Solution: Conflicting installations or permissions were checked. MySQL community forums were consulted for specific error resolutions.
Reflection:
Setting up a development environment was challenging, especially with compatibility issues and configuration errors. However, following detailed guides and official documentation significantly reduced setup time and ensured a smooth development process.

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
