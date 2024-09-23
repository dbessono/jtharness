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

[]{#config}

# Specifying a Configuration File With `config`

To specify the configuration file the harness uses to run tests, use the `config` command.

[*\> jtharness*](aboutExamples.html) \... `-config` *path/filename* \... \[*task-command*\] \...

See [About the Command-Line Examples](aboutExamples.html) for a description of *\> jtharness* in the
example.

The configuration file might contain default values for the test suite (which contains the tests to
be run) and the work directory (where the results are placed).

Test suite and work directory values in the configuration file can be overridden with the
`testsuite` and `workdirectory` commands. If the configuration file is a template and does not
contain default values for the test suite and work directory, those values must be specified
explicitly with the testsuite and workdirectory commands.

See [Command-Line Overview](commandLine.html) for a description of the command line structure.

## Detailed Example of `config` Command

In the following example, *myconfig*`.jti` represents a configuration file name that might exist on
your system.

**Command Options Format Example:**

[*\> jtharness*](aboutExamples.html) `-config` *myconfig*`.jti -runtests`

See [Formatting a Command](formatCommands.html) for descriptions and examples of other command
formats that you can use.

----------------------------------------------------------------------------------------------------


