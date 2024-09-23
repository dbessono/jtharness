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

[]{#logViewerUI}

# Log Viewer

Use the Log Viewer to view the log contents during or after a test run. The test suite generates the
logs that are displayed in the viewer. The following illustration is an example of the content that
a test suite might generate. See your test suite documentation for detailed information about the
log files that it generates.

![harness log viewer](../../images/JT4logViewer_populated.gif){longdesc="logViewer.html"}

1.  Selection Action list
2.  Logs and levels pane
3.  Log Message pane
4.  Close button
5.  Open New Log Viewer button
6.  Save button
7.  Clear Log button
8.  Find text field.
9.  Live Scrolling check box
10. Word Wrap check box

## Selection Action List

The Selection Action list consists of three sections of message selection actions (log levels) that
a user might choose for displaying the message of a log. A log is a series of notifications
concerning a component of the system. Log levels are descriptive criteria applied to each message
within a log.

The first section of the list enables the user to either Select All log levels for display in the
log viewer or to Unselect All. The second section of the list enables the user to select one or more
general message log levels for display. In the example illustration, these messages are represented
by the General Logger messages. The third section of the list enables the user to select one or more
test suite log levels for display. In the example illustration, these message types are represented
by the TSM Logger message types.

The choices in this list only change the current state of selections. These selections would not
apply to the new log which is displayed after the user chooses Select All.

## Logs and Levels Pane

The log viewer displays a list of log levels available from the test suite that has been selected
for display. You can select one or more of the log levels in any combination. These log levels are
also listed in the Selection Action list. As in the Selection Action list, the log levels are
grouped into general types. See Selection Action List for a description of logs and log levels. See
your test suite documentation for detailed information about the log messages that it generates.

## Log Message Pane

The contents of the output log specified by the selections in the logs and levels pane are displayed
as text. The test suite specifies the output log contents displayed in the viewer. See your test
suite documentation for detailed information about the log file contents that it generates.

## Close Button

The Close button closes the log viewer. If multiple log viewers are open during a test run to
monitor specific sets of log messages, the Close button only closes the log viewer to which it is
bound.

## Open New Log Viewer Button

Use the Open New Log Viewer button to open an empty log viewer. During a test run, multiple log
viewers can be opened and used to monitor specific sets of log messages.

## Save Button

Click the Save button to save the contents of the Log Viewer as an XML file.

## Clear Log Button

Click the Clear Log button to erase the contents displayed in the log viewer and usually stored on a
disk. These contents are automatically loaded the next time that the work directory is opened.

## Find Text Field

Use the Find Text field to search the contents of the log message pane for specific text strings.

## Live Scrolling Check Box

Check to monitor for log output while the harness runs. Log entries can be generated at any time,
not just while tests are running.

## Word Wrap Check Box

Check the Work Wrap check box to cause the log viewer to wrap long line of content in the log
message pane.

 

----------------------------------------------------------------------------------------------------


