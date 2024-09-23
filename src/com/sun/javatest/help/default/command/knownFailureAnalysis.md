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

[]{#writeReportsKFL} []{#kfl}

# Specifying Known Failures Lists With `kfl`

The ability to specify a known failures list is enabled in the configuration editor interview, as
described in [Creating Reports](../../default/report/newReports.html#specKFL) in the *Graphical User
Interface User\'s Guide*. In the user interface, if the value for \"Specify a Known Failures List?\"
is Yes and you have specified KFLs, they become the default values, and are used when you create
reports using Reports \> Create New Report or using the [`-writeReports`](writeReports.html) HTML
report type.

The `-kfl` option enables you to change the default list of KFL files from the command line.

You can call the KFL file(s) as follows. Multiple files are separated by spaces:

    java -jar ... -kfl foo.kfl bar.kfl path/foobar.kfl -runtests

![The following text is a note](../../images/hg_note.gif){longdesc="otherConfigValues.html"}\
Note, because a space is a separator, file path arguments cannot contain spaces (for example,
`C:\Program Files\myconfig\foobar` will not work).

See [Command-Line Overview](commandLine.html) for a detailed description of the command line
structure. See [Formatting a Command](formatCommands.html) for descriptions and examples of other
command formats that you can use.

----------------------------------------------------------------------------------------------------

