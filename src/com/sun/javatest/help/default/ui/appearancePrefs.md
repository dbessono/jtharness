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

[]{#appearancePrefs}

# Appearance Preferences

Change the desktop appearance by opening the Appearance folder and setting the following options:

-   [Tool Tip Options](#appearancePrefs.tooltips)
-   [Shutdown Options](#appearancePrefs.shutdown)

![Appearance preferences dialog
box](../../images/JT4appearancePrefs.gif){longdesc="appearancePrefs.html"}

See [GUI Layout](desktopStyles.html) for a detailed description of the tabbed interface.

[]{#appearancePrefs.tooltips}

## Tool Tip Options

You can set the tool tip options from the Appearance category of the Preferences dialog box.

The Tool Tips area contains combo boxes and a check box that you can use to specify how tool tips
function in the desktop. The following table describes the available tool tip options.

  Option     Description
  ---------- ----------------------------------------------------------------------------------------------
  Enabled    Use the check-box to enable or disable tool tips for the GUI.
  Delay      Use the combo box to select the delay interval before displaying tool tips.
  Duration   Use the combo box to select how long a tooltip will stay on the screen before hiding itself.

[]{#appearancePrefs.shutdown}

## Shutdown Options

Check the **Save Desktop State on Exit** option to save your current desktop for use in a future
test session. This default is on.

When you exit this option saves the current view filter information, recent work directories, and
recent configuration information. If a desktop file exists, it will remain.

If you uncheck Save Desktop State on Exit and close the harness, the current view filter information
is not saved. The next time you open a test session the harness opens the Quick Start Wizard (if the
test suite author has enabled it) or an empty harness tool.

 

[]{#appearancePrefs.restore}

Check **Restore Tools State on Start** to restore saved desktop settings. The default is on. If this
option is not checked, the recent work directories and configuration information are restored but
the tools are not.

If Restore Tools is set **on** and Save Desktop State on Exit is set **off**, the harness will
always start with one tools set (although **-newdesktop** can be used to remove all data).

----------------------------------------------------------------------------------------------------

