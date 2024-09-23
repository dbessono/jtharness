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

[]{#open}

# Specifying a Test Suite, Work Directory or Configuration (`open`)

To specify a test suite, work directory, or a configuration `.jti` file, use the `open` command:

\... `open` *path/filename* \...

![The following text is a note](../../images/hg_note.gif){longdesc="open.html"}\
See [About the Command-Line Examples](aboutExamples.html) for a description of the use of *\>
jtharness* in the following example. See [Command-Line Overview](commandLine.html) for a description
of the command line structure. See [Formatting a Command](formatCommands.html) for descriptions and
examples of the following command formats.

**Command Options Example:**

[*\> jtharness*](aboutExamples.html) \... `-open` *path/filename* \... \[*task command*\] \...

**Single String Arguments Example:**

[*\> jtharness*](aboutExamples.html) \... `; open` *path/filename* ; \... \[*task command*\] \...

**Command File Example:**

[*\> jtharness*](aboutExamples.html) `@`*mycmd*`.jtb` \... \[*task command*\] \...

In addition to any other commands, for this example the *mycmd*`.jtb` command file must contain the
command:\
\"`open` *path/filename*;\"

Refer to [Using Command Files](commandFile.html) for detailed information about creating and using
command files.

----------------------------------------------------------------------------------------------------


