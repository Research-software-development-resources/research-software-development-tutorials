Command line terminal + text editor
===================================
The most basic IDE is the combination of a text editor (allowing you to edit your source code) and a command line terminal (allowing you to execute commands to build and run your source code).

.. note::
   It is recommend to use a IDE for software development as they provide tools such as graphical debuggers to help improve efficiency of the software development process.

Common editors include Gedit, Vim on Linux, Text editor on Mac, and Notepad++ on Windows.

.. note::
   It is recommend to use an editor such as Notepad++ that allows you to choose text file line-ending deliminators on Windows. See the following resource for more information (`Converting from Windows-style to UNIX-style line endings <https://support.nesi.org.nz/hc/en-gb/articles/218032857-Converting-from-Windows-style-to-UNIX-style-line-endings>`_).

PyCharm
=======
`PyCharm <https://www.jetbrains.com/pycharm/>`_ is an IDE specifically for Python programming. It is developed by the Czech company JetBrains. It provides code analysis, a graphical debugger, an integrated unit tester, integration with version control systems, ability to profile code (professional version required), and remotely debug your projects (professional version required).

  .. figure:: https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/PyCharm_2021.1_Community_Edition_screenshot.png/1280px-PyCharm_2021.1_Community_Edition_screenshot.png
    :width: 700
    :align: center
    :figclass: align-center

    PyCharm 2021.1 IDE.

See the `PyCharm documentation <https://www.jetbrains.com/help/pycharm/quick-start-guide.html>`_ for installation instructions and how to get started.

.. note::
   Check the `JetBrains Academic Licensing page <https://www.jetbrains.com/community/education/#students>`_ to see if you qualify for a free educational license. This will provide free access to the Professional edition of PyCharm.

PyCharm tips
------------
- PyCharm has inbuilt PEP8 style checking. Selecting the code of interest and clicking the |br|:guilabel:`Code` → :guilabel:`Reformat code` Pycharm menu option will automatically format your code according to PEP8.

- Enable automatic saving of open files:

  - :guilabel:`File` → :guilabel:`Settings` → :guilabel:`Appearance & Behavior` → :guilabel:`System Settings` →
    :guilabel:`Synchronization` → |br|:guilabel:`☑ Save files automatically if application is idle for 5 sec.`
  - :guilabel:`File` → :guilabel:`Settings` → :guilabel:`Editor` → :guilabel:`General` → :guilabel:`Editor tabs` → :guilabel:`☑ Mark modified (*)`

Visual Studio Code
==================
`Visual Studio Code <https://code.visualstudio.com/>`_ combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle. It provides comprehensive code editing, navigation, and understanding support along with lightweight debugging, a rich extensibility model, and lightweight integration with existing tools.

  .. figure:: https://user-images.githubusercontent.com/1487073/58344409-70473b80-7e0a-11e9-8570-b2efc6f8fa44.png
    :width: 700
    :align: center
    :figclass: align-center

    Visual Studio Code IDE.

See the `Visual Studio Code documentation <https://code.visualstudio.com/docs>`_ for installation instructions and how to get started.

JupyterLab
==========
JupyterLab is a web-based interactive development environment for Jupyter notebooks, code, and data. JupyterLab is flexible: configure and arrange the user interface to support a wide range of workflows in data science, scientific computing, and machine learning. JupyterLab is extensible and modular: write plugins that add new components and integrate with existing ones.

  .. figure:: https://jupyter.org/assets/homepage/labpreview.webp
    :width: 700
    :align: center
    :figclass: align-center

    JupyterLab IDE.

See the `JupyterLab documentation <https://jupyterlab.readthedocs.io/en/latest/>`_ for installation instructions and how to get started.

JupyterLab tips
---------------

- `JupyterLab tips and tricks <https://towardsdatascience.com/jupyter-notebooks-tips-and-tricks-4e995e7b1fd0>`_.

Google Colab
============
`Google Colaboratory <https://colab.research.google.com/>`_ or “Colab” for short is a **free** Python Jupyter notebook environment from Google Research that runs entirely in the cloud. There is no setup process. The notebooks that you create can be simultaneously edited by you and your collaborators — similar to how you can collaboratively edit documents in Google Docs. It is especially well suited to machine learning, data analysis and education and **provides free access to computing resources including GPUs (Nvidia K80s, T4s, P4s and P100s)**.

  .. figure:: /_static/development_environments/google_colab_ide.png
    :width: 700
    :align: center
    :figclass: align-center

    Google Colab IDE.

Navigate to https://colab.research.google.com to get started. See the `Colab FAQ <https://research.google.com/colaboratory/faq.html>`_ for more information on usage limits of the free GPUs provided by this service.

.. note::
   If your team requires you to use in-house software as part of your projects then it may not be possible to access and build that software on cloud-based IDEs.

Binder
======
The `Binder Project <https://mybinder.org/>`_ allow you to package and share interactive, reproducible environments. A Binder or "Binder-ready repository" is a code repository that contains both code and content to run, and configuration files for the environment needed to run it.

This allows you to take a code repository e.g .on Github that may contain Jupyter notebooks, and open those notebooks in an executable environment, making your code immediately reproducible by anyone, anywhere.

  .. figure:: /_static/development_environments/mybinder.png
    :width: 700
    :align: center
    :figclass: align-center

    Binder setup page.

Binderhub
---------
A BinderHub lets you launch a publicly executable version of a Binder repository. Given a URL to a repository, it generates a new URL that anyone can visit in a browser to interact with a running version of the code in that repository.

.. Add line breaks.

.. |br| raw:: html

     <br>