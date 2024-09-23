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

[]{#running}

# Running Tests

In the Test Manager, you can use the Run Tests menu or the toolbar button to start a test run of the
tests specified in your current configuration. See [Test Manager Tool](../ui/window.html) for a
description of the Run Tests menu and the tool bar buttons. See [Configuring a Test
Run](../confEdit/overview.html) for a description of how to use the Configuration Editor to specify
configuration information used to run tests.

You can also use the test tree pop-up menu to start a test run of one or more tests selected from
the test tree. See [Test Tree Pop-up Menu](../ui/popupmenu.html) for a description of how to use the
test tree pop-up menu to run individual tests in a test tree.

![The following text is a note](../../images/hg_note.gif){longdesc="running.html"}\
If you do not want to use the Test Manager to run tests, you can use the command line. See
[Command-Line Summary](../command/commandLine.html) in the *Command-Line Interface User\'s Guide*
for information about running tests from the command line.

The harness saves all test results after running tests but does not automatically generate reports
of test results. You must generate test reports from the Test Manager or from the command line. See
[Generating and Viewing Reports](../report/usingReports.html) for detailed information about
reports.

If you use the All Tests view filter and begin a test run, the harness displays an advisory dialog
box. Using the All Test view filter displays the results of all tests in a test suite regardless of
whether or not they are included in the test run.

You can choose to disable the dialog box by setting harness Preferences, by choosing a different
view filter, or by using the check box in the dialog to stop the dialog from being displayed in the
future.

This chapter contains the following topics, presented in a sequence that you can use when running
tests:

-   [**Starting a Test Run**](starting.html) - Describes how to use the Test Manager to start a test
    run using the current configuration.
-   [**Monitoring a Test Run**](monitoring.html) - Describes how to use the Test Manager (including
    the use of the Log Viewer) to monitor a test run.
-   [**Monitoring Agents**](../ui/agentMonitor.html) - Describes how to use the Agent Monitor tool
    to monitor agent activity during a test run.
-   [**Stopping a Test Run**](stopping.html) - Describes how to use the Test Manager to stop a test
    run.
-   [**Troubleshooting a Test Run**](troubleshooting.html) - Describes how to use the Test Manager
    to troubleshoot a test run.

----------------------------------------------------------------------------------------------------

