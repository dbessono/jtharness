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

# Plain Text Output

The HTTP server provides plain text output that can be used for automated monitoring of the harness
during test runs. The plain text output does not include HTTP headings or HTML formatting and is
intended for use by automated testing frameworks, not for viewing in web browsers. Consequently,
future releases of the harness will attempt to maintain the content formatting and URLs of this
output.

The following two types of harness information can be accessed by automated testing frameworks:

-   [Version Information](#version)
-   [Harness Information](#harness)

## [accessing Version Information]{#version}

The HTTP Server Version page displays version information about the JT Harness harness. You can
display the HTTP Server Version page by choosing its link on the index page or by including
`/version` at the end of the URL in the browser URL field.

Example:\
`http://129.145.162.75:1903/version`

A dump of the version information is provided.

Example:\
\<*`name`*\> `Harness <`*`version`*`> Built on August 14, 2007`

## [accessing Harness Information]{#harness}

The following strings access specific information about the harness:

-   `/harness/text/config`

    Currently provides, in `java.util.Properties` format, the test suite name location and work
    directory of the current harness configuration values.

    Example:\
    `testsuite.path=/export/scratch/myTest`\
    `testsuite.name=myTest`\
    `workdir=/export/scratch/wdsc13a`

-   `/harness/text/tests`

    Provides in `java.util.Properties` format the initial tests used for the current test run.

    Example:\
    `url0=api/java_lang`\
    `url1=api/java_util`

-   `/harness/text/stats`

    Provides, in `java.util.Properties` format, the current count of test results in each state
    (pass, fail, error, not run). Whitespace is not present in the output:

    Example:\
    `Passed.=0`\
    `Failed.=151`\
    `Error.=54`\
    `Not_run.=1`\

    For performance reasons, the `Not_run` number usually equals the concurrency setting in batch
    mode and matches the \"not run\" number shown in the GUI when in GUI mode (Current Configuration
    view filter).

-   `harness/text/results`

    Provides alternating lines of test name, test status.

    Example:\
    `lang/FP/fpl005/fpl00506m1/fpl00506m1.html`\
    `Error. context undefined for hardware.xFP_ExponentRanges`\
    `lang/FP/fpl005/fpl00506m2/fpl00506m2.html`\
    `Error. context undefined for hardware.xFP_ExponentRanges`\
    `vm/classfmt/atr/atrnew003/atrnew00301m1/atrnew00301m1.html`\
    `Failed. unexpected exit code: exit code 1`\
    `vm/classfmt/atr/atrnew003/atrnew00302m1/atrnew00302m1.html`\
    `Failed. unexpected exit code: exit code 1`\
    `vm/classfmt/atr/atrnew003/atrnew00303m1/atrnew00303m1.html`\
    `Failed. unexpected exit code: exit code 1`\

-   `/harness/text/state`

    Indicates whether harness is currently running. It will return one of the following:

    `running=true`\
    `running=false`\

-   `/harness/text/env`

    Provides, in `java.util.Properties` format, the current environment settings for the test run.

    Example:\
    `command.testExecute=com.sun.jck.lib.ExecJCKTestOtherJVMCmd`\
    `/work/jdk1.3.1/bin/java` `-classpath $testSuiteRootDir/classes`\
    `-Djava.security.policy=$testSuiteRootDir/lib/jck.policy`\
    `$testExecuteClass $testExecuteArgs`\
    `context.nativeCodeSupported=true`\
    `description=bar`\
    `jniTestArgs=-loadLibraryAllowed`\
    `nativeCodeSupported=true`\
    `platform.expectOutOfMemory=true`

----------------------------------------------------------------------------------------------------


