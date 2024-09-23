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

[]{#basicContext}

# Initial Setup Commands

Before you can perform tasks from the command line, you must first set up a configuration for the
harness to use. You can set up a configuration by performing *at least one* of the following:

1.  Specify an existing configuration (`.jti`) file. You are not required to specify either a test
    suite or a work directory.
2.  Specify an existing work directory and a configuration file. You are not required to specify a
    test suite.
3.  Open a test suite, create an empty work directory, and specify a configuration file.

After setting up a configuration, you can then change specific values for your specific
requirements. See [Setting Specific Values](otherConfigValues.html) for the commands used to modify
the values in the configuration.

You can include commands in any combination on the command line provided the initial set-up commands
are specified before any other commands in the command line.

You can use any of the following commands to set up a configuration for the harness to use when
performing tasks:

-   **`config`** - Specifies an existing configuration file. See [Specifying a Configuration File
    With `config`](config.html) for a detailed description of this command.
-   **`workDirectory`** or **`workDir`** - Specifies an existing work directory or to create a new
    work directory. See [Specifying a Work Directory With `workDir`](workdir.html) for a detailed
    description of this command.
-   **`testSuite`** - Used to specify a test suite. See [Specifying a Test Suite With
    `testSuite`](testsuite.html) for a detailed description of this command.
-   **`open`** - Specifies a test suite, work directory, configuration file, or parameter file. See
    [Specifying a Test Suite, Work Directory or Configuration With `open`](open.html) for a detailed
    description of this command.

----------------------------------------------------------------------------------------------------


