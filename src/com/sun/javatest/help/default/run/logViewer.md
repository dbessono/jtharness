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

[]{#LogViewerwindow}

# Monitoring Output Logs

You can use the Log Viewer to monitor logs produced during a test run. To use the Log Viewer, your
test suite must generate the logs that the viewer can display. See your test suite documentation for
detailed information about the log files that it generates. See [Log Viewer](../ui/logViewer.html)
for a detailed description of the Log Viewer.

The Log Viewer enables you to perform the following actions when monitoring output logs:

-   Display specific types of information from a log by selecting one or more notification levels.

    For example, you can choose to display only the Critical and Warning messages.

-   Monitor real-time content of output logs.

    You can track log data in real time by selecting the Live Scrolling check box.

-   Search log messages for text strings.

    You can use the Find text field to search for literal strings within the currently viewed log
    data.

-   Display multiple views of real-time content.

    You can display data side-by-side by clicking the Open New Log Viewer button and using different
    criteria for displaying the output data in each viewer. Only the first instance of the Log
    Viewer is used to restore log viewing preferences next time the work directory is opened.

-   Selection of log levels across all available logs in a single action.

    Use the Selection Actions list to turn on a log level in all available logs. For example, you
    can turn on Error reporting for all logs. Because the operation only affects the current logs,
    logs created after you make the selection are not affected. To include logs created after the
    initial selection, reselect the action.

-   Save log contents displayed in the log viewer. To save the log contents, click the Save button
    at the bottom of the viewer.

-   Clear the contents displayed in the log viewer. To clear the log contents, click the Clear log
    button at the bottom of the viewer.

----------------------------------------------------------------------------------------------------


