---
title: "Mendix ATS 1.8.4 Release Notes"
space: "ATS (Application Test Suite)"
category: "Release Notes"
---

Date: February 1, 2017

## New Selenium Action
* Added new click coordinates action, which enables ATS to click any point in the application, defined by x-y-coordinates. For more informations visit [Click Coordinates Reference page](/selenium-actions/click-coordinates).

## Improvements
* Changed the sorting of active and inactive scheduled tests. For active scheduled tests, the tests which will be executed next, will now be set on top of the list. For inactive scheduled tests, the test which hasn't been scheduled for the longest time, is set on first position.
* The tear down failure warning text on the Monitoring/Result page has been replaced by a warning icon. The original text is still displayed as tooltip for the icon.

## Fixes
* Fixed a bug, where an endless loop of dialogs was displayed, if a user tried to link a story to a test case.
* Fixed a bug, where not all of the possible test data fields were displayed inside a test case, if the master data set had more than 30 field entries.
* The name of the root folder in the repository will now change, if the project has been renamed.
* Fixed a bug, where users were able to select selenium configurations and applications from other projects in the test run configuration.
* Fixed a bug, where the chart on the project selection page did not show the same results as the chart on the project dashboard.     
* The "Show Log" link is now only displayed, if the test has execution logs to show.
* Fixed a bug, where test cases have been set in wrong order, if the user tried to add them to a newly created test suite. 
