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

[]{#editingTemplate}

# Loading a Template {#loading-a-template .proc}

![This is the start of a procedure](../../images/hg_proc.gif){longdesc="loadTemplate.html"} To load
a template, perform the following steps:

1.  Choose Configure \> Load Template from the Test Manager menu bar.

> The harness opens a Load Template dialog box containing a path field with Browse button and a
> navigation area that displays the file name, the template name (contained in the template), and
> the template description (contained in the template).
>
> The Path field sets the starting location for the directories and files displayed in the
> navigation area.
>
> The navigation area displays the directories and template files (if any) in the location set in
> the Path field. Only template files are displayed in the navigator area. Other files are hidden.

![Load Template](../../images/JT4loadTemplate.gif){longdesc="loadTemplate.html"}

2.  Use the icons in the dialog box to navigate to the location of the template.

> The Path text field in the dialog box displays the location for the list of files displayed in the
> dialog box.

3.  Click the template icon and the Load button.

> The harness loads the template. If the template is not correct for the test suite, the harness
> displays an error dialog box and closes without loading the template.

----------------------------------------------------------------------------------------------------


