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

[]{#folderInfo}

# Information Area

The Test Manager uses the information area to display information about the item selected in the
test tree. The Test Manager uses two views, folder view and test view, to display the information.

## Folder View

When you click a folder icon in the test tree, the Test Manager displays a Summary tab, a
Documentation tab, five status tabs, and a status field containing information from the work
directory about a folder and its descendants.

![Information pane, folder view](../../images/JT4folderview.gif){border="0"
longdesc="folderInfo.html"}

The folder view contains filtered summary and status information about the tests in a test folder.
The Test Manager also displays a status message at the bottom of the area about the selected view.
The messages can indicate that tests in the folder are loading or they can provide detailed status
information about a selected test.

During a test run, you can use the folder view to monitor the status of a folder and its tests. You
can also use the folder view during troubleshooting to quickly locate and open individual tests that
had errors or failed during the test run. When a status pane is empty, the Test Manager disables its
tab. This information is displayed in the Summary tabbed pane as values and as a pie chart. The
folder view and test tree use the same view filter when displaying information.

See [Displaying Folder Information](../browse/folderInfo.html) for detailed information about this
view.

## Test View

When you click a test icon in the test tree or double click its name in the Folder view, the Test
Manager displays tabbed panes that contain detailed information about the selected test.

![Test information pane](../../images/JT4Tabbed.gif){longdesc="infoPane"}

See [Displaying Test Information](../browse/testInfo.html) for detailed information about this view.

----------------------------------------------------------------------------------------------------


