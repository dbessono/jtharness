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

[]{#runTests}

# Running Tests With `runtests`

Use the `runtests` command to run the tests specified in the configuration.

[*\> jtharness*](aboutExamples.html) \[*monitor-option*\] \[*setup-commands*\] \... `-runtests` \...

See [About the Command-Line Examples](aboutExamples.html) for a description of the use of *\>
jtharness* in the example.

See [Command-Line Overview](commandLine.html) for a detailed description of the command-line
structure.

You can also use the `runtests` command as part of a sophisticated command sequence that resembles
and functions as a script. You can include command files and multiple commands in the same command
string to programmatically perform repeated, multiple test runs of different configurations without
starting the harness GUI.

See [Using Command Files](commandFile.html) for detailed information about creating and using
command files.

A *monitor-option* can be set in the command line to display test progress information during the
test run. See [Monitor Test Progress Option](verbose.html) for detailed information about setting
this option.

When creating the command string to run one or more tests, include the commands in the following
sequence:

1.  (Optional) Include the command required to monitor a test run.

> See [Monitoring Test Progress With `verbose`](verbose.html) for detailed information about the
> command.

2.  Include the commands required to set up a configuration.

> See [Setup Commands](setupCommands.html) for detailed description of the available commands.

3.  Include the `runtests` command.

[]{#runTests.example}

## Detailed Example of `runtests` Command

In the following example, *myconfig*`.jti` represents a configuration file name that might exist on
your system.

**Command Options format example:**

[*\> jtharness*](aboutExamples.html) `-config` *myconfig*`.jti -runtests`

See [Formatting a Command](formatCommands.html) for descriptions and examples of other command
formats that you can use.

----------------------------------------------------------------------------------------------------


