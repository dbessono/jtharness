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

[]{#stopping}

# Stopping a Test Run

When the harness is running tests, it enables both the ![Stop Test Run button displayed on the tool
bar](../../images/stopTests_button.gif){longdesc="stopping.html"}   button on the toolbar and the
Stop menu item.

Either click the ![Stop Test Run button displayed on the tool
bar](../../images/stopTests_button.gif){longdesc="stopping.html"}   button or choose Run Tests `>`
Stop to stop a test run.

As it completes each test, the harness writes the test results (`.jtr` files) in the work directory.
Stopping a test run causes the tests in progress to indicate an error.

When you stop a test run, the harness does not generate reports of test results. You must generate
the reports from the Test Manager window or from the command line. See [Creating and Displaying
Reports](../report/usingReports.html) for detailed information about test reports.

----------------------------------------------------------------------------------------------------


