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

# []{#load}Loading a Configuration {#loading-a-configuration .proc}

![This is the start of a procedure](../../images/hg_proc.gif){longdesc="loadConfiguration.html"}To
load an existing configuration, perform the following steps:

1.  Choose Configure **\>** Load Configuration from the Test Manager menu bar, or, if you have an
    open Configuration Editor window, choose File **\>** Load Configuration from the menu bar.

> The harness opens the Load Configuration dialog box.

![Keyword tab](../../images/JT4loadconfig.gif){longdesc="loadConfiguration.html"}

![The following text is a note](../../images/hg_note.gif){longdesc="saveConfiguration.html"}\
If your test group provides an existing configuration, you can use it to run tests.

2.  Locate and select the configuration file (`.jti`).
3.  Click the Load button.

> The harness loads the file and closes the Load Configuration File chooser.

If you loaded a configuration file that you must edit before running tests, use the Configuration
Editor to set appropriate values for your test environment. See [Editing a
Configuration](editConfiguration.html).

----------------------------------------------------------------------------------------------------


