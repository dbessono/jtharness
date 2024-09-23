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

[]{#progressMeter}

# Progress Indicator

The progress indicator located at the bottom of the Information Area displays the elapsed time of
the previous test run when tests are not running. When tests are running, it automatically changes
to the progress bar of the current test run. At the completion of the test run, the indicator
changes to display the elapsed time.

You can use the ![drop-down list button](../../images/drop-down.gif){longdesc="progressMeter.html"}
button at any time to select and display either the elapsed time or the progress bar.

[]{#progressMeter.time}

## Elapsed Time

When a test run starts, the elapsed time display resets to 00.00.00. At the end of the test run, the
total elapsed time for the test run is displayed.

[]{#progressMeter.bar}

## Progress Bar

The harness displays a progress bar and a percentage complete value. As the harness completes a
test, it updates the progress bar and the percentage complete value.

----------------------------------------------------------------------------------------------------


