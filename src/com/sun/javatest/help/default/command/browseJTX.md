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

[]{#excludeList}[]{#excludeList1}[]{#excludeList2}[]{#excludeList3}

# Browsing Exclude List Files

Included in the javatest.jar file is a servlet that allows you to use a web browser to view `.jtx`
files.

To view `.jtx` files in your web browser, you must configure your web server to use the
[]{#excludeList4}[]{#excludeList5}JT Harness harness `ExcludeBrowser` servlet.

`com.sun.javatest.servlets.ExcludeBrowser`

Refer to your server documentation for information about configuring it to use the harness
`ExcludeBrowser` servlet. Typically, you configure the web server to direct `.jtx `files to the
servlet for rendering.

----------------------------------------------------------------------------------------------------


