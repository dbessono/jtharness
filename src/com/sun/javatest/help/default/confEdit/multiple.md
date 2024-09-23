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

[]{#multiple}

# Working with Multiple Configurations

In some testing situations it is useful to use separate configuration files to switch between
different configurations for different test runs. For example, one configuration could select
automated tests and another could select interactive tests.

Prior to running tests, use the Configure menu to load the required configuration file. See [Loading
a Configuration](loadConfiguration.html) for detailed information. These configuration files can be
loaded from a central resource provided by your test group. See your test group for the name and
location of the configuration files.

If your group does not provide an existing set of configuration files, you can create them by using
the Configuration Editor to edit an existing configuration and then save each variation to a file
name of your choosing. See [Editing a Configuration](editConfiguration.html) for detailed
information.

You can save these configuration files anywhere in your file system. Generally, however, the work
directory should not be used to save configuration files. Clearing the work directory would delete
the configuration file.

After these configuration files are created, they can be used by your test group to run tests.

----------------------------------------------------------------------------------------------------


