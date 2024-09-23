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

[]{#environment}

# Specifying Test Environment Files {#specifying-test-environment-files .proc}

Currently test suites obtain configuration values from environment entries in a configuration file
(`.jti`).

For legacy test suites the environment values are read from a test environment file (`.jte`). The
Configuration Editor uses the values from these `.jte` files to build the configuration (`.jti)`
file. Current test suites do not use or support the test environment file.

![This is the start of a procedure](../../images/hg_proc.gif){longdesc="environment.html"}To include
the values from the environment files in the configuration, perform the following steps:

1.  Click the ![QuickSet Mode button](../../images/stdValues_button.gif){width="10" height="11"
    longdesc="toolBar.html"}  Quick Set Mode button on the Test Manager tool bar or choose Configure
    \> Edit Quick Set \> Test Environment in the menu bar. The Configuration Editor displays the
    Test Environment tab only if your test suite used `.jte` files to run tests.

> The Configuration Editor opens in Quick Set Mode. The following illustration clips the More Info
> panel.

![Test Environment pane from the Configuration Editor: Question Mode
view](../../images/env_confEditor.gif){border="0" longdesc="environment.html"}

> ![The following text is a Note](../../images/hg_note.gif){width="18" height="13"
> longdesc="keywords.html"}\
> You can also use the Configuration Editor window in Question Mode to specify the test environment.

2.  Click the Test Environment tab if it does not have focus.
3.  Use the buttons and text field in the tabbed pane to create or modify a list of environment
    files used to run tests in your computing environment.

> See [Files Area](#files) and [Name Area](#environment) for a detailed description of the buttons
> and text field in the Test Environment tabbed pane.

4.  Click the Done button to save the configuration change.

## [Files]{#files} Area

Use the buttons described in the following table to create or modify a list of environment files
used to run tests in your computing environment.

  Button      Description
  ----------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Add         Adds an environment file to the list. To select an environment file (`.jte`) for your test suite, click Add. As you make selections with the file chooser dialog box, they are added to the list. After you add an environment file, you can modify the list.
  Remove      Clears an environment file from the list. Select it in the list and click Remove.
  Move Up     Moves an environment file one position higher in the list. Select it in the list and click Move Up.
  Move Down   Moves an environment file one position lower in the list. Select it in the list and click Move Down.

## [Name]{#environment} Area

Click the drop-down arrow on the text field to see the list of test environments in the environment
files listed in the Env Files list. Click the Show button to view the contents of the selected test
environment.

----------------------------------------------------------------------------------------------------


