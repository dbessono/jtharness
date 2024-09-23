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

[]{#resolveConflict}

# Resolving Configuration-Template Conflicts

When the harness detects a conflict between a configuration and its template, it displays a Template
update conflict dialog box.

![Template conflict dialog
box](../../images/JT4templateconflict.gif){longdesc="resolveConflicts.html"}

By default, any change to a template is considered a Conflict and is listed in the Conflicts tab.
Configuration users get to choose whether to accept the new template value, reject the value, or
postpone deciding.

A test suite can also declare a template question to be auto-updating. If a user changes an
auto-updating value in the template, the harness replaces the corresponding property in the attached
configuration. The updated value is listed on the Updates tab.

![Template update dialog box](../../images/JT4templateupdates.gif){longdesc="resolveConflicts.html"}

A user cannot refuse to accept an auto-updating value.

Choose a dialog button based on the following guidelines:

-   **Change Now** - Click this button if you want the new template values to overwrite the
    corresponding configuration values.
-   **Don\'t Change** - Click this button if you want the new template values to be ignored.
-   **Remind Me Later** - Click this button if you want to defer the conflict resolution until the
    next time the harness checks for updates.

----------------------------------------------------------------------------------------------------


