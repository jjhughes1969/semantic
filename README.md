# semantic
a simple NLP similarity exercise

## Table of Contents

1. Overview of the Project
2. Installing and Running the Project
3. Usage of the Project
4. Credits

### Overview of the Project

This project was written as part of the HyperionDev University of Edinburgh Online Software Engineering Bootcamp, to demonstrate and practice the use of basic NLP similarity concepts using SpaCy in Python.

### Installing and Running the Project

The project was written in Python 3.11.0 using the Visual Studio Code IDE version 1.75.0.  You will require Python 3 to run this project in your IDE.

There is a Dockerfile attached which allows you to complile and run this on any machine; the Dockerfile uses Python 3.7, as I have found this gives the quickest results creating a Docker container and image with SpaCy.  Note there is no requirements.txt file, as the Dockerfile itself contains the instructions for installing SpaCy and the relevant language models.  Note that both en_core_web_sm and en_core_web_md are loaded as part of the exercise compares the output of the two models.

### Usage of the Project

The project requires no user input and can be run in an IDE or Console.

### Credits

The Python code was written by Jonathan Hughes, based on materials and instructions provided by HyperionDev.
The HyperionDev website is at https://www.hyperiondev.com
