Lab: Quick Search and Basic Search
Estimated time: 20 minutes
In this lab, you will:
1. Perform quick searches.
2. Perform basic searches.
3. Work with search results.
Note: These instructions assume that you have projects from the previous labs. If you have other projects, you
can change the search to provide results for your project.
1:Performquicksearches.
1. Click in the search box in the upper right (or if you see it, click on the search icon in the sidebar) to view
quick search. Notice that you have access to recent issues, boards, projects and filters.
2. Search for "item". As you type, the search results will change. This searches issues with fields of types text,
board names, filter names and project names. Press Enter. You will be taken to the Filters section with the
associated text-based search of issues.
3. Use quick search to search for "item 2".
4. Search for "ITEM 2" and verify that search terms are not case-sensitive.
5. Search for "item AND 2". The results should be the same as the previous search. The terms of a query are
joined with AND by default.
6. Search for "item NOT 1". The NOT keyword should exclude the "add item 1" issues.
7. Search for "item not 1". This should return the "add item 1" issues. This is because "not" is in lowercase, and
it is such a common word that it is excluded from the search (a reserved or stop word). This is the same as
searching for "item 1".
8. In another browser window or tab, perform a general web search for "Jira search syntax for text fields".
Click on the Atlassian documentation. Click on Cloud in the upper right. Scroll down to the "Reserved
words" heading and verify that "and" and "not" are reserved words for searches of text fields.
9. Back in Jira, perform any quick searches that interest you.
Congratulations, you have performed quick searches.
2:Performbasicsearches.
1. Click on the Filters tab. You may need to click the Jira icon in the upper left to see it.
2. Click on the All issues tab. You should be viewing all of the issues of the projects.
3. Verify that you are in the basic search. You should see a row of interface elements under All issues and a
Switch to JQL link to the right (this used to be called "Advanced"). If you see a Basic link, click on it to
change from JQL to basic search.
4. Click on the Project dropdown to view the issues of any one of your projects.5. Use the "Contains text" box in the basic search row to further limit your results. Press Enter or click on the
search hourglass to perform the search. Verify that the NOT keyword works in the basic search.
6. Use quick search (like you did earlier in the lab) to type in "item" and click Enter. You should be brought to
*Filters area with basic search. Verify that the text that you entered is in the textbox.
7. Clear the existing search by clicking Search issues or All issues in the sidebar.
8. In basic search, click on the More dropdown and search for issues that have been updated (Updated Date
field) in the last hour, day and week. Your results depend on when you performed the previous labs.
9. Perform any basic searches that interest you.
Congratulations, you have performed basic searches.
3:Work withsearchresults.
1. Toggle between List View and Detail View using the Change View icon to the right of the basic search
elements.
2. In List View, click on the Columns dropdown to change the columns that are displayed in the results. Click
Restore defaults to undo what you have changed.
3. Reorder the first two columns by dragging and dropping the column header. Change it back.
4. Click on a column header to sort by that column. Click on the column header again to reverse the sorting.
5. In the basic search "Contains text" box, enter "item 2" and click Enter. Using the Share icon in the upper
right, email yourself a copy of the search results. You should receive an email with a link to the underlying
JQL query. Click on the link in the email and you should see your search in a new browser window. Close
the new browser window.
6. In the original browser window, click on the Export icon in the upper right. Select Export XML. You should
see the XML search results. View the issues' field names and values under an item. If the XML displayed in
your browser window, click the browser's back button to navigate back to Jira.
7. Change the Assignee of all of the issues of the project:
Search for all issues of your projectA project.
Click on the More icon (the three dots) in the upper right and select Bulk change all X issue(s).
In step 1, select the issues that are Unassigned. (If they are all assigned, you can change this
exercise to unassigning them all.)
In step 2, select Edit Issues.
In step 3, click Change Assignee and click Assign to me.
In step 4, click Confirm.
Verify that your bulk changes were made.
8. Perform any other quick search or basic search operations that interest you.
Congratulations, you have worked with search results and completed this lab.