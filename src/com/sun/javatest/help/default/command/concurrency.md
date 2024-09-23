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

[]{#concurrency}

# Setting Concurrency with `concurrency`

If you are running the tests on a multi-processor computer, you can use concurrency to speed your
test runs. Use the `concurrency` command to specify the number of tests to run concurrently:

[*\> jtharness*](aboutExamples.html) \... \[*initial-set-up commands*\] \... `-concurrency` *number*
\... \[*task-command*\] \...

See [About the Command-Line Examples](aboutExamples.html) for a description of the use of *\>
jtharness* in the example.

Unless your test suite restricts concurrency, the maximum *number* of threads specified by the
`concurrency `command is 256. See your test suite documentation for additional information about
using concurrency values greater than 1.

When creating a command string to specify the number of tests to run concurrently, include the
commands in the following sequence:

1.  [Set up a configuration](setupCommands.html)
2.  Specify the concurrency value (`concurrency` *number*)
3.  [Include the `runtests` command](runTests.html) (optional).

See [Command-Line Overview](commandLine.html) for a description of the command line structure.

## Detailed Example of `concurrency` Command

In the following example, *myconfig*`.jti` represents a file name that might exist on your system
and value represents a numeric value from 1 to 256 that you might use.

**Command Options Format Example:**

[*\> jtharness*](aboutExamples.html) `-config` *myconfig*`.jti -concurrency` *value* `-runtests`

See [Formatting a Command](formatCommands.html) for descriptions and examples of other command
formats.

----------------------------------------------------------------------------------------------------


