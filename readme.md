task4AIEA: Introduction to Prolog and Python Integration 🐍🧠
A repository demonstrating the fundamentals of Prolog (a declarative, logic programming language) and how to seamlessly integrate it with a Python application. This project is likely part of a task or assignment focused on Artificial Intelligence and Expert Systems (AIEA).

Table of Contents
Project Description






Project Description
This project serves as an introductory guide to logic programming using Prolog and showcases a practical example of integrating a Prolog-based knowledge base into a standard Python workflow.

The core idea is to leverage Prolog for tasks requiring logical inference, rule-based decision-making, or knowledge representation, while using Python for the main application logic, data handling, and user interface.

Key learning points in this repository include:

Defining facts and rules in a Prolog knowledge base (.pl file).

Using a Python library to query the Prolog engine.

Passing variables and retrieving solutions from the Prolog engine back into Python.

Files Overview
Prerequisites
To run this project, you will need:

SWI-Prolog: The Prolog interpreter is required for the integration library to function.

Python 3.x: The main language for the application code.

Installation
1. Install SWI-Prolog
Ensure you have SWI-Prolog installed on your system and that its executables are accessible from your system's PATH.


2. Set up Python Environment
Clone the repository and install the necessary Python dependencies.

Note: The primary Python library for Prolog integration is likely pyswip, which requires a correctly installed SWI-Prolog. If you encounter issues, please check the pyswip installation instructions for your specific OS.

Usage
To run the demonstration of Prolog-Python integration, execute the main Python script:

This script will:

Initialize the Prolog engine.

Consult (load) the kb.pl knowledge base.

Execute pre-defined queries against the knowledge base.

Print the results of the logical inferences performed by Prolog.

Example Prolog Query (Hypothetical)
You can inspect the python_prolog_demo.py file to see how queries are constructed, for example:

You can also modify the kb.pl file to add your own facts and rules and then update the python_prolog_demo.py script to query your new knowledge.

License
This project is open source and available under the MIT License.
