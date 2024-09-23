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

[]{#createTemplate}

# Creating a Template {#creating-a-template .proc}

![This is the start of a procedure](../../images/hg_proc.gif){longdesc="setMarkers.html"}To create a
template, perform the following steps:

1.  Choose Configure **\>** New Template from the Test Manager menu bar.
2.  Answer the questions displayed in the Template Editor.\
    \
    The Template Editor displays questions in the center pane (the Question Pane). After answering a
    question, click the Next button to proceed to the next question.

<!-- -->

3.  Choose File **\>** Save As from the menu bar and save the template with a relevant name.\
    \
    Template file names are automatically appended with a `.jtm` extension.

An optional feature enables template updates to propagate (flow) to all of the configurations that
are based on the template. When template propagation is enabled, the harness checks for template
updates when a user does any of the following actions:

-   Starts a test run
-   Opens a work directory
-   Loads a configuration

![The following text is a Note](../../images/hg_note.gif){longdesc="createTemplate.html"}\
Changes to a template propagate to configurations based on the template *only* if propagation is
enabled in both the template and the derived configurations.

----------------------------------------------------------------------------------------------------


