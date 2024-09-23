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

# []{#name}Obtaining the Question Tag-Name

The following three ways can be used to obtain a configuration question *tag-name*:

-   **Question Tag** - Start the harness GUI, open the configuration editor, and load the
    configuration file used to run tests. Choose View **\>** Question Tag in the configuration
    editor menu bar. The configuration editor displays the *tag-name* at the bottom of the question
    pane. Navigate through the configuration until you locate the question whose value must be
    changed. Use the question *tag-name* in the command line.
-   **Control and T** - Start the harness GUI, open the configuration editor, and load the
    configuration file used to run tests. Click on text in question pane and then press the Control
    and T keys. The configuration editor displays the *tag-name* at the bottom of the pane. Navigate
    through the configuration until you locate the question whose value must be changed. Use the
    *tag-name* in the command line.
-   **Question Log** - Start the harness GUI and load the configuration file that will be used to
    run tests. Choose View \> Configuration **\>** Show Question Log to view the Question Log of the
    current configuration. The Question Log displays the *tag-name* for each question in the
    configuration and its value.
-   **Report Question Log** - Start the harness GUI and choose Create Report in the Test Manager
    menu bar. Check the Question Log option to generate a Question Log of the current configuration.
    View the report and click the Confioguration link. The Question Log displays the *tag-name* for
    each question in the configuration and its value.

----------------------------------------------------------------------------------------------------


