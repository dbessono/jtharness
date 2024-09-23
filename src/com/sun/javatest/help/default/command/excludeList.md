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

[]{#excludeList}

# Specifying Exclude Lists With `excludeList`

Test suites can supply exclude list files which contain the list of tests that the harness is not
required to run. Exclude list files conventionally use a [`.jtx`]{#jtx} extension. Once you have set
up a configuration, you can use an `excludeList` command to specify the exclude list for your test
run:

[*\> jtharness*](aboutExamples.html) \... \[*initial-setup-commands*\] \... `-excludeList`
*path/filename1* *path/filename2 \...* \[*task-command*\]

For example, to specify multiple *path/filename* arguments , issue the `-excludeList` command once
followed by multiple *path/filename* arguments separated by spaces. For example:

[*\> jtharness*](aboutExamples.html) \... \[*initial-setup-commands*\]
\...` -excludeList aaaa.jtx bbb.jtx C:\myconfig\cc.jtx` \... \[*taskcommand*\]

Note, because a space is a separator, file path arguments cannot contain spaces (for example,
`C:\Program Files\myconfig\foobar` will not work).

See [About the Command-Line Examples](aboutExamples.html) for a description of the use of *\>
jtharness*.

See [Command-Line Overview](commandLine.html) for a detailed description of the command-line
structure.

The exclude list that you specify in the command line overrides any exclude list specified in the
configuration file without changing the configuration file. To specify an exclude list, include the
commands in the following sequence:

1.  Include the commands required to set up a configuration.See [Setup Commands](setupCommands.html)
    for a description of the commands.\

<!-- -->

2.  Include the commands to specify an exclude list (`excludeList` *path/filename*).
3.  (Optional) Include a task command (such as `runtests`).\
    \
    See [Task Commands](taskCommands.html) for the commands that you can include.

## Detailed Example of `excludeList` Command

In the following example, *myconfig*`.jti` and *myexcludelist*`.jtx` represent file names that might
exist on your system.

**Command Options Format Example:**

[*\> jtharness*](aboutExamples.html) `-config` *myconfig*`.jti -excludeList`
*myexcludelist*`.jtx -runtests`

See [Formatting a Command](formatCommands.html) for descriptions and examples of other command
formats that you can use.

----------------------------------------------------------------------------------------------------


