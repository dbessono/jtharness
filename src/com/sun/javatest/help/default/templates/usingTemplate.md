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

# Working With Templates

The harness enables test suites to provide users with the capability of using templates to create
configurations required to run tests on multiple test systems or test platforms.

For example, if your test suite enables using templates and your test group uses a central location
to provide and manage the resources required to run tests (the test suite, report directories,
configuration files, or the harness), a site administrator or user could provide templates
containing the known configuration values required by the test group to run tests. A user could use
that template to quickly create a configuration for their test run by including the values unique to
their own test environment.

In addition to providing users with partially completed configurations, templates can further
simplify the process of creating and maintaining configurations through the use of the following
features:

-   Bookmarks
-   Propagation

A feature of templates is the ability to propagate updates of a template to all configurations based
on that template. When template propagation is enabled, the harness checks for template updates when
a user does any of the following:

-   Starts a test run.
-   Opens a work directory.
-   Loads a configuration.

[]{#conflictDef}

----------------------------------------------------------------------------------------------------


