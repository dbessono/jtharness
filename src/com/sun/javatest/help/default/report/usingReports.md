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

[]{#usingReports}

# Creating and Displaying Reports

The harness does not automatically create reports at the end of a test run. You must use the harness
to manually create a new report after the test run. You can create and view reports containing the
following test run information:

-   Tests grouped by test status
-   Configuration interview questions and answers
-   Test environment used for the test run

See [Creating Reports](newReports.html) for a description of how to create test reports.

To view reports in the harness Report Browser, choose Report **\>** Open Report from the menu bar.
See [Displaying Reports](reportBrowser.html) for a description of how to view reports.

Because harness reports contain relative and fixed links to other files, you must update these links
when moving reports to other directories. The harness provides a command-line utility for you to use
when moving reports to other directories. See [Moving Test Reports](../command/moveReports.html) in
the *Command-Line Interface User\'s Guide* for a description of how to use the `EditLinks` utility
to move reports.

----------------------------------------------------------------------------------------------------

