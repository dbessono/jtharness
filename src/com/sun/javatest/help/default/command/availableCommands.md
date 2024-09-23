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

# [List of Available Commands]{#batchCommands}

The following table describes all of the commands available in command mode.

  Command                                        Description
  ---------------------------------------------- ----------------------------------------------------------------------------------------------------------------------------------
  [`concurrency`](concurrency.html)              Specifies the number of tests that are run concurrently.
  [`env`](testEnv.html)                          Specifies a test environment in an environment file.
  [`envFile` or `envFiles`](testenvFile.html)    Specifies an environment file (`.jte`) containing test environments.
  [`excludeList`](excludeList.html)              Specifies an exclude list file.
  [`keywords`](keyword.html)                     Restricts the set of tests to be run based on keywords.
  [`kfl`](knownFailureAnalysis.html#kfl)         Specifies one or more known failure list (`.kfl`) files.
  [`open`](open.html)                            Opens a test suite, work directory, or a configuration `.jti` file.
  [`params`](param.html)                         This command is deprecated.
  [`priorStatus`](prior.html)                    Selects the tests included in a test run based on their outcome on a prior test run.
  [`set`](otherConfigValues.html)                Overrides a specified value in a configuration (`.jti`) file.
  [`tests`](testDir.html)                        Creates a list of test directories and/or tests to run.
  [`testSuite`](testsuite.html)                  Specifies the test suite.
  [`timeoutFactor`](timeout.html)                Increases the amount of time the harness waits for a test to complete
  [`workDir` or `workDirectory`](workdir.html)   Opens an exiting work directory, creates a new work directory, or replaces an existing work directory with a new work directory.
  [`runTests`](runTests.html)                    Runs tests in command mode.
  [`writeReport`](writeReports.html)             Writes test reports in command mode.

----------------------------------------------------------------------------------------------------

