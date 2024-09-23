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

# Introduction

The online User\'s Guide contains information about using the graphical user interface (GUI), the
command-line interface, the harness utilities, and the optional JT harness agent (when it is
included by the test suite). The online User\'s Guide provides a glossary, an index, and a search
function that enables the user to locate any word or phrase used in the User\'s Guides.

Users can display the User\'s Guide with or without starting the GUI. To display the User\'s Guide
without starting the GUI, type the following command from the directory where the `javatest.jar`
file is located:

`java -jar javatest.jar -userGuide`

## ![The following text is a heading](../images/closedbook.gif){longdesc="jt_intro.html"}Graphical User Interface

This section describes how the GUI enables the user to:

-   Configure, run, and monitor tests.
-   Create templates.
-   Use the Quick Start to set up and run tests.
-   Generate and view test reports.
-   Monitor agents (Optional).

## ![The following text is a heading](../images/closedbook.gif){longdesc="jt_intro.html"} Command-Line Interface

This section describes how the command-line interface enables the user to:

-   Configure, run, and monitor tests.
-   Generate and view test reports.
-   Run tests in build scripts and other automated processes.
-   Start the GUI in a specified configuration.

## ![The following text is a heading](../images/closedbook.gif){longdesc="jt_intro.html"} Utilities

This section describes how the utilities provided by the harness allow a user to perform the
following basic tasks without starting the GUI:

-   Remotely monitor results with an HTTP server.
-   Browse result files.
-   Browse exclude list files.
-   Edit entries in a configuration file.
-   Move test reports.

## ![The following text is a heading](../images/closedbook.gif){longdesc="jt_intro.html"} Optional JT Harness Agent

The harness provides an optional agent that you can use when running test suites on small systems.
In some cases, users might understand the term *agent* as including software components which are
not part of the harness. However, in this documentation, the term *agent* refers to the JT Harness
agent. If a test suite uses this agent, the test suite might also include the agent user\'s guide in
the harness.

----------------------------------------------------------------------------------------------------

