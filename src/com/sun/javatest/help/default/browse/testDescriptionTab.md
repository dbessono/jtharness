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

[]{#testDescriptionTab}

# Test Description Pane

Click the Test Description tab to display a two-column table of name-value pairs derived from the
test descriptions cached in the work directory. Each test in a test suite has a test description.

![Test description tab](../../images/JT4testDescriptionTab.gif){longdesc="testDescriptionTab.html"}

When you open the test suite in the harness, the test finder reads the test descriptions and caches
them in the work directory. Test descriptions in the cache and the Test Description pane are not
updated until you close and reopen the test suite. Refer to your test suite documentation for
detailed descriptions of the names and values displayed in the Test Description pane.

## Name

The names displayed in the table identify the attributes and properties contained in the test
description.

## Value

The values displayed in the table are the attribute and property values that the harness used to run
the test. The values are read from the files in the test suite.

----------------------------------------------------------------------------------------------------


