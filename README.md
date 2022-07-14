# Loan Qualifier App

This is a Python command-line interface application that allows users to determine qualifying loans from lenders. By utilizing loan criteria from other loan providers, the application runs the criteria against lendees to evaluate their eligibility for a loan. Returns a list of qualifying loans (healthy vs unhealthy loans).

## Technologies

This project utilizes Python 3.7 with the following packages:

* [Fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [Questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

* [PyTest](https://docs.pytest.org/en/stable/) - For basic assertion testing of financial calculators and filters, and filio.

## Installation Guide

Before running the application, first install the following dependencies.

```python
  pip install fire
  pip install questionary
  pip install pytest
```

## Examples

Launching the application will direct you to the following prompts.

![Loan Qualifier Prompts](../Images/example_1.PNG)

## 
