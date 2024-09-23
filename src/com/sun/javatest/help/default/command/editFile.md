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

# [Changing Configuration Values]{#edit}

When using `EditJTI` to change the values in a configuration, you can use either of the following
command formats:

-   Use *tag=value* for direct replacement of values. You must know the *tag-name* for the question
    that sets the value.
-   Use */old pattern/new pattern/* to replace all occurrences (strings) of an old pattern to a new
    pattern. This format replaces all occurrences in the file.

When using the */old pattern/new pattern/* format, the separator can be any character. However, the
string should be enclosed in quotes to avoid shell problems.

`"|/java/jdk/1.3/|/java/jck/1.4/|"`

![The following text is a note](../../images/hg_note.gif){longdesc="editFile.html"}\
To run the following examples of changing configuration values, you must replace *myoriginal*`.jti`
with a `.jti` file name that exists on your system. Win32 users must also replace the / file
separators with \\ file separators to run these examples.

Example:\
`java -cp `\[*jt_dir*`/lib/`\]`javatest.jar com.sun.javatest.EditJTI -o`
*mynew*`.jti "|/java/jdk/1.3/|/java/jck/1.4/|"` *myoriginal*`.jti`

----------------------------------------------------------------------------------------------------


