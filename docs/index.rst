.. Calculator Documentation documentation master file, created by
   sphinx-quickstart on Wed Jun 18 14:38:25 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Calculator Documentation
=======================

Welcome to the Calculator library documentation!

This Python library provides a simple but powerful Calculator class with basic mathematical operations.

Features
--------

* **Addition**: Add two numbers
* **Subtraction**: Subtract two numbers
* **Multiplication**: Multiply two numbers
* **Division**: Divide two numbers (with zero division protection)
* **Square Root**: Calculate square root (with negative number protection)

Quick Start
-----------

.. code-block:: python

   from calculator import Calculator

   calc = Calculator()
   result = calc.add(5, 3)  # Result: 8
   sqrt_result = calc.sqrt(16)  # Result: 4.0

Installation
-----------

The project uses a virtual environment. Activate it and install dependencies:

.. code-block:: bash

   source venv/bin/activate
   pip install -r requirements.txt

Running Tests
------------

.. code-block:: bash

   python -m unittest test_calculator.py -v

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   api
