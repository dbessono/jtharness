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

# Changing the HTTP Port

You can use `EditJTI` to change the HTTP port and either overwrite the original configuration file
or create a new configuration file.

![The following text is a note](../../images/hg_note.gif){longdesc="changePort.html"}\
To run the following examples, you must use a `.jti` file that exists on your system and include
httpPort in your current interview path. If your current interview path does not include httpPort
you will not be able to change its value from the command line. To view the current interview path,
open your `.jti` file in the Configuration Editor. See [Obtaining the Question
tag-name](tagName.html) for detailed information about the *tag-name* for the question.

## [Change the HTTP Port and Overwrite Original Configuration File]{#example1}

The following example changes the HTTP port used when running tests and overwrites original
configuration file (*myoriginal*`.jti` in this example).

`java -cp` \[*jt-dir* `/lib/`\] `javatest.jar com.sun.javatest.EditJTI httpPort=8081`
*myoriginal*`.jti`

## [Change the HTTP Port and Create a New Configuration File]{#example2}

The following example changes the HTTP port used when running tests and writes the changed
configuration to a new configuration file (*myoutput*`.jti` in this example). The original
configuration file (*myoriginal*`.jti` in this example) remains unchanged.

`java -cp` \[*jt-dir* `/lib/`\] `javatest.jar com.sun.javatest.EditJTI -o`
*myoutput*`.jti httpPort=8081` *myoriginal*`.jti`

----------------------------------------------------------------------------------------------------


