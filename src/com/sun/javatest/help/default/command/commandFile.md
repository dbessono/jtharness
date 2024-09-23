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

[]{#commandFile}

# Using Command Files

A command file is a text file that contains one or more commands used by the harness from the
command line or as a part of a product build process. You can place combinations of configuration
settings and commands in the command file and use it to repeatedly perform the following actions:

-   Perform test runs
-   Write test reports

The advantage of using the command file format is that it is easy to use a complex, persistent,
repeatable set of commands in a command line.

The commands used in a command file are a formatted set of commands, executed in the sequence that
they appear in the command string. Use the commands in the command file as you would if you were
writing a script. See [Formatting a Command](formatCommands.html) for a description of the formats
you can use.

The following topics provide additional detailed information:

-   [Creating a Command File](creatingCommandFile.html)
-   [Examples of Using Command Files](examplesCommandFile.html)

----------------------------------------------------------------------------------------------------


