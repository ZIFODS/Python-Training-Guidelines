# Zifo Python Training and Guidelines

## Introduction

Welcome to the Zifo Python training documentation and guidelines for programmers!  

The internet is abundant with resources for learning the Python programming langauge, but it can often be overwhelming to understand where to start and what direciton to take given your career and objectives.

In this repository you will find a roadmap for building different Python programming expertise. For each topic we will direct you to a free resource that has been verified by our Python programming team as well as optional paid resources that provide benefits like certifications.

For each resource you will find the following icons to help you decide which resource is best for you:

:gift_heart: Free resource \
:moneybag: Paid resource \
:closed_book: Book/Article/Documentation \
:movie_camera: Video \
:computer: Interactive 

We will try to limit the resources to those that we feel are most appropriate and delivers to best return on investment. When we provide more than one resource recommendation, it is because they are different formats that may suit different learning styles. You do not need to complete all the resources, just pick the one that you feel is best for you.

You will find that some resources overlap with each other and therefore the completion of one may contribute to knowledge acquired for multiple stages of your Python training.

Separate to the training material, you will find a guide on how you should setup Python on your local machine and manage projects for Zifo related work. See `Python_Setup.md` document for details. If you are unfamiliar with concepts such as git, github, and the command line interface, we recommend completing some of the tutorials in the [1.2 Must-know developer skills](#12-must-know-developer-skills) section first.

---
## Table of Contents
1. [Roadmap](#roadmap)
2. [The Basics](#1-the-basics)
3. [Python Developer Skills](#2-python-developer-skills)
4. [Testing and quality control](#3-testing-and-quality-control)
5. [Web development frameworks](#4-web-development-frameworks)
6. [Databases](#5-databases)
7. [Data Science and Machine Learning](#6-data-science-and-machine-learning)
8. [Advanced Python Developer Skills](#7-advanced-python-developer-skills)
9. [Advanced Biomedical Python Programming](#8-advanced-biomedical-python-programming)

---

# Roadmap

The roadmap below gives a high level overview of the stages recommended in our training guidelines.

![roadmap](images/Roadmap.jpg)

Within each stage of the Python training roadmap there are options as to what technologies to learn. We recommend that you focus on one option to begin with and return to additional material at the end of the roadmap.

---

# Minimal required training

## 1 The Basics

The resources in this section are recommended as a minimal requirement for anyone that will be using Python. 

[1.1 Basic Syntax](#11-basic-syntax) \
[1.2 Must-know developer skills](#12-must-know-developer-skills)

### 1.1 Basic Syntax

The python ecosystem can sometimes confuse newcomers because of the existance of multiple versions of the language. The most recent version of Python is 3.11.0, but some older projects still use Python 2.7. Python 2.7 is no longer supported and will not be covered in this guide.

Although there are many different versions of Python 3, the syntax has not changed significantly between versions, but many of the libraries have. For this reason, we recommend that you use Python 3.9 or greater for all of your projects.

When learning the basic syntax however, do not be too concerned over the version of Python you are using. The syntax is very similar between versions and you can always upgrade your version later.

:gift_heart: :movie_camera: [Freecodecamp - Python for Beginners](https://www.freecodecamp.org/news/python-programming-course/)

:computer: [Freecodecamp - Python for Everybody](https://www.freecodecamp.org/learn/scientific-computing-with-python/); only the _Python for Everybody_ section is required for basic syntax, however, this resource also contains a lot of other useful material that covers more advanced topics.

### 1.2 Must-know developer skills

These are the skills that you should have independent of Python programming knowledge that are important to use Python professionally. If you are unfamiliar with any of these concepts, we recommend that you complete the tutorials before you start learning any advanced concepts.

[1.2.1 Git and version control](#121-git-and-version-control) \
[1.2.2 Basic command line knowledge](#122-basic-command-line-knowledge) \
[1.2.3 Using IDEs](#123-using-ides) \
[1.2.4 Basic SQL](#124-basic-sql)

#### 1.2.1 Git and version control

:gift_heart: :movie_camera: [Introduction to Git and GitHub](https://youtu.be/RGOj5yH7evk)

:gift_heart: :movie_camera: [Introduction to Git and GitHub](https://youtu.be/Uszj_k0DGsg )

#### 1.2.2 Basic command line knowledge

:gift_heart: :closed_book: [How to Use the Command Line Interface – for Beginners](https://www.freecodecamp.org/news/how-to-use-the-cli-beginner-guide/); recommended reading for all beginners

:gift_heart: :closed_book: [Learn enough command line to be dangerous](https://www.learnenough.com/command-line-tutorial)

:gift_heart: :movie_camera: [Terminal commands you must know](https://www.youtube.com/watch?v=CV-ven_rxhw)

#### 1.2.3 Using IDEs

For most developers we recommend either Visual Studio Code (VSCode) or PyCharm. Whereas VSCode is free, PyCharm has a limited community edition but requires a paid license for the professional version.

:gift_heart: :movie_camera: [Setting up a Python Development with VSCode](https://www.youtube.com/watch?v=-nh9rCzPJ20)

:gift_heart: :closed_book: [Python development with VSCode](https://realpython.com/python-development-visual-studio-code/)

#### 1.2.4 Basic SQL

SQL or "Structured Query Language" is a language used to interact with relational databases. Although you will not need to know SQL to use Python, it is a useful skill to have and will be required for some of the more advanced topics in this guide.

:gift_heart: :movie_camera: [SQL Basics for beginners](https://www.youtube.com/watch?v=zbMHLJ0dY4w)

:gift_heart: :computer: [Learn SQL: SQL Tutorial for Beginners](https://www.programiz.com/sql)

#### 1.2.5 Python package managers and virtual environments

Python has two main package managers, pip and conda. Pip is the default package manager for Python and is used to install packages from the Python Package Index (PyPI). Conda is a package manager that is used to install packages from the Anaconda repository. Conda is also used to manage virtual environments and install packages from other repositories such as Bioconda.

A virtual environment is a tool that helps to keep dependencies required by different projects separate by creating isolated Python environments for them. This is useful because it allows you to work on multiple projects with different dependencies at the same time without having to worry about breaking your other projects.

There are also more advanced package managers such as poetry, pipenv and hatch, which provide additional functionality and environment management. See the `Python_Setup.md` file in this repository for more information on how you should manage your python environments.

If you are new to Python, we recommend that as a mimimum you familarise yourself with venv and conda.

:gift_heart: :closed_book: [A beginners guide to pip](https://realpython.com/lessons/what-is-pip-overview/); beginners should start here

:gift_heart: :closed_book: [Using Python's pip to Manage Your Projects' Dependencies](https://realpython.com/what-is-pip/); a more advanced overview of pip

:gift_heart: :closed_book: [Effective python environment management](https://realpython.com/effective-python-environment/); highly recommended reading to understand different approaches to managing your python environments

## 2 Python Developer Skills

If you have got this far, well done! You have now completed the basics and are ready to start learning some of the more advanced concepts in Python. The resources in this section are recommended for anyone that will be using Python professionally.

[2.1 Data structures and Algorithms](#21-data-structures-and-algorithms) \
[2.2 Object-oriented programming](#22-object-oriented-programming) \
[2.3 Comprehensions, Iterators, and Generators](#23-comprehensions-iterators-and-generators) \
[2.4 Map, Reduce, and Lambda functions](#24-map-reduce-and-lambda-functions) \
[2.5 Regular Expressions](#25-regular-expressions) \
[2.6 Caching](#26-caching) \
[2.7 Multi-processing and multi-threading](#27-multi-processing-and-multi-threading) \
[2.8 Other advanced syntax and concepts](#28-other-advanced-syntax-and-concepts)

### 2.1 Data structures and Algorithms

Data structures and algorithms are the building blocks of computer science. They are the fundamental concepts that are used to solve problems in the real world. In this section, we will cover some of the most common concepts that are applicable not just to Python but all software development.

:gift_heart: :closed_book: [Data structures in Python](https://realpython.com/python-data-structures/)

:moneybag: :closed_book: [Grokking Algorithms:  
An illustrated guide for programmers and other curious people](https://www.manning.com/books/grokking-algorithms)

:gift_heart: :movie_camera: [Data Structures and Algorithms in Python - Full Course for Beginners](https://www.youtube.com/watch?v=pkYVOmU3MgA)


### 2.2 Object-oriented programming

Python is an object-oriented programming language. This means that it supports object-oriented programming (OOP) concepts such as classes, inheritance, and encapsulation. In this section, we will link to resources that cover some of the most common OOP concepts that are applicable not just to Python but all software development.

:gift_heart: :movie_camera: [Object Oriented Programming with Python - Full Course for Beginners](https://www.youtube.com/watch?v=Ej_02ICOIgs)

:gift_heart: :closed_book: [Object-oriented programming in Python](https://realpython.com/python3-object-oriented-programming/)

:moneybag: :computer: :movie_camera: [Object-oriented Programming in Python: Create Your Own Adventure Game](https://www.futurelearn.com/courses/object-oriented-principles)

### 2.3 Comprehensions, Itertools, and Generators

Although Python is an object-oriented programming language, it also supports functional programming concepts such as comprehensions (If you're wondering what we mean by object-oriented programming and functional programming, and the differences between them, checkout this [article](https://www.geeksforgeeks.org/difference-between-functional-programming-and-object-oriented-programming/)). In this section, we will link to resources that cover these concepts.

:gift_heart: :closed_book: [Comprehensions in Python](https://realpython.com/list-comprehension-python/)

:gift_heart: :movie_camera: [Python Tutorial: Comprehensions - How they work and why you should be using them](https://www.youtube.com/watch?v=3dt4OGnU5sM)

:gift_heart: :closed_book: [Itertools in Python](https://realpython.com/python-itertools/)

:gift_heart: :closed_book: [Generators in Python](https://realpython.com/introduction-to-python-generators/)

:gift_heart: :movie_camera: [Intermediate Python Programming Course](https://www.youtube.com/watch?v=HGOBQPFzWKo); this video covers multiple intermediate python concepts that are applicable to many topics in this section

:gift_heart: :movie_camera: [Python Generators Explained](https://www.youtube.com/watch?v=u3T7hmLthUU)

### 2.4 Map, Reduce, and Lambda functions

Map, Reduce, and Lambda functions are functional components in Python that are used to perform operations on lists. In this section, we will link to resources that cover these concepts.

:gift_heart: :movie_camera: [Lambda in Python - Advanced Python 08 - Programming Tutorial - Map Filter Reduce](https://www.youtube.com/watch?v=D2TJ9wvSP94)

:gift_heart: :movie_camera: [Intermediate Python Programming Course](https://www.youtube.com/watch?v=HGOBQPFzWKo); this video covers multiple intermediate python concepts that are applicable to many topics in this section

:gift_heart: :closed_book: [Lambda functions](https://book.pythontips.com/en/latest/lambdas.html)

:gift_heart: :closed_book: [Map, Filter, and Reduce in Python](https://book.pythontips.com/en/latest/map_filter.html)

### 2.5 Regular Expressions

Regular expressions or "regex" are a powerful tool that can be used to search for patterns in text. In Python, regular expressions are implemented in the `re` module. 

:gift_heart: :movie_camera: [Intermediate Python Programming Course](https://www.youtube.com/watch?v=HGOBQPFzWKo); this video covers multiple intermediate python concepts that are applicable to many topics in this section

:gift_heart: :movie_camera: [Regular Expressions in Python](https://www.youtube.com/watch?v=nxjwB8up2gI)

:gift_heart: :closed_book: [Regular Expressions: Regexes in Python](https://realpython.com/regex-python/)

### 2.6 Caching

Caching is a technique that is used to improve the performance of applications.

:gift_heart: :movie_camera: [The single most useful decorator in Python](https://www.youtube.com/watch?v=DnKxKFXB4NQ)

:gift_heart: :closed_book: [Caching in Python using the LRU Cache strategy](https://realpython.com/lru-cache-python)


### 2.7 Multi-processing and multi-threading

:gift_heart: :movie_camera: [Intermediate Python Programming Course](https://www.youtube.com/watch?v=HGOBQPFzWKo); this video covers multiple intermediate python concepts that are applicable to many topics in this section

:gift_heart: :closed_book: [Multi-processing in Python](https://realpython.com/python-concurrency/)

:gift_heart: :movie_camera: [Next-Level Concurrent Programming In Python With Asyncio](https://www.youtube.com/watch?v=GpqAQxH1Afc)

### 2.8 Other advanced syntax and concepts

Here we provide resources for other advanced Python concepts that are not covered in the previous sections but are enormously useful for Python developers.

:gift_heart: :movie_camera: [Dunder/Magic Methods](https://www.youtube.com/watch?v=z11P9sojHuM)

:gift_heart: :movie_camera: [Decorators](https://www.youtube.com/watch?v=tfCz563ebsU)

:gift_heart: :movie_camera: [Encapsulation](https://www.youtube.com/watch?v=FDdfGFhY9Ms)

:gift_heart: :movie_camera: [Python dataclasses will save you HOURS](https://www.youtube.com/watch?v=vBH6GRJ1REM)

:gift_heart: :movie_camera: [Collections](https://www.youtube.com/watch?v=QswQA1lRIQY)

## 3 Testing and quality control
 
When you write production ready Python code, you should always write tests for your code. This is because tests are a great way to ensure that your code is working as expected. In this section, we will link to resources that cover some of the most common testing and quality control concepts.

There are a few different tools that can be used to write tests in Python and to quality check your code. We recommend using PyTest and a few specific tools for quality assurance, and will link to resources that cover these tools.

[3.1 PyTest](#31-pytest) \
[3.2 Linting, formatting, and Pre-commit](#32-linting-formatting-and-pre-commit)\
[3.3 Documentation](#33-documentation)\
[3.4 Logging](#34-logging)\
[3.5 Type hints](#35-type-hints)

### 3.1 PyTest

:gift_heart: :closed_book: [Effective Python Testing With Pytest](https://realpython.com/pytest-python-testing/)

:gift_heart: :movie_camera: [PyTest Tutorial | Unit Testing Framework In Python](https://www.youtube.com/watch?v=byaxg00Gf9I)

### 3.2 Linting, formatting, and Pre-commit

:gift_heart: :closed_book: [Linting and Formatting in Python](https://realpython.com/python-code-quality/); recommended reading for all

:gift_heart: :movie_camera: [Keeping your repo tidy with Pre-commit](https://www.youtube.com/watch?v=psjz6rwzMdk); recommended video for all

### 3.3 Documentation

Writing documentation for your code is a great way to ensure that your code is easy to understand and use. All Python developers at Zifo are required to write docstrings and documentation for their code. 

:gift_heart: :movie_camera: [Python Docstrings | Python Best Practices](https://www.youtube.com/watch?v=0YUdYk5E-w4); recommended video for all

:gift_heart: :movie_camera: [Top 5 Ways To Document Your Code](https://www.youtube.com/watch?v=uPMxUnBjGG8); recommended video for all

### 3.4 Logging

:gift_heart: :movie_camera: [Intermediate Python Programming Course](https://www.youtube.com/watch?v=HGOBQPFzWKo); this video covers multiple intermediate python concepts that are applicable to many topics in this section

:gift_heart: :movie_camera: [Logging in Python || Learn Python Programming](https://www.youtube.com/watch?v=g8nQ90Hk328)

:gift_heart: :closed_book: [Logging in Python](https://realpython.com/python-logging/)

### 3.5 Type hints

At zifo we recommend using Type hints in your code. Type hints are a great way to ensure that your code is easy to understand and use, and can help you catch bugs before they happen.

:gift_heart: :movie_camera: [Python Typing - Type Hints & Annotations](https://www.youtube.com/watch?v=QORvB-_mbZ0)

:gift_heart: :closed_book: [Type Hints –– An Introduction](https://cpske.github.io/ISP/type-hints/introduction)


# Advanced optional training

Congratulations on completing the core Python sections and mandatory content! In this section, we will link to resources that cover some of the most common advanced Python concepts. These are not mandatory for all Python developers at Zifo, but are highly recommended for those who are interested in learning more about Python.

You can choose from the following topics:

* Web development frameworks - useful for those who want to build web applications
* Databases - useful for web developers and data scientists alike
* Data Science and Machine Learning - useful for data scientists and machine learning engineers
* Other advanced topics - useful for all Python developers
* Advanced Biomedical Python Programming - useful for bioinformaticians and biomedical engineers

## 4 Web development frameworks

There are many different web development frameworks that can be used to build web applications in Python. Here we will cover resources for the most popular frameworks. It is best to focus on one framework to begin with, and then move on to others once you have a good understanding of web development in Python. If you are new to web development, we recommend starting with Flask or FastAPI.

**Note** - python is typically used for the backend of web applications, and Javascript is typically used for the frontend. The resources here will focus on Python, but should you require resources for learning Javascript and frontend development, we recommend starting with the [Front End Development Library certification on freeCodeCamp](https://www.freecodecamp.org/learn/front-end-development-libraries/). You should then investigate resources for full-stack development with Python.

[4.1 Flask](#41-flask) \
[4.2 Django](#42-django) \
[4.3 FastAPI](#43-fastapi) \
[4.4 Testing with Selenium](#44-testing-with-selenium)

### 4.1 Flask

Flask is a lightweight and flexible web development framework that is very popular in the Python community. Compared to Django, Flask is much simpler and easier to learn, but requires more work to set up and configure.

:gift_heart: :movie_camera: [Flask Course - Python Web Application Development](https://www.youtube.com/watch?v=Qr4QMBUPxWo)

:gift_heart: :closed_book: [Flask Tutorial](https://flask.palletsprojects.com/en/2.0.x/tutorial/)

### 4.2 Django

Django is a popular web development framework that is used to build large and complex web applications. Django is more complex than Flask, but is much more powerful and flexible. It also has a large community of developers and a lot of documentation.

:gift_heart: :movie_camera: [Python Backend Web Development Course (with Django)](https://youtu.be/jBzwzrDvZ18?t=13108); watch from 3:38:28 onwards.

:gift_heart: :movie_camera: [Django / Tailwind Tutorial - Code a Netflix Clone](https://www.youtube.com/watch?v=gbyYXgiSgdM); comprehensive practice project for Django but requires some prior understanding

:gift_heart: :closed_book: [Official Django Tutorials](https://docs.djangoproject.com/en/4.1/)

### 4.3 FastAPI

FastAPI is a modern and fast web development framework that is built on top of Python's standard library. FastAPI is ideal for building APIs and microservices, and is very popular in the data science community.

:gift_heart: :movie_camera: [FastAPI Course for Beginners](https://www.youtube.com/watch?v=tLKKmouUams)

:gift_heart: :closed_book: [FastAPI Documentation](https://fastapi.tiangolo.com/)

### 4.4 Testing with Selenium

Selenium is a popular tool for testing web applications. It can be used to automate the testing of web applications, and can be used to test both frontend and backend code.

:gift_heart: :movie_camera: [Selenium Course for Beginners - Web Scraping Bots, Browser Automation, Testing](https://www.youtube.com/watch?v=j7VZsCCnptM)

:gift_heart: :closed_book: [Modern Web Automation With Python and Selenium](https://realpython.com/modern-web-automation-with-python-and-selenium/)

## 5 Databases

Databases are used to store and manage data. There are many different types of databases, and each type is best suited to a different use case. In this section, we will cover the most common types of databases, and provide resources for learning how to use them in Python.

[5.1 SQLite](#51-sqlite) \
[5.2 Relational databases with SQLAlchemy](#52-relational-databases-with-sqlalchemy) \
[5.3 Document databases wtih PyMongo and Mongoengine](#53-document-databases-wtih-pymongo-and-mongoengine) \
[5.4 Graph databases with Neo4j](#54-graph-databases-with-neo4j)

### 5.1 SQLite

SQLite is a lightweight and easy to use database that is built into Python. It is ideal for small projects and prototyping, but is not suitable for large-scale applications.

:gift_heart: :movie_camera: [SQLite Databases With Python - Full Course](https://www.youtube.com/watch?v=byHcYRpMgI4)

:gift_heart: :closed_book: [Data Management With Python, SQLite, and SQLAlchemy](https://realpython.com/python-sqlite-sqlalchemy/)

### 5.2 Relational databases with SQLAlchemy

SQLAlchemy is a popular Python library that can be used to connect to and query relational databases. It is a powerful and flexible tool that can be used to build complex applications.

:gift_heart: :movie_camera: [SQLAlchemy Turns Python Objects Into Database Entries](https://www.youtube.com/watch?v=AKQ3XEDI9Mw)

:gift_heart: :closed_book: [SQLAlchemy Documenation Tutorial](https://docs.sqlalchemy.org/en/14/orm/tutorial.html)

### 5.3 Document databases wtih PyMongo and Mongoengine

MongoDB is a popular document database that is used to store and manage data in JSON-like documents. MongoDB is a NoSQL database, which means that it does not use SQL to query data.

In Python, we can use PyMongo to connect to and query MongoDB databases. PyMongo is a low-level library that is very flexible, but requires a lot of work to set up and configure. For this reason, we recommend using Mongoengine instead. Mongoengine is a high-level library that is built on top of PyMongo, and provides a more convenient and intuitive interface for working with MongoDB.

:gift_heart: :closed_book: [MongoDB Basics](https://www.mongodb.com/basics); recommended reading for all new-comers to NoSQL

:gift_heart: :movie_camera: [MongoDB with Python Crash Course - Tutorial for Beginners](https://www.youtube.com/watch?v=E-1xI85Zog8&t=2466s); introduction to MongoEngine

:gift_heart: :closed_book: [Python and MongoDB: Connecting to NoSQL Databases](https://realpython.com/introduction-to-mongodb-and-python/); use this resource if you need to learn PyMongo in detail

:moneybag: :closed_book: [MongoDB and Python](https://www.oreilly.com/library/view/mongodb-and-python/9781449312817/); great resource if you need to understand MongoDB in detail for high-performance applications
 
### 5.4 Graph databases with Neo4j

Neo4j is a popular graph database that is used to store and manage data in a graph structure. Graph databases are ideal for storing and querying data that has a complex relationship structure.

:gift_heart: :computer: [Neo4j Graph Academy](https://graphacademy.neo4j.com/); complete the _Beginners_ pathway followed by the _Building Neo4j Applications with Python_ course

:gift_heart: :closed_book: [Neo4j Python Driver Documentation](https://neo4j.com/docs/driver-manual/1.7/get-started/)

:money_bag: :closed_book: [Graph Algorithms: Practical Examples in Apache Spark and Neo4j](https://www.amazon.co.uk/Graph-Algorithms-Mark-Needham/dp/1492047686); for those who want to learn more about graph data analytics

## 6 Data Science and Machine Learning

Python is becoming the predominant language for data science and machine learning. In this section, we will cover the most popular Python libraries for data science and machine learning.

[Pre-requisites](#pre-requisites)\
[6.1 JupyterLab](#61-jupyterlab) \
[6.2 Numpy and Pandas](#62-numpy-and-pandas) \
[6.3 Data visualisation with Matplotlib and Seaborn](#63-data-visualisation-with-matplotlib-and-seaborn) \
[6.4 Interactive plotting and Dashboards with Plotly and Dash](#64-interactive-plotting-and-dashboards-with-plotly-and-dash) \
[6.5 Streamlit](#65-streamlit) \
[6.6 Scientific programming with SciPy](#66-scientific-programming-with-scipy) \
[6.7 Statistical modelling with Statmodels](#67-statistical-modelling-with-statmodels) \
[6.8 Machine learning with Scikit-Learn](#68-machine-learning-with-scikit-learn) \
[6.9 Time-series analysis](#69-time-series-analysis) \
[6.10 Deep learning](#610-deep-learning) \
[6.11 NLP](#611-nlp) \
[6.12 Probablistic models with PyMC3 and pomegranate](#612-probablistic-models-with-pymc3-and-pomegranate) \
[6.13 Model explanation and interpretation](#613-model-explanation-and-interpretation)

### Pre-requisites

Data science and machine learning require a strong understanding of mathematics and statistics. If you are new to these topics, we recommend that you complete the following courses before proceeding with the resources in this section:

:gift_heart: :movie_camera: [Statistics Fundamentals](https://www.youtube.com/watch?v=xxpc-HPKN28&t=24721s)

:gift_heart: :movie_camera: [Essence of linear algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

:gift_heart:/:moneybag: :movie_camera: [Mathematics for Machine Learning on Coursera](https://gb.coursera.org/specializations/mathematics-machine-learning)

:gift_heart: :closed_book: [Mathematics for Machine Learning](https://mml-book.github.io/book/mml-book.pdf); for advanced learners

### 6.1 JupyterLab

JupyterLab is a popular open-source web application that can be used to create and share documents that contain live code, equations, visualisations and narrative text. JupyterLab is ideal for data science and machine learning, as it allows you to combine code, data and results in a single document.

:gift_heart: :closed_book: [JupyterLab Documentation](https://jupyterlab.readthedocs.io/en/stable/)

:gift_heart: :movie_camera: [How To Setup Jupyter Lab in 2022](https://www.youtube.com/watch?v=BtYXPY-A9_M)

### 6.2 Numpy and Pandas

Numpy and Pandas are two of the most popular Python libraries for data science and machine learning. Numpy is a library for working with multi-dimensional arrays, and Pandas is a library for working with tabular data.

:gift_heart: :movie_camera: [Data Analysis with Python Course - Numpy, Pandas, Data Visualization](https://www.youtube.com/watch?v=GPVsHOlRBBI)

:moneybag: :closed_book: [Python for Data Analysis](https://www.amazon.co.uk/Python-Data-Analysis-3e-Wrangling/dp/109810403X); covers numpy, pandas, and data analysis in Jupyter

### 6.3 Data visualisation with Matplotlib and Seaborn

Matplotlib and Seaborn are two of the most popular Python libraries for data visualisation. Matplotlib is a low-level library that provides a lot of flexibility, but requires a lot of work to set up and configure. Seaborn is a high-level library that is built on top of Matplotlib, and provides a more convenient and intuitive interface for data visualisation.

:gift_heart: :closed_book: [Matplotlib Documentation](hhttps://matplotlib.org/stable/tutorials/index.html)

:gift_heart: :movie_camera: [Matplotlib Tutorial : Matplotlib Full Course](https://www.youtube.com/watch?v=wB9C0Mz9gSo)

:gift_heart: :closed_book: [Seaborn Documentation](https://seaborn.pydata.org/tutorial.html)

:gift_heart: :movie_camera: [Seaborn Tutorial for Beginners in Python](https://www.youtube.com/watch?v=MyhBYkWarBE)

### 6.4 Interactive plotting and Dashboards with Plotly and Dash

Plotly is an interactive data visualisation library that can be used to create interactive plots and dashboards. Dash is a Python library for building dashboards and web applications that utilise Plotly for data visualisation.

:gift_heart: :closed_book: [Plotly Documentation](https://plotly.com/python/)

:gift_heart: :movie_camera: [Plotly Tutorial](https://www.youtube.com/watch?v=GGL6U0k8WYA)

:gift_heart: :closed_book: [Dash Documentation](https://dash.plotly.com/)

:gift_heart: :movie_camera: [Getting Started With Dash](https://www.youtube.com/watch?v=XOFrvzWFM7Y)

### 6.5 Streamlit

An alternative to Dash is Streamlit, a Python library for building web applications for data science and machine learning. Streamlit is ideal for building data science and machine learning prototypes, as it allows you to quickly build and deploy web applications that can be used to explore and visualise data, and to test machine learning models.

:gift_heart: :closed_book: [Streamlit Documentation](https://docs.streamlit.io/library/get-started)

:gift_heart: :movie_camera: [Build 12 Data Science Apps with Python and Streamlit - Full Course](https://www.youtube.com/watch?v=JwSS70SZdyM)

### 6.6 Scientific programming with SciPy

SciPy is a collection of Python libraries for scientific computing. SciPy contains modules for linear algebra, optimisation, integration, interpolation, special functions, FFT, signal and image processing, ODE solvers and other tasks commonly encountered in scientific computing.

:gift_heart: :closed_book: [SciPy Documentation](https://docs.scipy.org/doc/scipy/reference/)

:gift_heart: :movie_camera: [SciPy Tutorial (2022): For Physicists, Engineers, and Mathematicians](https://www.youtube.com/watch?v=jmX4FOUEfgU)

:moneybag: :closed_book: [Elegant SciPy](https://www.amazon.co.uk/Elegant-SciPy-Juan-Nunez-iglesias/dp/1491922877)

### 6.7 Statistical modelling with Statmodels 

Statmodels is a Python library for statistical modelling. Statmodels contains modules for regression, time series analysis, classification, clustering, and other tasks commonly encountered in statistical modelling.

:gift_heart: :closed_book: [Statmodels Documentation](https://www.statsmodels.org/stable/gettingstarted.html)

:gift_heart: :movie_camera: [Statistical Modeling with Python](https://www.youtube.com/playlist?list=PLlbbWgBRF8EePgK40-i7aGU2_ky1yujgL)

### 6.8 Machine learning with Scikit-Learn

Scikit-Learn is the most popular Python library for traditional machine learning (i.e. methodologies other than deep learning). Scikit-Learn contains modules for regression, classification, clustering, dimensionality reduction, model selection, preprocessing, feature extraction, feature selection, and other tasks commonly encountered in machine learning.

:moneybag: :closed_book: [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.amazon.co.uk/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1492032646)

:gift_heart: :movie_camera: [Scikit-learn Crash Course - Machine Learning Library for Python](https://www.youtube.com/watch?v=0B5eIE_1vpU)

### 6.9 Time-series analysis

Time-series analysis is a subfield of statistics concerned with the analysis of time-series data. Python has a number of libraries for time-series analysis, including statsmodels, scikit-learn, and PyFlux.

:moneybag: :closed_book: [Practical Time Series Analysis: Prediction with Statistics and Machine Learning](https://www.amazon.co.uk/Practical-Time-Analysis-Aileen-Nielsen/dp/1492041653)

:gift_heart: :movie_camera: [Time Series Analysis in Python](https://www.youtube.com/watch?v=e8Yw4alG16Q)   

:gift_heart: :closed_book: [PyFlux Documentation](https://pyflux.readthedocs.io/en/latest/)

### 6.10 Deep learning

Deep learning is a subfield of machine learning concerned with the use of artificial neural networks for the analysis of data. Python has a number of libraries for deep learning, including TensorFlow, PyTorch, and Keras. 

Those who wish to understand NLP, image analysis, and other complex classification problems should learn deep learning before progressing to other topics. 

The choice of framework depends on the user's preference. TensorFlow is the most popular deep learning framework, but PyTorch is gaining popularity. Keras is a high-level API for TensorFlow and PyTorch, and is ideal for beginners.

:gift_heart: :closed_book: :computer: :movie_camera: [FastAI Practical Deep Learning Course](https://course.fast.ai/)

:moneybag: :closed_book: [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.amazon.co.uk/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1492032646); ideal for learning tensorflow and keras

:moneybag: :closed_book: [Deep Learning for Coders with fastai and PyTorch](https://www.amazon.co.uk/Deep-Learning-Coders-fastai-PyTorch/dp/1492045527); ideal for learning pytorch

### 6.11 NLP

Natural language processing (NLP) is a subfield of computer science concerned with the analysis of natural language data. Python has a number of libraries for NLP, including NLTK, SpaCy, and Haystack.

#### 6.11.1 Fundamentals and NLTK

:gift_heart: :movie_camera: [Introduction to Natural Language Processing ](https://www.youtube.com/watch?v=8S3qHHUKqYk)

:gift_heart: :closed_book: [Natural Language Processing with Python](https://www.nltk.org/book/)

#### 6.11.2 SpaCy

SpaCy is a production-ready Python library for NLP. SpaCy contains modules for tokenisation, part-of-speech tagging, dependency parsing, named entity recognition, text classification, rule-based matching, and other tasks commonly encountered in NLP.

:gift_heart: :closed_book: [SpaCy Documentation](https://spacy.io/usage/spacy-101)

:gift_heart: :movie_camera: [Natural Language Processing with spaCy](https://www.youtube.com/watch?v=dIUTsFT2MeQ)

#### 6.11.3 Haystack

Haystack is a Python library for question answering and information retrieval. Haystack contains modules for document retrieval, question answering, and other tasks commonly encountered in NLP.

:gift_heart: :closed_book: [Haystack Documentation](https://haystack.deepset.ai/tutorials)

### 6.12 Probablistic models with PyMC3 and pomegranate

Probablistic models are a class of statistical models that are used to model uncertainty. Probablistic models are used in a wide range of applications, including machine learning, computer vision, and natural language processing.
Generally, probablistic models are used to model the probability distribution of data using bayesian statistics and monte carlo methods Probablistic models are used to make predictions about the future, and to explain the past.

:gift_heart: :closed_book: [Probabilistic Programming and Bayesian Methods for Hackers](https://dataorigami.net/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)

:gift_heart: :closed_book: [pomegranate Documentation](https://pomegranate.readthedocs.io/en/latest/)

### 6.13 Model explanation and interpretation

Model explanation and interpretation is a subfield of machine learning concerned with the explanation and interpretation of machine learning models. Python has a number of libraries for model explanation and interpretation, including LIME, SHAP, and ELI5.

:gift_heart: :closed_book: [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/)

:gift_heart: :movie_camera: [Explainable AI](https://www.youtube.com/playlist?list=PLV8yxwGOxvvovp-j6ztxhF3QcKXT6vORU)

:gift_heart: :closed_book: [LIME Documentation](https://lime-ml.readthedocs.io/en/latest/)

:gift_heart: :closed_book: [SHAP Documentation](https://shap.readthedocs.io/en/latest/)

:gift_heart: :closed_book: [ELI5 Documentation](https://eli5.readthedocs.io/en/latest/)

## 7 Advanced Python Developer Skills

In this section, we will cover advanced Python developer skills, including package development and distribution, design patterns, Cython and C bindings, interacting with AWS and Azure, and distributed computing with PySpark.

[7.1 Package development and distribution](#71-package-development-and-distribution)\
[7.2 Design patterns](#72-design-patterns)\
[7.3 Cython and C bindings](#73-cython-and-c-bindings)\
[7.4 Interacting with AWS and Azure](#74-interacting-with-aws-and-azure)\
[7.5 Distributed computing with PySpark](#75-distributed-computing-with-pyspark)

### 7.1 Package development and distribution

:gift_heart: :closed_book: [How to Publish an Open-Source Python Package to PyPI](https://realpython.com/pypi-publish-python-package/)

:gift_heart: :movie_camera: [Publishing (Perfect) Python Packages on PyPi](https://www.youtube.com/watch?v=GIF3LaRqgXo)

:gift_heart: :closed_book: [Poetry Documentation](https://python-poetry.org/docs/)

### 7.2 Design patterns

Design patterns are general solutions to common problems in software design.

:gift_heart: :closed_book: [Design Patterns in Python](https://refactoring.guru/design-patterns/python)

### 7.3 Cython

Cython is a superset of Python that allows you to write Python code that is compiled into C. Cython is used to write Python code that is fast enough to be used in production.

:gift_heart: :closed_book: [Cython Tutorial](https://cython.readthedocs.io/en/latest/src/tutorial/cython_tutorial.html)

:gift_heart: :movie_camera: [Speed Up Your Code With Cython](https://www.youtube.com/watch?v=Ic1oE6SEOBs)

### 7.4 Interacting with AWS and Azure

Python has a number of libraries for interacting with AWS and Azure, including boto3 and Azure SDKs.

:gift_heart: :closed_book: [Python, Boto3, and AWS S3: Demystified](https://realpython.com/python-boto3-aws-s3/)

:gift_heart: :closed_book: [Use the Azure libraries (SDK) for Python](https://learn.microsoft.com/en-us/azure/developer/python/sdk/azure-sdk-overview)

### 7.5 Distributed computing with PySpark

PySpark is a Python library for distributed computing. PySpark is used to write Python code that is executed in a distributed environment.

:moneybag: :closed_book: [Advanced Analytics with PySpark](https://www.amazon.co.uk/Advanced-Analytics-PySpark-Patterns-Learning/dp/1098103653)

:gift_heart: :movie_camera: [PySpark Tutorial](https://www.youtube.com/watch?v=_C8kWso4ne4)

## 8 Advanced Biomedical Python Programming

Python is becoming popular for bioinformatics and biomedical data analysis, especially with the rise of multi-omics technologies. In this section, we will cover advanced Python skills for bioinformatics and biomedical data analysis, including survival analysis, single cell analysis, and discrete event simulation.

[8.1 Survival analysis with lifelines](#81-survival-analysis-with-lifelines)\
[8.2 BioPython](#82-biopython)\
[8.3 Nextflow](#83-nextflow)\
[8.4 Single cell analysis with ScanPy](#84-single-cell-analysis-with-scanpy)\
[8.5 Cytometry data analysis with CytoPy](#85-cytometry-data-analysis-with-cytopy)\
[8.6 Discrete event simulation with SimPy](#86-discrete-event-simulation-with-simpy)

### 8.1 Survival analysis with lifelines

Survival analysis is a class of statistical models that are used to model the time until an event occurs. Survival analysis is used in a wide range of applications, including clinical trials, epidemiology, and reliability engineering.

:gift_heart: :closed_book: [Survival Analysis with lifelines](https://lifelines.readthedocs.io/en/latest/Survival%20Analysis%20intro.html)

### 8.2 BioPython

BioPython is a library for computational molecular biology with a focus on bioinformatics and sequence analysis.

:gift_heart: :closed_book: [Biopython Tutorial](https://biopython.org/DIST/docs/tutorial/Tutorial.html)

:gift_heart: :movie_camera: [Bioinformatics with Biopython - Full Course](https://www.youtube.com/watch?v=ocA2IMe7dpA)

### 8.3 Nextflow

Nextflow is a workflow management system for computational biology. Nextflow is used to write pipelines for bioinformatics and biomedical data analysis.

:gift_heart: :closed_book: [Nextflow Documentation](https://www.nextflow.io/docs/latest/index.html)

:gift_heart: :movie_camera: [Nextflow Training Workshop](https://www.youtube.com/playlist?list=PLPZ8WHdZGxmUVZRUfua8CsjuhjZ96t62R)

### 8.4 Single cell analysis with ScanPy

ScanPy is a Python library for single cell analysis for technologies such as single cell RNA-seq and single cell ATAC-seq.

:gift_heart: :closed_book: [ScanPy Tutorial](https://scanpy-tutorials.readthedocs.io/en/latest/)

:gift_heart: :movie_camera: [Single Cell Analysis with ScanPy](https://www.youtube.com/playlist?list=PL4rcQcNPLZxWQQH7LlRBMkAo5NWuHX1e3)

:gift_heart: :movie_camera: :computer: [Machine Learning for Single Cell Analysis](https://www.krishnaswamylab.org/workshop)

### 8.5 Cytometry data analysis with CytoPy

CytoPy is a Python library for cytometry data analysis.

:gift_heart: :closed_book: [CytoPy Tutorials](https://github.com/burtonrj/CytoPyManuscript)

### 8.6 Discrete event simulation with SimPy

SimPy is a Python library for discrete event simulation. Discrete event simulation is used to model the behaviour of complex systems.

:gift_heart: :closed_book: [SimPy Documentation](https://simpy.readthedocs.io/en/latest/)

:gift_heart: :movie_camera: [Running simulations in Python](https://www.youtube.com/watch?v=8SLk_uRRcgc)

:gift_heart: :movie_camera: [Launching a new warehouse with SimPy at Rent the Runway](https://www.youtube.com/watch?v=693UiPq6mII)