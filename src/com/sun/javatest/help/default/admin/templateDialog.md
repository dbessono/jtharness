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

[]{#createConfigurationTemplate}

# Creating and Editing Templates

The harness provides users with the **[optional]{.underline}** ability to create and edit templates
that can be used to run tests on multiple test systems or test platform.

![The following text is a Note](../../images/hg_note.gif){longdesc="createTemplate.html"} Your test
suite might not enable creating or editing templates. The menu items and features described here
**[will not appear in your user interface]{.underline}** if your test suite does not support
templates.

For example, if your test suite enables creating and editing templates and your test group uses a
central location to provide and manage the resources required to run tests (the test suite, report
directories, configuration files, or the harness), you can create a template that contains all known
configuration values required by the test group to run tests. Each user can load the template from
the central site, provide only those values unique to their test environment or test run, and run
their tests using their completed configuration.

See [Creating a Template](createTemplate.html) for a detailed description of the process used to
create a template.

See [Editing a Template](editTemplate.html) for a detailed description of the process used to change
the contents of a template.

In addition to providing users with partially completed configurations, templates can further
simplify the process of creating and maintaining configurations through the use of the following
features:

-   Bookmarks
-   Propagation

An optional feature of templates is the ability to propagate (inherit) template updates to all
configurations based on that template. When the test suite developer enables template propagation,
the harness checks for template updates when a user does any of the following:

-   Starts a test run.
-   Opens a work directory.
-   Loads a configuration.

For a configuration to receive template updates, the test suite developer must enable propagation in
both the configuration and its template.

 

----------------------------------------------------------------------------------------------------


