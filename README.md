[![Python application test with Github Actions](https://github.com/nogibjj/DETemplatePy/actions/workflows/main.yml/badge.svg)](https://github.com/nogibjj/DETemplatePy/actions/workflows/main.yml)

## Python template for Data Engineering

This is a python template repository doing the following:

1. **Set up enviroment for development**:
  <br>a. .devcontainer: contains devcontainer (used CodeSpace defaut python default), setting up the environment for development.
  <br>b. .gitignore: specified information to ignore (used GitHub default)
  <br>c. requirements.txt: list required packages for the project.

2. **Specify GitHub Actions and Timing**
  <br>d. Makefile: when pushed/ pulled to main branch, install packages, then lint, format and test python files in the branch.

3. **Provide example python function and test functions**
   e. main.py: contains main functions.
   f. test_main.py: contains test functions for main.

4. **Provide an overview of the template**
   <br>g. README.md: THIS FILE, explaining the purpose of the directory.
