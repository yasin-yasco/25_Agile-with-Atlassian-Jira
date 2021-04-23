Lab: Filters
Estimated time: 30 minutes
In this lab, you will:
1. Explore default filter queries.
2. Create a starred filter.
3. Explore and create quick filters.
4. Explore existing board filters.
5. Create a board.
Note: These instructions assume that you have projects from the previous labs. If you have other projects, you
can modify the queries to make them work for your projects.
1:Exploredefault filterqueries.
1. Click on the Filters tab. You may need to click the Jira icon in the upper left to see it.
2. Click on each of the tabs/filters to view and execute each query. In JQL search, view the JQL and explore
any fields and/or functions that you are not familiar with. Notice that some of the queries can not be
displayed with basic search, because the user interface elements don't support the query.
Congratulations, you have explored the default filter queries.
2:Createastarredfilter.
1. In basic or JQL search, create and execute a query that searches for all issues with a statusCategory of
In Progress that are assigned to the currentUser()``. (If the search returns no issues,
you may want to move an issue to the In Progress or Review column in projectA` and assign
yourself to the issue.)
Using "statusCategory" in this query instead of "status" has the advantage of including issues in any
column where the work is in progress, such as the Review column that you created in the earlier lab.
There are only three statusCategories: To Do, In Progress and Done, so this is a very flexible query if
teams add columns/statuses to the boards.
2. Click the Save as link to save the query as a filter. Name the filter My in progress . After you create the
filter, it should show under the Starred category in the sidebar. You may need to refresh your browser to
see it.
3. In Filters click the View all filters tab. This tab is at the bottom of the sidebar. You should see your My in
progress filter in the list of filters.
4. Click on the more (...) icon to the right of your new filter and select Edit. View and change any of the
metadata details if you would like.
5. Execute the filter by clicking on it. Change the query slightly (for example, swap the order of the fields) and
re-save the filter.
6. Experiment with creating other filters.
Congratulations, you have created and edited a starred filter.3:Exploreandcreatequickfilters.
1. View your projectA classic kanban board.
2. Enter some text in the text search box below the board name to show only issues containing that text.
3. Clear the search text and click on your user icon at the top to view only your issues.
4. Click on your user icon to clear the user filter and use the quick filters to the right of the user icons to
change the issues viewed on the board.
5. Navigate to board settings and view the quick filters for the board (under the Quick Filters tab).
6. Add a quick filter named Stale Issues that displays non-done issues that have not been updated in the
last day. (Hint: updated < -1d AND statusCategory != Done ). It is a good practice to test your JQL
in advanced/JQL search before placing it in a user interface element that expects JQL.
7. Verify that your quick filter is working by navigating back to the board and clicking on Stale Issues . You
may need to change the query and/or issues' status to see results.
8. Experiment with creating other quick filters.
9. (Optional) View your projectAng next generation board. You can filter by entering text or clicking on a
user's icon. Quick filters (and the features in the rest of this lab) are currently not available for next-gen
projects.
Congratulations, you have explored and created quick filters.
4:Exploreexistingboardfilters.
1. Navigate to the kanban board for projectA .
2. In the board's settings, navigate to the General tab.
3. Under the Filter heading, view the name of the filter used as the board's filter. View the associated Filter
Query, also under the Filter heading.
4. Click Edit Filter Query. You will be brought to Filters with the board's filter executed. These are the issues
that appear on the board.
5. Under Filters, scroll down and click View all filters. Notice that the board's filter is a standard filter. Also
notice that it is not starred. This is because board filters are usually not useful as standalone queries.
Congratulations, you have explored existing board filters.
5:Createaboard.
1. Create a board's filter using the steps below. This board will be used to show all issues that are in
projectA or projectB .
Navigate to View all filters.
Copy the board's filter for projectA by selecting its More icon (...) and selecting Copy filter.
Name the filter Projects A and B . We will use this filter as a starting point for our new board's
filter.Using JQL search, modify and save the query so that it meets the requirements described above.
Reuse the ORDER BY clause from the board filter for projectA . Hint: Here is a query that would
work: project in (projectA, projectB) ORDER BY Rank ASC .
2. Create a board in your profile:
From your projectA project, click the board dropdown under the project name in the sidebar.
Click Create board.
Click Create a Kanban board. (Notice that you could create a new board with sample data. This will
create a new project in your account. This is good for looking at reports with more realistic data than
what we have seen in this course.)
In Create a board, select Board from an existing Saved Filter. Click Next.
In Name this board, name the board Projects A and B and select your Projects A and B
saved filter. Set the location to your profile (under Personal).
Click Create board. You should see your new board. You can also find the board using the VIEW
ALL link that you saw when creating the board.
3. View the board's settings and verify that the filter that you created above is being used as the board's filter.
4. Configure the board's columns.
Click the Columns tab in the board's settings. Notice that the columns of the board are the same
names as the three statusCategory values (To Do, In Progress, Done). The statuses in each column
are arranged by statusCategory.
Notice that multiple statuses are included in a single board column. If you would like, you could
create a Review column on the board and move the Review status to that column. You could also do
this for other statuses.
5. View your new board and verify that it looks and behaves as expected. You should see issues from both of
your projects.
6. Verify that your board is accessible in your profile. Click your user icon and select Your boards or Personal
boards.
7. Change the board's location to the projectA project. You can change this under the General tab for the
board's settings (under Location). Verify that projectA now has two boards. Use the board switcher
dropdown in the upper left to switch between boards.
8. Move your new board back to your user profile.
Congratulations, you have created a board containing issues that span multiple projects and completed this
lab.
