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

[]{#testManager.preferences}

# Test Manager Preferences

To change the Test Manager preferences, select File \> Preferences \> Test Manager.

-   [Test Manager Preferences](#testManager.preferences)
-   [Configuration Editor](#testManager.confeditor)
-   [Reporting](#testManager.reporting)

The following preferences are set when the Test Manager folder is selected as follows:

![Test Manager preferences dialog
box](../../images/testManagerPreferences.gif){longdesc="testManager.html"}

-   Tool Bar: Check Displayed to see the toolbar. If you enable or disable this option you must
    restart JavaTest to see the change.
    ![standard UI toolbar](../../images/uiToolbar.gif){longdesc="standard UI toolbar"}
-   View Filters: Enables a warning message that is displayed if the [All Tests
    filter](../browse/viewFilters.html) is selected for a test run.
-   []{#testExecOrder} Test Execution:
    -   Execution from tree popup includes configuration Test to Run setting:
    -   Disable sort of Tests to Run when specified from input file: This allows you to set the test
        execution order. Traditionally tests are run in the order they appear in the main test tree.
        This order is generally determined by the test suite architect. By selecting this option,
        the order execution will follow that in the input file for the Tests to Run section in the
        configuration. That is, the tests will be executed in the order they appear in that file,
        rather than being sorted and then executed. The default state of this checkbox is unchecked.
        See
-   Test Run Messages: Wrap Test Output in the [Test Run Messages
    Pane](../../default/browse/messagesTab.html#messagesTab).

[]{#testManager.confeditor}

## Configuration Editor

Check the More Info box to view the More Info pane in the configuration editor. Same as choosing
View \> More Info, except the preference will remain in future sessions.

![More Info display
preference](../../images/JT4testManagerReporting.gif){longdesc="More Info display preference"}

[]{#testManager.reporting}

## Reporting

Set the bug prefix URL for KFL reports.

![bug prefix URL field](../../images/JT4testManagerPrefs.gif){longdesc="bug prefix URL field"}

----------------------------------------------------------------------------------------------------


