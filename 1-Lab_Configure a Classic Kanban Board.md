Lab: Configure a Classic Kanban Board
Estimated time: 25 minutes
In this lab, you will:
1. Move issues through a workflow.
2. View the default kanban workflow.
3. View the board's current column configuration.
4. Add a Review column to the board.
5. Verify that your Review column is working.
6. Configure board cards.
Note: These instructions assume you have created a projectA classic kanban project with issues.
1:Moveissuesthrougha workflow.
1. Log into Jira (if necessary). https://[your site name].atlassian.net
2. Navigate to your projectA project. This is your classic kanban project. These instructions DO NOT
APPLY to next-gen projects.
3. Click on the Kanban board tab in the sidebar to view your board (if necessary, click the Back to project
link first). This board was automatically created when you created the project and selected Kanban for the
project template.
4. You should see three issues on the board from the previous classic kanban lab.
5. Drag issues to new columns.
6. Click on an issue to open its details. Notice that the dropdown value in the upper right matches the name of
the column on the board. This is the Status field value of the issue. Change the status value. Close the
issue details and notice that your issue has changed columns on the board.
7. Again view an issue's details. Notice that the Assignee field is Unassigned . Click on the Unassigned
value and select Assign to me. This lets the team know that you are responsible for working on the issue in
this status. Close the issue details and notice that your user avatar appears with the issue on the board.
Congratulations, you have moved issues through a workflow, both by dragging and dropping and by changing
the issue's status field value.
2:View thedefaultkanban workflow.
1. While viewing your projectA project, click on the Project settings tab in the sidebar. The scope of these
settings is limited to the project.
2. Click on the Workflows tab in the sidebar to view the workflow(s) for your project.
3. You should see one workflow. Click on the (View as) diagram link to view the workflow. Notice that the
workflow contains the four default statuses of projects created with the kanban template. Also notice that
when you create an issue, its status will automatically be set to Backlog (as indicated by the circle
pointing to it). The All boxes means that all of the other statuses in the workflow can transition to this
status.
4. Close the workflow diagram.Congratulations, you have viewed a diagram of the default kanban workflow.
3:View theboard'scurrentcolumnconfiguration.
Note: The set of columns on a kanban board are related to the workflow that your issues go through. To add a
column with a new status, you must be a project administrator for the project.
1. (You can skip this step if you are on the free plan, because all users of a site are project administrators for
all projects.) Add yourself as a project administrator for the project:
With your project selected, click Project settings.
Select People.
(If the "Add people" button is disabled, you are on the free plan and can skip this step) Click Add
people and add yourself (begin typing in your name) with a role of Administrators .
2. Navigate out of project settings and view the kanban board for the project.
3. Click the ... (more) button in the upper right and select Board settings.
4. Click the Columns tab.
5. Notice that the four columns of the board are shown in the order that they appear on the board.
6. Below the horizontal bar in each column, you should see the workflow status name for the column. The
color of the status name represents the category of the status. The BACKLOG and SELECTED FOR
DEVELOPMENT status names are gray, which means that issues with these statuses have a category of To
Do . The IN PROGRESS status name is blue, indicating that issues with this status have a category of In
Progress . The DONE status name is green, indicating that issues with this status have a category of
Done .
Congratulations, you have viewed the board's current configuration.
4:Adda Review columntotheboard.
1. Under the Columns tab of your board settings, verify that the Add status button is enabled. Even though
we won't click this button directly in this lab, you need to have the permissions to add a status to the
workflow. If the Add status button is not enabled, you need to add yourself as a project administrator for
the project. These steps do not apply if you are using the free plan.
With your project selected, click Project settings.
Click People.
Click Add people and add yourself (type in your email address to find yourself) with a role of
Administrators .
Navigate back to the board settings for your board and verify that the Add status button is now
enabled.
2. Under the Columns tab of your board settings, click the Add column button.
3. In the Add column window, name the column Review and specify a category of In Progress . Click
Add to add the column to the board.
4. You should now see the Review column before the Done column. Below the blue bar, you should see
that Jira has created a REVIEW status for you, matching the name of your column. The text of the
REVIEW status is blue, indicating that the category for the REVIEW status is In Progress . In theREVIEW status, the Set resolution checkbox should remain UNCHECKED. Checking this would set an
issue's resolution field when it is moved to the Review status. We don't want to check this, because
checking it would mean that issues in this status were resolved or closed.
5. Click the Back to board link in the upper right. You should see the Review column on your board.
Congratulations, you have added a column to your board.
5:Verifythatyour Review columnis working.
1. On your board, drag issues to the Review column.
2. View an issue's details and change the Status to and from a value of Review . The issue should move to
the new column on the board.
3. From the board, open any issue. In the dropdown in the upper right, change the status of an issue to
Done . Notice that a checkmark and Done indicator are shown next to the status. This indicates that the
Resolution field is set to Done . Change the status to Review . Notice that the Done checkmark and
indicator are gone. This is because we didn't check the Set resolution checkbox when configuring the
Review column. The Resolution field is cleared.
4. Using the same procedure that you used earlier, view the workflow diagram under Project settings. You
should see the Review status. You should also see that all other statuses are allowed to transition to
Review . Jira added this status to the workflow when you added the Review column. The actual order of
the statuses in this diagram does not matter, since all statuses are allowed to freely transition to other
statuses. The order on a board is specified in board settings.
5. Navigate back to your board.
Congratulations, you have verified that your Review column is working.
6:Configureboardcards.
1. View a card on your board and identify all of the fields that are displayed.
2. Add the created field to the cards, which will display the date and time that the issue was created:
Under the Card layout tab of your board settings, add the Created field to the cards. Click the
Add button.
3. View your board. You should see the created date on all cards.
4. Use the Card colors tab of board settings to show a vertical color bar based on the issue's assignee:
Change the Colors based on field to Assignees .
View your board.
5. Undo the previous two changes to the cards on your board.
Congratulations, you have configured board cards and completed this lab.
