# **Django**

Django is a web framework - a set of tools dddesigned to help you guild interactve websites. In this chapter, you'll learn how to use Django.

### **Creating Virtual Environment**

To work with django, we need to set up a **virtual environment**. **A virtual environment** _is a place on your system here you can install packages an isolate them from all other Python packages_. Separating one project's libraries from other projects is beneficial and will be necessay when we deploy Learning Log to a server.

> _Virtual environments are used when workng on a Python project that uses external dependencies that you're installing with pip, to use them for your project it iss better to set up a virtual environment first._

> Python applications will often use packages and modules that don’t come as part of the standard library. Applications will sometimes need a specific version of a library, because the application may require that a particular bug has been fixed or the application may be written using an obsolete version of the library’s interface.

> This means it may not be possible for one Python installation to meet the requirements of every application. If application A needs version 1.0 of a particular module but application B needs version 2.0, then the requirements are in conflict and installing either version 1.0 or 2.0 will leave one application unable to run.

> The solution for this problem is to create a virtual environment, a self-contained directory tree that contains a Python installation for a particular version of Python, plus a number of additional packages.

To create a new directory for your poject called learning_log, switch to that directory in a terminal, and enter the following code to create a virtual environment:

```
python -m venv ll_env
```
This system command will create a folder called ll_env in the folder you console is in and will install all the files necessary for setting up a python virtual environment.

