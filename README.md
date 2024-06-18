[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15273086&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   To install windows 11:
      Ensure your PC has all the required specifications. To do this, download and run PC Health Check.![alt text](<Screenshot 2024-06-17 165239.png>)

      If all is well, ensure to back up your files and documents to avoid losing them.![alt text](<Screenshot 2024-06-17 165647.png>)

      When upgrading from lesser versions, head to the official microsoft website https://www.microsoft.com/software-download/windows11 

      It is recommended to choose Installation Assistant as Installation Media is when you want to clean install Windows 11.![alt text](<Screenshot 2024-06-17 170116 - Copy.png>)

      Agree to the terms and conditions and click install. Ensure your PC remains on and plugged in during this time.![alt text](<Screenshot 2024-06-17 171905.png>)

      After installing, your PC will prompt you to restart it and will begin a thirty minute countdown.![alt text](<Screenshot 2024-06-17 171927.png>)

      After this is over you will have successfully installed Windows 11.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   To install Visual Studio Code:
      Head to your browser and search Visual Studio Download. https://code.visualstudio.com/Download

      Download according to the specifications on your PC.![alt text](<Screenshot 2024-06-17 174037.png>)

      Agree to the terms and conditions by clicking "I accept the agrreement."![alt text](<Screenshot 2024-06-17 174105.png>)

      Click next to and select a folder you would wish it to be stored in.![alt text](<Screenshot 2024-06-17 174122.png>)

      Select next and select additional tasks you would like when installing, such as open with code option. Click next.![alt text](<Screenshot 2024-06-17 174146.png>)

      Click install to start the installation.![alt text](<Screenshot 2024-06-17 174204.png>)

      Click finish and tick the square to launch Virtual Studio Code.![alt text](<Screenshot 2024-06-17 174235.png>)

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   To install Git:
      Navigate to the official git download page and download the required version according to your PC specifications.![alt text](<Screenshot 2024-06-17 175852.png>)

      Double click the downloaded file to extract and launch the installer.

      Review the General Public License and click next.![alt text](<Screenshot 2024-06-17 180516.png>)

      Click next after choosing the installation location.![alt text](<Screenshot 2024-06-17 180533.png>)

      Click next and respond accordingly if you want a start menu folder.![alt text](<Screenshot 2024-06-17 180715.png>)

      Select the text editor you want to use with Git by clicking the drop down bar.![alt text](<Screenshot 2024-06-17 180733.png>)

      The next step asks you to choose the name you want for your initial branch.![alt text](<Screenshot 2024-06-17 180754.png>)

      This next one allows you to choose the PATH environment. Click on the recommended one and continue.![alt text](<Screenshot 2024-06-17 180811.png>)

      You are then prompted to select the SSH client for Git to use.Click next.![alt text](<Screenshot 2024-06-17 180905.png>)

      This next option refers to server certificates. The default option is recommended. Choose and continue.![alt text](<Screenshot 2024-06-17 180922.png>)

      The following selection configures line-ending conversion, which relates to the way data is formatted. The default selection is recommended for Windows. Click Next to proceed.![alt text](<Screenshot 2024-06-17 180937.png>)

      Choose the terminal emulator you want to use. The default minTTY is recommended.![alt text](<Screenshot 2024-06-17 180950.png>)

      The next step allows you to choose what the git pull command will do. The default option is recommended unless you specifically need to change its behavior. Click Next to continue with the installation.![alt text](<Screenshot 2024-06-17 181004.png>)

      The next step is to choose which credential helper to use. Git uses credential helpers to fetch or save credentials. The default option is the most stable one. Select your preferred credential manager and click Next.![alt text](<Screenshot 2024-06-17 181017.png>)

      The next step lets you decide which extra options to enable. If you use symbolic links, which represent shortcuts for the command line, tick the box. Keep file system caching checked and click Next.![alt text](<Screenshot 2024-06-17 181030.png>)

      Depending on which Git version you are installing, it may offer to install experimental features.For the most stable operation, do not install experimental features and click Install.![alt text](<Screenshot 2024-06-17 181045.png>)

      Once the installation is complete, tick the boxes to view the Release Notes or launch Git Bash if you want to start using Git right away, and click Finish.![alt text](<Screenshot 2024-06-17 181056.png>)

   Creating a GitHub account:
      Navigate to https://github.com/.
      Click Sign up.
      Follow the prompts to create your personal account.

   Configuring Git on Windows:
      Type in git config --globaluser.name "your username". This command configures your GitHub account to your git,thus when pushing, the work done will be pushed to a remote repo that is under your GitHub account.![alt text](<Screenshot 2024-06-17 193430.png>)

      This command is followed by git config --globaluser.email "your email". This is to link your email which you used to create your GitHub account with.![alt text](<Screenshot 2024-06-17 193442.png>)


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  To install Python:
      Visit Python's official website http://wwww.python.org

      For the latest python version click the yellow button which immediately installs the latest version. Be sure to confirm your PC specifications before choosing a version to install.![alt text](<Screenshot 2024-06-17 194122.png>)

      To check if you have downloaded an authentic python, go to  git and type in the command python --version. This shows you the version of python you have installed.![alt text](<Screenshot 2024-06-17 195753.png>)

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
      Open git as an administrator. Do this by typing git in your search bar and choosing the 'run as administrator' option.![alt text](<Screenshot 2024-06-17 200032.png>)

   To install pip:
      You would first need to install Python, as pip is included with the Python installation. Here is the command to install Python, which includes pip:![alt text](<Screenshot 2024-06-17 200555.png>)

      This command will install the latest version of Python 3, and pip will be installed along with it. After installing Python, you can verify that pip is installed by running:![alt text](<Screenshot 2024-06-17 200644.png>)

      If you specifically need to install or upgrade pip after installing Python, you can use the following command:![alt text](<Screenshot 2024-06-17 200725.png>)

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

      Visit MySQL download for Windows with this link,https://dev.mysql.com/downloads/windows/installer/5.7.html

      This provides MySQL versions for windows. Choose the one you require according to your device specifications.![alt text](<Screenshot 2024-06-17 201342.png>)

      Double click the file after downloading the installer and follow the prompts to install.


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

       Open Virtual Studio Code and navigate to the activity bar and click on the extensions icon.

      Some of the extensions we will need are Dart, Flutter, Python and Pylance.Search for their names in the search bar and install. It is advisable to install the verified ones.


9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
    Setting up my developer environment has been smooth sailing apart for a few hiccups such as having to delete and reinstall dart due to complications with my device. Some of the customizations I did was on Virtual Studio Code where I installed Maaterial Icon Theme that enhances the look of icons displayed by the IDE.

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
