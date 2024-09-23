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

[]{#execProps.dialog}

# Viewing Test Manager Properties

To view the properties of a test manager, choose View \> Properties. The harness opens the Test
Manager Properties viewer.

![Test Manager Properties dialog
box](../../images/JT4testManagerProperties.gif){longdesc="dialog.html"}

The Test Manager Properties viewer contains the following four areas:

-   [Test Suite](#execProps.dialog.testSuite)
-   [Work Directory](#execProps.dialog.workDir)
-   [Configuration](#execProps.dialog.config)
-   [Plug-Ins](#execProps.dialog.plugins)

All value fields in the viewer can be highlighted and copied to the clipboard with keystroke
Control-C.

[]{#execProps.dialog.testSuite}

## Test Suite

The Test Suite properties area displays the Path, Name, and ID of the current test suite opened by
the test manager.

[]{#execProps.dialog.workDir}

## Work Directory

The Work Directory properties area displays the path of the current work directory opened by the
test manager.

[]{#execProps.dialog.config}

## Configuration

The Configuration properties area displays the Path, Name, Description, State, and Template of the
current configuration interview opened by the test manager. The State field indicates whether the
configuration is complete and tests can be run. It also identifies the availability of special
filters.

[]{#execProps.dialog.plugins}

## Plug-Ins

The Plug-Ins properties area displays the name of the plug-ins used by the Test Manager. The
plug-ins are provided by the test suite architect. The following table describes the properties that
might be identified in the Plug-Ins properties area.

  Property      Description
  ------------- -----------------------------------------------------------------------------
  Test Suite    The fully qualified name of the test suite class used by the test manager.
  Test Finder   The fully qualified name of the test finder class used by the test manager.
  Test Runner   The fully qualified name of the test runner class used by the test manager.
  Interview     The fully qualified name of the interview class used by the test manager.

----------------------------------------------------------------------------------------------------


