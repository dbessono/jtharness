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

[]{#editConfiguration}

# [Editing a Configuration]{#edit} {#editing-a-configuration .proc}

![This is the start of a procedure](../../images/hg_proc.gif){longdesc="editConfiguration.html"} To
edit a configuration, perform the following steps:

1.  Choose Configure **\>** Edit Configuration in the Test Manager menu bar.

> The harness opens the Configuration Editor in Question Mode and loads the current configuration.
>
> In Question Mode, the Configuration Editor enables the Bookmarks feature. Use the Bookmarks
> feature to simplify an interview by displaying only questions whose answers might change. See
> [Using Bookmarks in Configurations](setMarkers.html) for the steps required to set, clear, and
> manage Bookmarks in a configuration. See [Question Mode](fullViewDialog.html) for detailed
> information about using the features of this mode to edit a configuration.
>
> Quick Set Mode enables rapid editing of frequently changed values. If you are editing only these
> values, you can change to the Quick Set Mode. You can use the View menu at any time to change from
> one mode to the other. Because only one configuration file is loaded in the Configuration Editor
> at a time, any changes that you made in one mode are automatically reflected in the other mode.
> See [Editing Quick Set Values](editQuickSet.html) for detailed information about using the
> features of this mode to edit a configuration.

2.  In Question Mode, navigate to the question by one of the following means:

-   Use the Search menu to locate specific characters or character strings in the titles, questions,
    and answers. See [Searching a Configuration](searchConfiguration.html).
-   Choose the question directly from the Index pane.
-   Click the Back button or Next button as required to locate the question.

3.  Review and change configuration values as necessary.

> When you move backward and forward through the list of questions, the Configuration Editor
> preserves your previous answers until you change them.

4.  After making all required changes to the configuration, save the changed configuration by one of
    the following means:

-   If you are using a configuration template or an existing configuration file to create a new
    configuration file, choose File **\>** Save As from the Configuration Editor menu bar. The
    Configuration Editor opens a dialog box for you to use in setting the location and name of the
    new configuration file.
-   If you are modifying an existing configuration file used to run tests, click the Done button.
    The Configuration Editor saves the changes to the configuration file and closes. When the Done
    button is enabled, you can click it regardless of your location in the configuration.

----------------------------------------------------------------------------------------------------


