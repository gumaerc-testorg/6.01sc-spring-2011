---
content_type: page
description: This section contains instructions for installing the 6.01 software on
  GNU/Linux.
learning_resource_types: []
ocw_type: CourseSection
parent_title: Software and Tools
parent_type: CourseSection
parent_uid: 7ff627d1-c807-cddd-75e0-3d0659f60269
title: Installing the 6.01 Software on GNU/Linux
uid: f1bdaacf-7071-5579-04da-a1ee567058ad
---

« {{% resource_link 7ff627d1-c807-cddd-75e0-3d0659f60269 "Previous" %}}

This course makes use of Athena, MIT's UNIX-based computing environment. OCW does not provide access to this environment.

The laptops in the lab use Athena software that is built on [Ubuntu](http://www.ubuntu.com/) version 10.4. We expect the 6.01 software to work on other distributions, but other distributions have not been tested.

A. Get Python, TK, and Numpy
----------------------------

Make sure that your machine is running Python 2.6.6. You can use either your distribution's package manager (apt, synaptic, yum, etc.) to download and install the python package (make sure it's version 2.6.6), or you can compile Python from [source](http://www.python.org/download/releases/2.6.6/).

You should also install tkinter, a Python package that is necessary for running soar. Installation will be dependent on your distribution. For recent Debian-based distros, there is a package (python-tk) that you can install with apt. On other distributions, you should be able to find an appropriate package to install as well.

You will also need to install numpy, a Python package, for some of the assignments. Again, installation will be dependent on your distribution. For recent Debian-based distros, there is a package (python-numpy) that you can install with apt. For other distributions, you can either compile from [source](http://sourceforge.net/projects/numpy/files/) or find the appropriate package for your distribution.

B. Get Idle or Emacs
--------------------

You'll also need Idle or Emacs (and it won't hurt to have both). If your Python distribution did not come with Idle (type "idle" at a command line to see if it's defined), there's a package (idle) that you can install with apt. Since you'll be starting Idle a lot, you'll find it convenient to create a launcher for and place it in a menu or on the menu bar.

C. Get 6.01 Software
--------------------

Download the {{% resource_link afbbebcc-ae39-bfa4-2f9d-071e9ed10453 "6.01 modules" %}} to a convenient directory (e.g., ~/Desktop). Open a terminal window, navigate to the Desktop directory by typing a command of the form

\> cd ~/Desktop

Then unpack the modules by typing

\> tar xvzf lib601-3-500.tar.gz

Then change directories and do the installation with

\> cd lib601-3-500  
\> sudo python setup.py install

You can now delete all of the files created by this operation (i.e., ~/Desktop/lib601-3-500.tar.gz and its associated directory tree). You should now be able to use the lib601 files from Python and to run soar by typing soar at a terminal command prompt.

« {{% resource_link 7ff627d1-c807-cddd-75e0-3d0659f60269 "Previous" %}}