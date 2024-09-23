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

# [Startup Commands]{#newdesktop}

When starting the harness, include `-newDesktop` in the command string to start the harness GUI
without using a previous desktop. The harness ignores any previous desktop information and opens the
Quick Start wizard.

**Note: ** Some test suites do not implement the optional Quick Start wizard. It won\'t be available
if the test suite architect disabled it.

![The following text is a note](../../images/hg_note.gif){longdesc="newDesktop.html"}\
The harness uses a new desktop when you include GUI options in the command line. Using this option
preserves any preferences set for the desktop. Use the following example to start the harness with a
new Desktop.

[*\> jtharness*](aboutExamples.html) `-newDesktop`

See [About the Command-Line Examples](aboutExamples.html) for a description of the use of *\>
jtharness*.

# [Restore Tools State]{#resume}

Specify `-resume` to restore the last-saved tools state. Tools settings will be restored, even if
the preference [Check Restore Tools State on
Start](../ui/appearancePrefs.html#appearancePrefs.restore) was disabled from the user interface.

----------------------------------------------------------------------------------------------------


