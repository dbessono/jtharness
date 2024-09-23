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

# Last Test Run View Filter

When you select the Last Test Run view filter, the Test Manager displays the current totals in the
Summary pane and status icons in the test tree for all folders and tests included in the last test
run (even if you have exited the harness since the last test run) or the states from the test run in
progress if the harness is running tests. The information displayed in the Test Manager is
associated with the work directory.

The following examples provide descriptions of the use of the Last Test Run view filter:

-   **Example 1 -** A test run had failed tests and you want to rerun only the failed tests. See
    [Specifying Prior Status](../confEdit/status.html) for a detailed description of setting the
    prior status value. The Test Tree and the Summary pane continue to show all tests in the last
    test run regardless of their status.

> When you repeat the test run, the Test Manager clears the previous test results and only displays
> current status icons in the test tree and totals in the Summary pane for the tests and folders in
> the current test run.

-   **Example 2 -** A test run had failed tests and you want to use an Exclude List in the next run
    that excludes the failed tests from the test run. See [Using Exclude
    Lists](../confEdit/excludeList.html) for a detailed description of specifying an exclude list.
    The Test Tree and the Summary pane do not change when the exclude list is added to the
    configuration.

> When you repeat the test run, the Test Manager clears the previous test results and only displays
> current status icons in the test tree and totals in the Summary pane for the tests and folders in
> the current test run.

----------------------------------------------------------------------------------------------------


