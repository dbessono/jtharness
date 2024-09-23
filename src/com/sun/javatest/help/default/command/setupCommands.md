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

[]{#setupCommands}

# Setup Commands

Before you can perform a task from the command line, you must first use setup commands to specify a
configuration.

After setting up a configuration, you can then modify the values in the configuration for your
specific requirements. These changed values override but do not change values in the configuration
file. You can use configuration templates from a central resource to run tests on different test
platforms and configurations.

![The following text is a note](../../images/hg_note.gif){longdesc="setupCommands.html"}\
See [About the Command-Line Examples](aboutExamples.html) for a description of use of *\> jtharness*
in the following example.

The setup commands are used in the following sequence in the command line:

[*\> jtharness*](aboutExamples.html) \[*initial-setup-commands*\] \[*set-specific-values*\]
\[*additional-setup-commands*\] \[*task-commands*\]

Setting specific values and additional setup commands are optional.

The task command at the end of the example is also optional. If a task command is not included, the
harness uses the specified configuration and any changes set on the command line to open the GUI.

For additional information about using setup commands see the following topics:

-   [Initial Setup Commands](basicContext.html)
-   [Setting Specific Values](otherConfigValues.html)
-   [Additional Setup Commands](harnessSettings.html)

----------------------------------------------------------------------------------------------------


