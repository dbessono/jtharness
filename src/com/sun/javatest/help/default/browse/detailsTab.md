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

[]{#detailsTab}

# Test Run Details Pane

Click the Test Run Details tab to display a two-column table of name-value pairs that were recorded
when the test was run and may provide valuable information when troubleshooting a test run. Refer to
your test suite documentation for detailed descriptions of the result property name-value pairs for
your test.

![Test Run Details information
tab](../../images/JT4testRunDetailsTab.gif){longdesc="detailsTab.html"}

[]{#detailsTab.name}

## Name

The harness derives property names from the test results file and displays them in the table with
the following defaults:

-   Information about the version of the harness used to run the test
-   Information about the operating system used to run the test
-   Date and time the test started
-   Date and time the test ended
-   Additional details recorded by the test script used to run the test

Because the properties listed in the table are a function of the test that you are running, the
contents vary for each test suite.

Information written by commands, tests, and scripts as they are executing is displayed in the Test
Run Messages pane.

[]{#detailsTab.value}

## Value

The values displayed in the table are from the test results file created by the harness after
running the test.

----------------------------------------------------------------------------------------------------


