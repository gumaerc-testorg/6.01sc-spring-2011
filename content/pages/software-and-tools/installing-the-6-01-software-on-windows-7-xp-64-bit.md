---
content_type: page
parent_title: Software and Tools
parent_uid: 7ff627d1-c807-cddd-75e0-3d0659f60269
title: Installing the 6.01 Software on Windows 7/XP (64-bit)
uid: 59ebc664-3e5a-4fc7-b4b5-1e2dc2557012
---

« [Previous]({{< baseurl >}}/pages/software-and-tools)

A. Download the Software
------------------------

Download the following files to your desktop:

*   The appropriate Windows installer for [Python 2.6.x (64-bit)](http://www.python.org/ftp/python/2.6.6/python-2.6.6.amd64.msi)
*   [Unofficial numpy for Python 2.6.x (64-bit)](http://www.lfd.uci.edu/~gohlke/pythonlibs/#numpy) (select **numpy-unoptimized-1.6.1.win-amd64-py2.6.exe**; make sure you get the py2.6 part correct.) 64-bit numpy is not officially supported, however, _Unofficial_ binaries exist at the above website courtesy of Christoph Gohlke (UC Irvine).
*   [Soar, CMax, and lib601 installer (64-bit)]({{< baseurl >}}/resources/lib601-3-500-win-amd64). (**Win7 Must Run as Administrator**). Right-click on installer and choose "Run as Administrator".

B. Install the Python Language
------------------------------

Double click on the Python installer to begin the Python installation process.

1.  In reply to the options: install the software for all users, use the default directory (C:\\Python26\\) and in general just click "next" to accept the defaults.
2.  Wait for the installation to finish and click "finish". Note that installing Python will also automatically install idle.

C. Check that Python Works
--------------------------

1.  Find Python 2.6 in your menu of programs and run "idle". This should produce a window that says "Python 2.6.x ..." and ends with a prompt (>>>)
2.  At the prompt, type  
    \>>> 2\*\*10  
    and press Enter. The result should be 210, or 1024. Try computing 21000 and verify that this works as well.
3.  If this works, you've (probably) successfully installed Python. Exit idle by selecting exit from the file menu. Ask for help if something has gone wrong.
4.  Download [idle-n.zip]({{< baseurl >}}/resources/idle-n-2) and extract the .bat file. This file will let you start idle with the "-n" flag that allows it to generate plots properly.

D. Install Numpy
----------------

Double-click on the numpy installer on your desktop (**numpy-1.5.1-win32-superpack-python2.6.exe** ). Accept the defaults (i.e., just click "next"), wait for the installation to complete, and click "finish".

**E. Install the 6.01 Software: _lib601_, _soar_, and _CMax_**
--------------------------------------------------------------

The links to download the lib601, soar, and CMax installer are at the top of this page

Double-click on the **soar** installer on your desktop (**lib601-3-500.win-amd64.exe**). Accept the defaults (i.e., just click "next"), wait for the installation to complete, and click "finish".

**If you have Windows Vista or Windows 7, do NOT simply double-click to run these installers! You MUST right-click on the installers and choose "Run as Administrator"; otherwise you will see error messages during the installation, and soar will not appear on your Start menu.**

F. Try it!
----------

To start soar, simply run **soar** from **Start->Programs**. To start CMax, run **CMax** from **Start->Programs**.

You can now remove the installer files that you downloaded to your desktop.

If you just want to write Python scripts, without needing to use soar, you can open up idle directly. Go to Start | All Programs | Python 2.6 | idle (Python GUI). This will bring up the idle editor that you use during lab.

« [Previous]({{< baseurl >}}/pages/software-and-tools)