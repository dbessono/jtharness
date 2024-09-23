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

[]{#commandLineIntro}

# Command-Line Interface

There are two harness editions:

-   The *test harness* is a full-featured test system that runs on a computer that has at least the
    resources of a laptop.
-   The *lite harness* provides a subset of test harness features and can run on devices lacking
    some resources required to run the test harness.

The test harness has two interfaces, a command-line interface (CLI), and a graphical user interface
(GUI).

-   The command-line interface provides scriptable test harness functionality for configuring and
    executing tests and creating reports. Information about using the command-line interface can be
    found in the following topics:
    -   [Command-Line Summary](commandLine.html)
    -   [Set-up Commands](setupCommands.html)
    -   [Task Commands](taskCommands.html)
    -   [Desktop Commands](desktopCommands.html)
    -   [Information Commands](displayHelp.html)
    -   [Legacy Commands](legacyCommands.html)
-   The [GUI interface](../ui/usingJT.html) is more suitable for interactive test harness users.

The [lite harness](lite.html) has a command-line interface that supports most test harness CLI
commands except those that activate a graphics component (such as online help).

![The following text is a note](../../images/hg_note.gif){longdesc="editFile.html"}\
See [Troubleshooting](troubleshooting.html) for information about the codes displayed when the
harness exits after running tests using the command-line interface.

----------------------------------------------------------------------------------------------------


