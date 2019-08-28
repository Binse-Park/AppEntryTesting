# AppEntryTesting

Introduction
============

 This project provides a toolkit to be logging systrace or ftrace automatically during app execution time. This project's goal is to help android developers to measure the app launched time and to be remain logging for analysis during app launched time.
 This project use many libraries in the LISA project of arm. So This should be installed with LISA library.

Motivations
===========

The main goals of App Entry Tester are:
-  Get the systrace or ftrace automatically during app execution time. 
-  Gather the app entry time and calculating statistics.
-  Calculate the variance of app launch time.
-  Store some testing scenarios.
-  Gather Scheduling infor.


Install
=======

- [**Install of lisa project**](https://lisa-linux-integrated-system-analysis.readthedocs.io/en/master/setup.html)
- copy aapt-arm-pie file to the path of lisa project.
- open ipynb to use jupyternotebook in lisa project.


External Links
==============

- Linux Integrated System Analysis (LISA) & Friends [Slides](http://events.linuxfoundation.org/sites/events/files/slides/ELC16_LISA_20160326.pdf) and [Video](https://www.youtube.com/watch?v=yXZzzUEngiU)
  Note: the LISA classes referred by the slides are outdated, but all the other concepts and the overall architecture stays the same.
- Some insights on what it takes to have reliable tests: [Video](https://www.youtube.com/watch?v=I_MZ9XS3_zc&t=7s)
