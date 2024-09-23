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

[]{#allTests}[]{#allTests}

# All Tests View Filter

When you select the All Tests view filter, the Test Manager immediately displays current totals in
the Summary pane and status icons in the test tree for all folders and tests, regardless of the
values set in the configuration. This is an unfiltered view of the complete work directory contents.

The harness only overwrites the previous results for tests when they are rerun. The All Tests filter
displays the last run status for all tests in the work directory, including the tests that were
excluded from the current test run.

If you are using the All Tests view filter and begin a test run, the harness displays an advisory
dialog box. Using the All Test view filter will display the results of all tests in a test suite
regardless of whether or not they are included in the test run.

You can choose to disable the dialog box by setting preferences, by choosing a different view
filter, or by using the check box in the dialog to stop the dialog from being displayed in the
future.

The following examples provide descriptions of the use of the All Tests view filter.

-   **Example 1 -** A test run had failed tests and you want to rerun only the failed tests. See
    [Specifying Prior Status](../confEdit/status.html) for a detailed description of setting the
    prior status value. The Test Tree and the Summary pane do not change.

> When you use the All Tests view filter, the Test Manager displays all totals in the Summary pane
> and status icons in the test tree regardless of the values set in the current configuration.

-   **Example 2 -** A test run had failed tests and you want to use an Exclude List in the next run
    that excludes the failed tests from the test run. See [Using Exclude
    Lists](../confEdit/excludeList.html) for a detailed description of specifying an exclude list.
    The Test Tree and the Summary pane do not change.

> When you repeat the test run, the Test Manager displays current status icons in the test tree and
> totals in the Summary pane for every test in the work directory, including results for any tests
> excluded from the current test run.

----------------------------------------------------------------------------------------------------


