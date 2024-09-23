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

# [Changing Test Suites or Creating a New Interview]{#change}

The following example uses the `-ts` option to create an empty interview derived from the test suite
( *mytestsuite*`.ts`). Use the `-ts` option only for very simple test suites.

Example:\
`java -cp` \[*jt_dir* `/lib/`\] `javatest.jar com.sun.javatest.EditJTI -o` *mynew*`.jti -l`
*myeditlog*`.html -ts` *mytestsuite*`.ts "|/java/jdk/1.3/|/java/jck/1.4/|"` *myoriginal*`.jti`

If a change is made that is not in the current interview path, the interview will be invalid and the
tests cannot be run.

Do not use `EditJTI` to change the interview path, but only the values on the existing path. If you
are in doubt about the current interview path, open the configuration editor window in the harness
GUI and use it to change the values. The configuration editor window displays the current interview
path for that question name-value pair.

----------------------------------------------------------------------------------------------------


