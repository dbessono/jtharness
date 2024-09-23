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

[]{#prior}

# Selecting Tests With `priorStatus`

Tests can be selected for a test run based on their prior test status. Use the `priorStatus` command
to run tests based on their results from a previous test run:

[*\> jtharness*](aboutExamples.html) \... \[*initial-set-up commands*\] \...
`-priorStatus fail,error` \... \[*task-command*\] \...

See [About the Command-Line Examples](aboutExamples.html) for a description of the use of *\>
jtharness* in the example.

The *status-arguments* that can be used are pass, fail, error, and notRun. If you use more than one
argument, each argument must be separated by a comma.

When creating a command string to specify the prior test status, include the commands in the
following sequence:

1.  [Set up a configuration](setupCommands.html).
2.  Specify the prior test status (`priorStatus` *status-arguments*).
3.  [Include a Task Command](taskCommands.html) such as `runtests` (optional).

See [Command-Line Overview](commandLine.html) for a detailed description of the command-line
structure.

## Detailed Example of `priorStatus` Command

In the following example, *myconfig*`.jti` represents a configuration file name that might exist on
your system.

**Command Options Format Example:**

[*\> jtharness*](aboutExamples.html) `-config` *myconfig*`.jti` `-priorStatus fail,error -runtests`

See [Formatting a Command](formatCommands.html) for descriptions and examples of other command
formats that you can use.

----------------------------------------------------------------------------------------------------


