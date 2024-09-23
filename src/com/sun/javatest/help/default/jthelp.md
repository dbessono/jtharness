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

[]{#jthelp}

# JT Harness User\'s Guide

This User\'s Guide describes how to use the harness to run tests and evaluate test results. This
page describes the different actions used to display information from the online User\'s Guide in a
viewer provided by the harness.

-   *Graphical User Interface User\'s Guide* - contains information about using the GUI.
-   *Command-Line Interface User\'s Guide* - contains command-line and utility information.
-   *JT Harness Agent User\'s Guide* - (available only if supplied by the test suite) contains
    information about the optional agent.

Throughout the online version, the ![The following text is a
note](../images/hg_note.gif){longdesc="jthelp.html"} icon is used to identify additional information
that may be required to fully understand a topic.

[]{#jthelp.accessing}

## Accessing the Online Documentation

You can display an online version of the documentation with or without starting the GUI. To display
the User\'s Guides without starting the GUI, type the following command from the directory where the
`javatest.jar` file resides:

`java -jar javatest.jar -userGuide`

Because the harness provides the documentation viewer, no additional software is required.

The following table describes user actions in the GUI that display the User\'s Guides and other
online information:

+-------------------------------------------------+-------------------------------------------------+
| Action                                          | Description                                     |
+=================================================+=================================================+
| F1 key                                          | Press the F1 key to display information about   |
|                                                 | the window that has keyboard focus.             |
|                                                 |                                                 |
|                                                 | ![The following text is a                       |
|                                                 | note](                                          |
|                                                 | ../images/hg_note.gif){longdesc="jthelp.html"}\ |
|                                                 | You must establish keyboard focus in a window   |
|                                                 | before pressing the F1 key. To establish focus, |
|                                                 | you might have to highlight something in the    |
|                                                 | window.                                         |
+-------------------------------------------------+-------------------------------------------------+
| Help menu                                       | The Help menu lists the available online        |
|                                                 | documentation.                                  |
|                                                 |                                                 |
|                                                 | The first category of online documentation is   |
|                                                 | information for the window that has focus. To   |
|                                                 | display information for the window that has     |
|                                                 | focus (such as the Test Manager window), choose |
|                                                 | Help **`>`** *window_name* from the menu bar.   |
|                                                 |                                                 |
|                                                 | The second category of online documentation is  |
|                                                 | information for the harness. To display the     |
|                                                 | User\'s Guide for the harness, choose Help      |
|                                                 | **`>`** Online Help from the menu bar.          |
|                                                 |                                                 |
|                                                 | The third category of online documentation is   |
|                                                 | optional information (such as, users\' guide    |
|                                                 | and release notes) provided by the test suite.  |
|                                                 |                                                 |
|                                                 | The fourth category of information consists of  |
|                                                 | information about the harness and the Java      |
|                                                 | Virtual Machine. This information is collected  |
|                                                 | and provided by the harness.                    |
+-------------------------------------------------+-------------------------------------------------+
| Help buttons                                    | Click the Help button in a dialog box for       |
|                                                 | information about how to use that dialog box.   |
+-------------------------------------------------+-------------------------------------------------+

[]{#jthelp.navigation}

## Displaying Information

The following table describes the tabs in the left pane of the viewer that are used to display
information from the User\'s Guide.

+-------------------------------------------------+-------------------------------------------------+
| Tab                                             | Description                                     |
+=================================================+=================================================+
| Contents                                        | Table of contents. Topics are organized by task |
|                                                 | (where possible). Topics displayed in the right |
|                                                 | pane are highlighted in the table of contents.  |
|                                                 | You can also build a subset of pages by adding  |
|                                                 | them from the Contents to the Bookmarks section |
|                                                 | of the viewer. See Bookmarks for detailed       |
|                                                 | information building a subset of the User\'s    |
|                                                 | Guide.                                          |
+-------------------------------------------------+-------------------------------------------------+
| Index                                           | Keyword index. Index entries are listed in      |
|                                                 | alphabetical order. To search for entries,      |
|                                                 | enter a string of characters in the Find field  |
|                                                 | and press Return. If the string is found in the |
|                                                 | index, it is highlighted (press Return again to |
|                                                 | repeat the search).                             |
+-------------------------------------------------+-------------------------------------------------+
| Glossary                                        | Glossary. Glossary entries are listed in        |
|                                                 | alphabetical order. You can scroll through the  |
|                                                 | list or search for a term. To search for a      |
|                                                 | term, enter a string of characters in the Find  |
|                                                 | field and press Return. If the term is found in |
|                                                 | the glossary, it is highlighted in the list and |
|                                                 | its definition is displayed. Press Return to    |
|                                                 | repeat the search.                              |
+-------------------------------------------------+-------------------------------------------------+
| Search                                          | Full-text search. Type a natural language       |
|                                                 | phrase in the Find field and press return. A    |
|                                                 | ranked list of topics is returned with the      |
|                                                 | following information:                          |
|                                                 |                                                 |
|                                                 | -   The circle in the first column indicates    |
|                                                 |     the ranking of the matches for that topic.  |
|                                                 |     The more filled-in the circle is, the       |
|                                                 |     higher the ranking. There are five possible |
|                                                 |     rankings (from highest to lowest):          |
|                                                 |     ![Ranking of the matches                    |
|                                                 |     icon](../images/ranks.gif){align="BOTTOM"   |
|                                                 |     width="90" height="16"                      |
|                                                 |     longdesc="jthelp.html"}                     |
|                                                 | -   The number in the second column indicates   |
|                                                 |     the number of times the query was matched   |
|                                                 |     in the listed topic.                        |
|                                                 | -   The title of the topic in which matches are |
|                                                 |     found is listed as it appears in the table  |
|                                                 |     of contents.                                |
+-------------------------------------------------+-------------------------------------------------+
| Bookmarks                                       | You can add a page from the Contents to the     |
|                                                 | Bookmarks section of the viewer. Click the page |
|                                                 | name in the Contents tab and then click the     |
|                                                 | Bookmark button ![Bookmarks                     |
|                                                 | button                                          |
|                                                 | ](../images/runTests_button.gif){align="BOTTOM" |
|                                                 | longdesc="jthelp.html"} on the toolbar. The     |
|                                                 | page is listed in the Bookmarks panel. You can  |
|                                                 | then use the Bookmarks list as a customized     |
|                                                 | subset of the online document. Right click an   |
|                                                 | item in the Bookmarks list to display a pop-up  |
|                                                 | menu. Use the pop-up menu to manage items in    |
|                                                 | the Bookmarks list.                             |
+-------------------------------------------------+-------------------------------------------------+

----------------------------------------------------------------------------------------------------

