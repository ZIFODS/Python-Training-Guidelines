# ​​Python project management​ 
## ​​Guidance, standards, and best practices to follow​ 
Author: Ross Burton (Ross.Burton@zifornd.com) \
Review Date: 03/01/2022

## Introduction and Objectives 

In this document, we will outline the standards and best practices that should be followed when developing Python code at Zifo R&D EU. The document will start with an overview of how to install Python on your local machine and manage multiple installs. This document assumes that you’re using Windows 10 or greater as your operating system. 

We will outline what version control systems you should be using, command line tools in Windows, and how to manage your code. We will then introduce the ZifoPyBuilder tool for setting up your Python projects. Finally, we will outline the best practices that should be followed when writing your Python code. 

## Objectives 

1. Installing Python on your local machine 

2. Setting up the command line and version control tools 

3. Managing your environment and Python packages 

4. Using integrated development environments (IDEs) 

5. Introducing ZifoPyBuilder for your Python projects 

6. Best practices for your python code and projects 

## Installing Python on your local machine 

A complication with Python that many new developers struggle with is juggling the multiple versions of Python that are available for use. In general, unless there is a specific requirement due to legacy code, we encourage people to use Python version 3.x and above. Python 2.7 is an older syntax and is no longer supported. 

The core language is constantly being updated and as of the time of writing this document the most recent stable release is version 3.11. However, you will often require older versions of the Python programming language depending on the packages that you’re using. If you code base is reliant on many open source packages, it is good practice to use a Python version a couple of releases behind. It is possible to have multiple versions installed on our machine and in fact this is standard practice.  

You should install your Python distribution from the official website where you can download an installation executable (https://www.python.org/downloads/). 

## Managing multiple Python versions 

It is possible to install multiple versions of Python on your machine. Upon installing multiple versions of Python, Windows should add each one to your PATH variable, making the different versions of Python available across your applications. The default version of Python will correspond to the first version you installed, but you can change this (see ‘Changing the default version of Python’). The default version can be identified using the following command in the command line: 

```bash
python --version
```

You can access different versions of the Python console using the following commands. In this example, we are accessing version 3.10 and version 3.8:

```bash
py -3.10
```

```bash
py -3.8
```

## Add environment variables 

If when executing the previous example you receive an error despite the relevant version being installed, you may need to manually edit your environment variables.  

1. Enter _“edit environment variables”_ in your search bar 

2. Click _“Edit environment variable for your account”_, this will bring up the “System Properties” window (you might have to login as administrator to access this window) 

3. Click on _“Environment Variables…”_ in the bottom right hand corner 

4. Under _“System variables”_ click on the _“Path”_ variable and then click the _“Edit”_ button 

5. A new window will appear listing all the file paths in the “Path” variable. If your system cannot find the version of Python you are trying to access, it is probably because the path is missing in this list. To access Python there should be two paths in this list, one for the root directory and one for the “Scripts” folder. For example, for Python 3.8 you would expect the following paths: 

`C:\Users\{USER}\AppData\Local\Programs\Python\Python38 `

`C:\Users\{USER}\AppData\Local\Programs\Python\Python38\Scripts`

6. Add missing paths by clicking the _“New”_ button. 

## Changing the default version of Python 

To change the default version of Python on your system, access the Path variable as described in the previous section. The order of the Path’s listed in the “Path” variable dictates the order of priority. Click on the version of Python you want as the default version and click “Move Up” to increase the priority of that Python version. The version listed highest in the order will be the default version. 

## Installing Git for version control and using command line tools 

It is very important that we use version control tools for managing our code locally and for sharing code with our colleagues. The standard practice in Zifo is to use Git. Although it is beyond the scope of this document, the following resources can be used to understand Git and version control: 

1. Introduction to Git and GitHub: https://youtu.be/RGOj5yH7evk  

2. Intermediate Git for professional programmers: https://youtu.be/Uszj_k0DGsg 

Speak to your line manager and discuss with your team about your preferred remote repository and DevOps tool. Across Zifo teams also use Azure DevOps as an alternative to GitHub. For more information about Azure DevOps, see this tutorial: https://youtu.be/4BibQ69MD8c  

Regardless of whether you are using GitHub or Azure DevOps, you will still need to understand the principles of version control and the Git command line tool. Install Git on your local machine by downloading the Windows install executable from the official website: https://git-scm.com/  

Once you have installed Git locally, you will have access to the Git Bash application. Git Bash is an emulation layer for a Linux environment on Windows. Learning Bash (also known as the Unix shell or Linux command language) is a vital skill for any developer.  For those new to Bash, a good introduction video can be found here: https://youtu.be/BFMyUgF6I8Y  

Git Bash can be used like a Linux command line tool to manage your projects, but for a more powerful command line experience on Windows, you can use ConEmu (https://conemu.github.io/) which allows for tabulation of command line panels and can offer access to Windows Command Line, PowerShell, and Git Bash, all within one application. 