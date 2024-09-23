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

[]{#bookmarksTE}

# Setting Bookmarks

You can use Bookmarks to restrict the set of questions displayed when a user loads the template in a
Configuration Editor. This feature enables you to reduce the visible length and complexity of a
configuration interview by only displaying the questions that a user must answer before running
tests.

Bookmarks are persistent and are saved in the `.jtm` file. If bookmarks are disabled by a user, they
remain in program memory but cannot be manipulated.

## Set Bookmarks for Specific Questions {#set-bookmarks-for-specific-questions .proc}

![This is the start of a procedure](../../images/hg_proc.gif){longdesc="SetMarkersTE.html"}To set
bookmarks for specific questions in the template, perform the following steps:

1.  Click the Bookmarks **\>** Enable Bookmarks check box in the menu bar.
2.  Click a question in the Template Editor.
3.  Set a bookmark for the highlighted question by performing one of the following actions:
    -   Click to the left of the highlighted question text.
    -   Choose Bookmarks **\>** Mark Current Question in the menu bar.
    -   Right click the highlighted question and choose the Mark Current Question menu item in the
        pop-up menu.

## Display Questions With Bookmarks {#display-questions-with-bookmarks .proc}

![This is the start of a procedure](../../images/hg_proc.gif){longdesc="SetMarkersTE.html"}To only
display the questions with bookmarks, perform the following step:

-   Click the Bookmarks **\>** Show Only Bookmarked Questions checkbox in the menu bar.\
    \
    The Template Editor displays bookmarked questions in the following manner:
    -   The first question in the interview is displayed.
    -   Questions with bookmarks are displayed.
    -   If the interview is complete (all questions have valid answers) the final question is
        displayed.
    -   If the interview is incomplete (one or more questions have invalid or incomplete answers),
        the questions from the last marked question to the first question with an invalid or
        incomplete answer are displayed.
    -   Sequences of questions not described by a previous category are grouped and represented by
        three dashes (\-\--) in the list of questions. These groups can be opened to display the
        complete sequence of questions.

## Open Groups of Questions {#open-groups-of-questions .proc}

Groups of hidden questions without bookmarks are represented by three dashes (\-\--) in the list of
questions.

![This is the start of a procedure](../../images/hg_proc.gif){longdesc="SetMarkersTE.html"}To open a
group of hidden questions, perform the following steps:

1.  Click the \-\-- section in the list.
2.  Click the Bookmarks **\>** Open \-\-- Group menu item from the menu bar or right click the
    highlighted \-\-- section and choose Open \-\-- Group menu item from the pop-up menu.

## Close Groups of Questions {#close-groups-of-questions .proc}

![This is the start of a procedure](../../images/hg_proc.gif){longdesc="SetMarkersTE.html"}To close
groups of questions without bookmarks, perform the following steps:

1.  Click the question in the list.
2.  Click the Bookmarks **\>** Close \-\-- Group menu item from the menu bar or right click the
    highlighted \-\-- section and choose Close \-\-- Group menu item from the pop-up menu.

## Clear the Values of All Questions With Bookmarks {#clear-the-values-of-all-questions-with-bookmarks .proc}

![This is the start of a procedure](../../images/hg_proc.gif){longdesc="SetMarkersTE.html"}To clear
the values of all questions with bookmarks, perform the following steps:

1.  Click a question in the question list.
2.  Click the Bookmarks **\>** Clear Answers to Bookmarked Questions menu item from the menu bar.

## Clear the Value of a Specific Question {#clear-the-value-of-a-specific-question .proc}

![This is the start of a procedure](../../images/hg_proc.gif){longdesc="SetMarkersTE.html"}To clear
the value of a specific question, perform the following steps:

1.  Click the question in the list.
2.  Click the Bookmarks **\>** Clear Answer For Current Question menu item or right click the
    highlighted question and choose Clear Answer For Current Question from the pop-up menu.

## Remove All Bookmarks {#remove-all-bookmarks .proc}

![This is the start of a procedure](../../images/hg_proc.gif){longdesc="SetMarkersTE.html"}To remove
the bookmarks from the template, perform the following step:

-   Choose Bookmarks **\>** Remove Bookmarks.\
    \
    The list of questions reverts to the full list.

## Remove a Bookmark From a Question {#remove-a-bookmark-from-a-question .proc}

![This is the start of a procedure](../../images/hg_proc.gif){longdesc="SetMarkersTE.html"}To remove
the bookmarks from a question in the template, perform the following steps:

1.  Click the question in the question list.
2.  Click the Bookmarks **\>** Unmark Current Question menu item or right click the highlighted
    question and choose Unmark Current Question menu item from the pop-up menu.

----------------------------------------------------------------------------------------------------


