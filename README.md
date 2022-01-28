# Building Data Science Applications with FastAPI

This is my code repository for [Building Data Science Applications with FastAPI](https://www.packtpub.com/product/building-data-science-applications-with-fastapi/9781801079211?utm_source=github&utm_medium=repository&utm_campaign=9781801079211), published by Packt.

It contains all the code files I made while learning to develop, manage, and deploy efficient machine learning applications with Python from this amazing Book.

## Setup

To set up a similar development environment for running the applications(preferably in a Linux distro), follow the steps below:

- **Installing a Python distribution using `pyenv`**

  Most Unix environments already has Python bundled along with other packages. Check the version of the currently installed Python using:

  ```
    $ python3 --version
  ```

  The output will vary depending on your system. If you don't have python or `pyenv`, please follow the instructions present in their Official Website to install it: [PyEnv](https://github.com/pyenv/pyenv#installation)

  - Installing a Python 3.7
    Even though FastAPI is compatible with Python 3.6 and later, we'll use Python 3.7.
    ```bash
    $ pyenv install 3.7.10
    ```
  - Set the default python version
    ```bash
    $ pyenv global 3.7.10
    ```
  - Check your installation
    ```bash
    $ python --version
    Python 3.7.10
    ```

- **Creating a Python virtual environment**

  - Create a directory that will contain your project:
    ```bash
    $ mkdir fastapi-data-science
    $ cd fastapi-data-science
    ```
  - Create a virtual env
    ```bash
    $ python -m venv venv
    ```
  - Activate the environment
    ```bash
    $ source venv/bin/activate
    ```

- **Installing Python packages with pip**

  - Install FastAPI and Uvicorn
    ```bash
    $ pip install fastapi 'uvicorn[standard]'
    ```
  - Chcek your installation
    To make sure the installation worked, you can open a Python interactive shell and try to import the FastAPI package:

    ```bash
    $ python
    >>> from fastapi import FastAPI
    ```

    If it passes without any errors, congratulations, FastAPI is installed and ready to use!

- **Installing the HTTPie command-line utility**
  We will use HTTPie, a command-line tool aimed at making HTTP requests with an intuitive syntax, JSON support, and syntax highlighting. It's available to install from most package managers:

  - macOS:

  ```bash
  $ brew install httpie
  ```

  - Ubuntu and its like:

  ```bash
  $ sudo apt-get update; sudo apt-get install httpie
  ```

Following the above steps will let you have all the tools and setup required to confidently run the examples and applications of this repository and all your future Python projects.
