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

# Creating a Command File

Use the single string arguments format style to write commands in a text file. See [Formatting a
Command](formatCommands.html) for detailed information.

Command files can contain blank lines and comments as well as lines with commands and their
arguments. The following table describes the contents of a command file.

+-------------------------------------------------+-------------------------------------------------+
| File Contents                                   | Description                                     |
+=================================================+=================================================+
| Comments                                        | Comments can begin anywhere on a line, are      |
|                                                 | started by the pound symbol ( #), and stop at   |
|                                                 | the end of the line.                            |
|                                                 |                                                 |
|                                                 | Example:\                                       |
|                                                 | `#File contains commands`                       |
+-------------------------------------------------+-------------------------------------------------+
| Commands                                        | Commands are executed in the sequence that they |
|                                                 | appear in the file (for example, setup commands |
|                                                 | must precede task commands). Commands used in   |
|                                                 | the file must be separated by a semicolon (;)   |
|                                                 | or a new line symbol (#). The \# symbol acts as |
|                                                 | a new line character and can terminate a        |
|                                                 | command.                                        |
|                                                 |                                                 |
|                                                 | Examples:\                                      |
|                                                 | `open` *default*`.jti; #opens file`\            |
|                                                 | `-set host` *mymachine*                         |
+-------------------------------------------------+-------------------------------------------------+
| Command Arguments                               | Arguments that contain white space must be      |
|                                                 | placed inside quotes. Use a backslash (\\) to   |
|                                                 | escape special characters such as quotes (\"    |
|                                                 | \") and backslashes (\\).                       |
+-------------------------------------------------+-------------------------------------------------+

After writing the commands, use a descriptive name and the extension `.jtb` to save the text file.
Choose a file name that helps you identify the function of each command file.

----------------------------------------------------------------------------------------------------


