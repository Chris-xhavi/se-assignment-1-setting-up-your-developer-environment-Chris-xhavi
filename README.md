[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15272390&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11


Windows Update:

Go to Settings > Update & Security > Windows Update.
Click Check for updates. If your PC is eligible, you’ll see the option to download and install Windows 11.
Windows 11 Installation Assistant:

Visit the Windows 11 download page.
Click Download now under Windows 11 Installation Assistant.
Run the Installation Assistant and follow the on-screen instructions.
Create Windows 11 Installation Media:

On the Windows 11 download page, click Download now under Create Windows 11 Installation Media.
Run the Media Creation Tool.
Select Create installation media (USB flash drive, DVD, or ISO file) for another PC and follow the prompts.
Use the media to install Windows 11 on your PC.
4. Install Windows 11
Using Windows Update or Installation Assistant:
Follow the on-screen prompts to begin the installation.
Your PC will restart several times during the process.
After the installation is complete, follow the setup prompts to configure Windows 11.
Using Installation Media:
Insert the USB flash drive or DVD into the PC where you want to install Windows 11.
Restart your PC and boot from the USB or DVD.
Follow the on-screen instructions to install Windows 11. Select your language, time, and keyboard preferences.
Click Install now.
Enter your product key if prompted. If you don’t have one, click I don’t have a product key.
Select the Windows 11 edition you want to install.
Choose the type of installation: Upgrade or Custom (for a clean installation).
Follow the prompts to complete the installation.
5. Set Up Windows 11
Once the installation is complete, follow the on-screen instructions to:

Set up your region and keyboard layout.
Connect to a network.
Set up your Microsoft account or create a local account.
Customize your privacy settings.
Choose settings for services and apps.
6. Install Drivers and Updates
After installation, go to Settings > Update & Security > Windows Update to check for the latest updates and drivers to ensure your system is up to date.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Visit the Official Website:
Go to the Visual Studio Code website.

Download the Installer:
On the homepage, you will see a download button. It usually auto-detects your operating system. Click the download button to download the installer.

For Windows, you will download a .exe file.
Run the Installer:
Locate the downloaded .exe file and double-click it to run the installer.

Setup Wizard:
Follow the prompts in the setup wizard:

Accept the license agreement.
Choose the installation location (the default is usually fine).
Select additional tasks:
Create a desktop icon (optional).
Add "Open with Code" action to Windows Explorer file context menu (recommended).
Add "Open with Code" action to Windows Explorer directory context menu (recommended).
Register Code as an editor for supported file types (recommended).
Install:
Click the Install button and wait for the installation to complete.

Launch VS Code:
Once the installation is complete, you can check the option to launch Visual Studio Code and click Finish.


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

Windows:

Download the Git installer from the official Git website.
Run the installer and follow the installation wizard. Choose the default settings unless you have specific requirements.

Open the Terminal or Git Bash.

Set your user name and email address. These will be associated with your commits:

sh
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Verify your configuration:

sh
Copy code
git config --global --list
Creating a GitHub Account
Go to the GitHub website.
Click on "Sign up" and follow the prompts to create a new account.
Verify your email address to complete the setup.
Initializing a Git Repository and Making Your First Commit
Navigate to your project directory:

sh
Copy code
cd path/to/your/project
Initialize a Git repository:

sh
Copy code
git init
Add your project files to the staging area:

sh
Copy code
git add .
Commit the files:

sh
Copy code
git commit -m "Initial commit"
Pushing Your Repository to GitHub
Create a new repository on GitHub:

Go to your GitHub profile.
Click on the "+" icon at the top-right corner and select "New repository."
Name your repository and set it to public or private.
Do not initialize the repository with a README, .gitignore, or license (these can be added later if needed).
Link your local repository to the GitHub repository:

sh
Copy code
git remote add origin https://github.com/your-username/your-repository.git
Push your commits to GitHub:

sh
Copy code
git push -u origin master




4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Go to the official Python website: python.org.
Navigate to the Downloads section and select the latest version of Python for Windows.
Download the installer.
Run the Installer:

Run the downloaded installer.
Make sure to check the box that says "Add Python to PATH."
Select "Install Now" or customize the installation as needed.
Verify Installation:

Open Command Prompt.
Type python --version and press Enter. You should see the Python version number displayed.
You can also check the installation by typing pip --version to ensure the package manager is installed.
Setting Up Python Environment
Update Pip:

Open Command Prompt.
Type python -m pip install --upgrade pip and press Enter.
Install Virtual Environment:

Open Command Prompt.
Type pip install virtualenv and press Enter.
Create a virtual environment by navigating to your project directory and typing python -m venv venv.
Activate Virtual Environment:

To activate the virtual environment, use the command .\venv\Scripts\activate on Command Prompt.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).

Download the installer from the website.
Run the installer and make sure to check the box that says "Add Python to PATH."
Click on "Install Now" and follow the installation instructions.
After installing Python, verify the installation by opening your terminal or command prompt and running:

sh
Copy code
python --version
or

sh
Copy code
python3 --version
You should see the version of Python that you installed.

3. Installing pip
pip usually comes with Python by default. You can verify if pip is installed by running:

sh
Copy code
pip --version
or

sh
Copy code
pip3 --version
If pip is not installed, you can install it using the following steps:

For Windows and macOS:
Download the get-pip.py script by running:
sh
Copy code
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
Run the script using Python:
sh
Copy code
python get-pip.py
or
sh
Copy code
python3 get-pip.py
For Linux:
Use your package manager to install pip. For example, on Ubuntu:
sh
Copy code
sudo apt update
sudo apt install python3-pip
4. Verify pip Installation
After installation, verify pip by running:

sh
Copy code
pip --version
or

sh
Copy code
pip3 --version
You should see the version of pip that was installed.

5. Using pip
You can now use pip to install Python packages. For example, to install a package like requests, run:

sh
Copy code
pip install requests
or

sh
Copy code
pip3 install requests


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Go to the MySQL Website:

Navigate to the MySQL Community Downloads page.
Select Your Operating System:

Choose your operating system from the list (e.g., Windows, macOS, Linux).
Download MySQL Installer:

For Windows, you can download the MySQL Installer. For macOS and Linux, download the appropriate package file (DMG for macOS, DEB/RPM for Linux).
Step 2: Install MySQL
On Windows:
Run the Installer:

Double-click the downloaded installer file to run it.
Choose Setup Type:

Select a setup type (Developer Default, Server only, Full, Custom). For a typical installation, choose "Developer Default."
Follow Installation Wizard:

Follow the prompts in the installation wizard, including accepting the license agreement and selecting the installation path.
Configure MySQL Server:

During the configuration step, you will set the MySQL server options. This includes setting the root password and creating user accounts if desired.
Complete Installation:

After configuration, click "Execute" to begin the installation process. Once completed, click "Finish."
On macOS:
Run the DMG File:

Open the downloaded DMG file and follow the on-screen instructions to install MySQL.
Configure MySQL:

After installation, you may need to initialize and start the MySQL server using the following terminal commands:
bash
Copy code
sudo mysql_secure_installation
sudo mysql.server start
On Linux (Ubuntu Example):
Update Package Index:

Open a terminal and run:
bash
Copy code
sudo apt update
Install MySQL Server:

Install MySQL using:
bash
Copy code
sudo apt install mysql-server
Secure MySQL Installation:

Run the security script:
bash
Copy code
sudo mysql_secure_installation
Start MySQL Service:

Ensure the MySQL service is running:
bash
Copy code
sudo systemctl start mysql
sudo systemctl enable mysql
Step 3: Verify Installation
Open MySQL Command-Line Client:

On Windows, you can find it in the Start Menu. On macOS and Linux, open a terminal.
Log in to MySQL:

Use the following command and enter your root password:
bash
Copy code
mysql -u root -p
Check MySQL Version:

To confirm the installation, you can check the version by running:
sql




7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.



8. Explore Extensions and Plugins:
   Go to the MySQL Website:
Visual Studio Code (VS Code):

ESLint: Helps enforce coding standards and identify common errors in JavaScript.
GitLens: Enhances Git integration, providing insights into code changes, authors, and commit history.
Prettier: Automatically formats code according to predefined rules, ensuring consistency.
Docker: Facilitates Dockerfile and docker-compose.yml editing, Docker commands, and container management within VS Code.
Live Server: Launches a local development server with live reload capability for web development.
Remote Development: Allows you to work on a remote machine or container directly from VS Code.
Python Development:

Python Extension for Visual Studio Code: Provides syntax highlighting, code completion, debugging support, and integration with Jupyter notebooks.
Anaconda Extension Pack: Includes essential tools for Python and data science, such as Jupyter, pandas, and numpy.
PyLint: A Python static code analysis tool that checks for errors, enforces coding standards, and identifies code smells.
Django: Adds support for Django framework development, including project creation, code navigation, and template debugging.
Python Test Explorer: Helps discover and run Python tests directly from VS Code.
MySQL Development:

MySQL Syntax Highlighting: Improves readability by highlighting MySQL syntax within VS Code.
MySQL Language Server: Adds language support for MySQL, including code completion and syntax checking.
MySQL Snippets: Provides shortcuts for common MySQL commands, reducing typing effort.
Database Navigator: Facilitates database interaction, allowing you to browse schemas, tables, and execute SQL queries within VS Code.


9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 


[text](<../my documentation.txt>)


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
