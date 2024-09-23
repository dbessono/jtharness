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

# [Doing Escapes in a UNIX System Shell]{#example3}

The following example uses the syntax for doing escapes in a UNIX system shell. Changes to the
original configuration file (*myoriginal*`.jti` in this example) are written to a new configuration
file (*my-newconfig*`.jti` in this example).

In the following example, *myoriginal*`.jti` represents a configuration file name that might exist
on your system. Win32 users must also replace the UNIX system file separators (\\) with Windows file
separators (/) to run these examples.

To change a value in the command line, use the *tag-name* for the question that sets the value. See
[Obtaining the Question tag-name](tagName.html) for detailed information about viewing the
*tag-name* for the question.

`java -cp` \[*jt-dir*`/lib/`\] `javatest.jar com.sun.javatest.EditJTI`\
`-o`
*my-newconfig*`.jti test.serialport.midPort=/dev/term/a test.connection.httpsCert="\"CN=<Somebody>, OU=<People>, O=<Organisation>, L=<Location>, ST=<State>, C=US\""`*myoriginal*`.jti`

----------------------------------------------------------------------------------------------------


