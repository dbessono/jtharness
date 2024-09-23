<!---
  $Id$

  Copyright (c) 2001, 2024, Oracle and/or its affiliates. All rights reserved.
  DO NOT ALTER OR REMOVE COPYRIGHT NOTICES OR THIS FILE HEADER.

  This code is free software; you can redistribute it and/or modify it
  under the terms of the GNU General Public License version 2 only, as
  published by the Free Software Foundation.  Oracle designates this
  particular file as subject to the "Classpath" exception as provided
  by Oracle in the LICENSE file that accompanied this code.

  This code is distributed in the hope that it will be useful, but WITHOUT
  ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or
  FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License
  version 2 for more details (a copy is included in the LICENSE file that
  accompanied this code).

  You should have received a copy of the GNU General Public License version
  2 along with this work; if not, write to the Free Software Foundation,
  Inc., 51 Franklin St, Fifth Floor, Boston, MA 02110-1301 USA.

  Please contact Oracle, 500 Oracle Parkway, Redwood Shores, CA 94065 USA
  or visit www.oracle.com if you need additional information or have any
  questions.
-->

# View Menu

The View menu contains menu items that display information about a test run. The following table
describes the items in the View menu.

+-------------------------------------------------+-------------------------------------------------+
| Menu Item                                       | Description                                     |
+=================================================+=================================================+
| Configuration **\>** Show Checklist (Optional)  | Enabled by the harness when your test suite     |
|                                                 | supports the configuration checklist. Displays  |
|                                                 | a checklist of tasks to be performed before     |
|                                                 | running tests. See [Displaying the              |
|                                                 | Configuration                                   |
|                                                 | Checklist](../confEdit/checklist.html) for      |
|                                                 | detailed information.                           |
+-------------------------------------------------+-------------------------------------------------+
| Configuration **\>** Show Exclude List          | Opens an Exclude List dialog box that contains  |
| (Optional)                                      | the exclude list used to run the test suite.    |
|                                                 | You can use the Exclude List dialog box to      |
|                                                 | review but not edit the contents of the exclude |
|                                                 | list. If you use multiple exclude lists, the    |
|                                                 | Exclude List dialog box displays the merged set |
|                                                 | of exclude lists.                               |
|                                                 |                                                 |
|                                                 | You must use the configuration editor window to |
|                                                 | add or remove exclude lists. See [Using Exclude |
|                                                 | Lists](../confEdit/excludeList.html) for        |
|                                                 | detailed information.                           |
|                                                 |                                                 |
|                                                 | See [Viewing Exclude List                       |
|                                                 | Contents](../excl/dialog.html) for detailed     |
|                                                 | information about viewing the contents of the   |
|                                                 | exclude list.                                   |
+-------------------------------------------------+-------------------------------------------------+
| Configuration **\>** Show Test Environment      | Opens a Test Environment browser that displays  |
|                                                 | the configuration values used when running the  |
|                                                 | test suite.                                     |
|                                                 |                                                 |
|                                                 | You can browse but not change values in the     |
|                                                 | Test Environment browser. You must use the      |
|                                                 | configuration editor to change the values. See  |
|                                                 | [Editing a                                      |
|                                                 | Con                                             |
|                                                 | figuration](../confEdit/editConfiguration.html) |
|                                                 | for detailed information.                       |
|                                                 |                                                 |
|                                                 | See [Viewing Configuration                      |
|                                                 | Values](../env/dialog.html) for detailed        |
|                                                 | information about viewing the contents of the   |
|                                                 | test environment.                               |
+-------------------------------------------------+-------------------------------------------------+
| Configuration **\>** Show Question Log          | Displays a log of the current configuration     |
|                                                 | interview questions and answers. See            |
|                                                 | [Displaying the Question                        |
|                                                 | Log](../confEdit/questionLog.html) for detailed |
|                                                 | information.                                    |
+-------------------------------------------------+-------------------------------------------------+
| Filters                                         | Displays the available view filters, the active |
|                                                 | filter, and enables you to modify the custom    |
|                                                 | view filter.                                    |
|                                                 |                                                 |
|                                                 | See [Using View                                 |
|                                                 | Filters](../browse/viewFilters.html) for        |
|                                                 | detailed description.                           |
+-------------------------------------------------+-------------------------------------------------+
| Properties                                      | Click the Properties menu item to display the   |
|                                                 | Test Manager Properties dialog box containing   |
|                                                 | the current settings of the Test Manager.       |
|                                                 |                                                 |
|                                                 | See [Viewing Test Manager                       |
|                                                 | Properties](../execProps/dialog.html) for       |
|                                                 | detailed information about using the Test       |
|                                                 | Manager Properties dialog box.                  |
+-------------------------------------------------+-------------------------------------------------+
| Logs                                            | Is enabled if the harness detects any log       |
|                                                 | output, otherwise it is disabled. Click the     |
|                                                 | Logs menu item to display logged output         |
|                                                 | generated by the harness for the test suite.    |
+-------------------------------------------------+-------------------------------------------------+
| Test Suite Errors                               | Enables the Test Suite Errors menu item when it |
|                                                 | detects that the test suite (not the tests in   |
|                                                 | the test suite) contains errors. Click the Test |
|                                                 | Suite Errors menu item to display a dialog box  |
|                                                 | identifying the errors detected in the test     |
|                                                 | suite.                                          |
|                                                 |                                                 |
|                                                 | See [Viewing Test Suite                         |
|                                                 | Errors](../browse/testSuiteErrors.html) for     |
|                                                 | detailed information.                           |
+-------------------------------------------------+-------------------------------------------------+
| Toolbars                                        | Is enabled if more than one toolbar is          |
|                                                 | available to the user, otherwise it is          |
|                                                 | disabled.                                       |
+-------------------------------------------------+-------------------------------------------------+

----------------------------------------------------------------------------------------------------


