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

# [Shortcuts to Initialize a Configuration]{#restrictions}

The following apply to the test suite, work directory, and `.jti` file specified in a command:

-   If you specify an existing work directory, you are not required to specify a test suite.
-   If you specify an existing `.jti` file, you are not required to specify a test suite.
-   If you specify an existing `.jti` file, you are not required to specify a work directory unless
    you want to use a work directory different from that specified in the `.jti` file.

You can include commands as any combination of options, single string arguments, or files on the
command line. However, because commands are executed in the sequence that they appear in the command
string, *if specified, the commands must occur in the following sequence* :

-   Test suites must precede the work directory or `.jti` file.
-   The work directory and `.jti` file must match the test suite.
-   The work directory must precede any standard values.
-   The `.jti` file must precede any changes to the current configuration.

----------------------------------------------------------------------------------------------------


