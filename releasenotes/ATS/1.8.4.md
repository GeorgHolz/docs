---
title: "Mendix ATS 1.8.4 Release Notes"
space: "ATS (Application Test Suite)"
category: "Release Notes"
---

Date: February 1, 2017

## New Action
* Added a new action to click a x-y-coordinate within the browser window or a certain UI element. Visit the [Reference guide](/selenium-actions/click-coordinates) for more details.

## Improvements
* Improved the sorting of scheduler items. The items are now shown in order of next execution time. The top item is the one that is executed next.
* Added a new warning icon on the Monitoring/Results page that indicates a failure in the tear down procedure of a test.

## Fixes
* Fixed a bug where the dialog to link a story to a test case was not closed properly.
* If you configured a data set with more than 30 fields for your test case, only the first 30 fields could be used due to a UI bug. This has been fixed.
* A change of the project name now also updates the root folder in the repository.
* Fixed a bug, where users were able to select selenium configurations and applications from other projects in the test run configuration.
* Fixed a bug, where the chart on the project selection page did not show the same results as the chart on the project dashboard.     
* The "Show Log" link on the project dashboard is now hidden for tests that have never been executed.
* Fixed a bug, where test cases were added in the wrong order to an empty test suite. 
