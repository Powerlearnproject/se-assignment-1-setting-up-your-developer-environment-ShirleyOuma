[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15277023&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
Answer: I downloaded Windows 10 Operating System.
Overview
Windows 10 is a widely used operating system developed by Microsoft. It offers robust support for a variety of development tools and is compatible with many software applications. To ensure the system is up-to-date, I followed these steps:
   I clicked on the Start menu and select Settings.
   Click on Update & Security.
   In the Windows Update tab, I clicked on Check for updates.
   Updates were available![windowsScreenshot 2024-06-18 144658 ](https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-ShirleyOuma/assets/117755640/5048ef6d-3d24-42bd-bdd0-5f4ae60b9d21)


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
Answr: Text Editor or IDE: Visual Studio Code
Installation Steps
I Download Visual Studio Code on Visual Studio Code download page.
I Select the appropriate installer for Windows.
I Opened the downloaded .exe file and follow the installation prompts.
I Agreed to the license terms and select your preferred installation options.
Clicked Finish to complete the installation.
Launched the Visual Studio Code.
      Essential Extensions
Python:
Provides support for Python development, including linting and debugging.
Installed by clicking on the Extensions view icon (Ctrl+Shift+X) and searching for "Python" then install.
Docker:
Provides tools for building, managing, and running containerized applications.
Installed from the Extensions view by searching for "Docker" then install.
Prettier - Code Formatter:
Helps to Automatically formats your code to ensure a consistent style.
Installed from the Extensions view by searching for "Prettier".
   Configuration Tips
Python:
After installation, I set the Python interpreter path by pressing Ctrl+Shift+P, typing Python: Selected Interpreter, and choosed the correct interpreter.
Docker:
Docker extension requires Docker Desktop to be installed and running. It integrates with Docker CLI commands and provides management options in the VS Code UI.
Prettier:
I Set Prettier as the default formatter by navigating to File > Preferences > Settings, searching for Editor: Default Formatter, and selecting Prettier.
![VSScreenshot 2024-06-18 145537](https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-ShirleyOuma/assets/117755640/749a0503-4d94-4c0b-8719-ff89e7eab4cc)

4. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
Answer: Version Control System: Git and GitHub
Setting Up Git
Visited the Git download page and download the installer.
Opened the downloaded .exe file and follow the setup instructions.
Used the recommended settings.
Opened Command Prompt and typed git --version to check that Git is installed correctly.
Setting Up GitHub Repository
I already have GitHub Account:
After logging in, I clicked on the + icon in the upper-right corner and select New repository.
Filled in the repository name as "Testing" and choosed to initialize with a README. Clicked Create repository.
I Copied the repository URL and use the git clone command in Git Bash to clone it to my local machine.
Making the First Commit I Navigated to the Repository Folder by Using cd to change directory to the cloned repository folder.
I Created a file called "Testing1"
Add a new file in the repository.
Used git add . to stage all changes for the next commit.
Commit the Changes: Used git commit -m "change testing1" to commit the changes with a message.
Pushed to GitHub: Used git push to push my changes to the remote repository on GitHub. git push origin main![gtScreenshot 2024-06-18 152045](https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-ShirleyOuma/assets/117755640/8dc5654a-90d6-4b92-93ec-b5fdb6d988cd)



5. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
I already have python installed.![pyScreenshot 2024-06-18 152304](https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-ShirleyOuma/assets/117755640/99b02db1-05d0-4c15-be3c-2bb97be55f73)

6. Install Package Managers:
   If applicable, install package managers like pip (Python).

7. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   MySQL Installation:
   Downloaded MySQL Installer from the official site.
   Chose a setup type (Developer Default recommended).
   Followed the prompts to install MySQL Server, Workbench, and other tools.
   Configured MySQL Server:
   Setted up the server configuration and root password.
   Completed the installation and configuration.
   Did some project: ![sqScreenshot 2024-06-18 160505](https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-ShirleyOuma/assets/117755640/3b0cb254-4332-4d6e-9fd5-abf6338228bd)

9. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.![dkScreenshot 2024-06-18 161133](https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-ShirleyOuma/assets/117755640/548d911a-c8cc-4fa8-aa3d-e02a39250dea)

10. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

11. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

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
