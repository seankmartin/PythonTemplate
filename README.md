# PythonTemplate
Template for my Python Projects.

## How to convert to your project
1. Rename the folder `your_package` and edit `your_package/__init__.py`
2. Update `setup.py, version.txt, requirements.txt, dev_requirements.txt, LICENSE` to allow for users to install your package using `pip install .` or uploading to PyPI.
3. Update `README.md`.
4. Add the correct Makefile or batch script etc. to docs to allow for building documentation. Most likely this will use sphinx or pdoc3.
5. Add your tests to the tests folder that can be run with pytest or a similar testing framework.

Optionally, you could also setup continuous integration with CircleCI or similar, and setup git hooks.

Checkout TODO put link for a guide to getting a project like this formatted, linted, and shared on PyPI and Read the Docs.

# README Template

# Project Name
Short Description

# Installation
How to install stable version and dev version.

## Dependencies
What does installation require?

# Documentation
Where can further documentation be found?

# Contributing
Is there a guide for contributing?

# Licensing
What License is this project provided under?
