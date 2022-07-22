---
content_type: page
description: This section contains instructions for installing the 6.01 software on
  MacOS X.
learning_resource_types: []
ocw_type: CourseSection
parent_title: Software and Tools
parent_type: CourseSection
parent_uid: 7ff627d1-c807-cddd-75e0-3d0659f60269
title: Installing the 6.01 Software on Macs
uid: aa4c5c32-a0fc-63d4-cc8b-e09590cdc1cb
---

« {{% resource_link 7ff627d1-c807-cddd-75e0-3d0659f60269 "Previous" %}}

Note: Python is pre-installed on MacOS X, but it is often an older version. For this class we will be using Python 2.6.x.

*   First open a Terminal window (from the Applications/Utilities folder). Type python and see whether it says Python 2.6.x. If not, follow the Install Python instructions.
*   If you have Python 2.6, type import numpy. If that fails, then follow the Installing Numpy instructions.

A. Install Python
-----------------

You can get a Python 2.6.x DMG installer (Mac Installer disk image) here: [Python 2.6.6](http://www.python.org/ftp/python/2.6.6/python-2.6.6-macosx10.3.dmg)

B. Installing Numpy
-------------------

You should also install numpy, a package that will be used in later labs. This file is available here: [numpy 1.6](http://sourceforge.net/projects/numpy/files/NumPy/1.6.1/numpy-1.6.1-py2.6-python.org-macosx10.3.dmg/download)

C. Installing 6.01 Libraries and Soar
-------------------------------------

Download the {{% resource_link afbbebcc-ae39-bfa4-2f9d-071e9ed10453 "6.01 modules" %}} to a convenient directory (e.g., ~/Desktop). Open a Terminal window, navigate to the Desktop directory by typing a command of the form

\> cd ~/Desktop

Usually the download process will open and expand this file into a directory. If you don't see a directory lib601-3-500, then unpack the modules by typing

\> tar xvzf lib601-3-500.tar.gz

Then change directories and do the installation with

\> cd lib601-3-500  
\> sudo python setup.py install

You can now delete all of the files created by this operation (i.e., ~/Desktop/lib601-3-500.tar.gz and its associated directory tree). You should now be able to run soar by typing soar at a terminal command prompt.

« {{% resource_link 7ff627d1-c807-cddd-75e0-3d0659f60269 "Previous" %}}