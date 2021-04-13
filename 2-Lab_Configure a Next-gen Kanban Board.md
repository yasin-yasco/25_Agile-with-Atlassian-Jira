Lab: Configure a Next-gen Kanban Board
Estimated time: 15 minutes
Note: This lab is optional. If you are not interested in working with next-gen projects, you can skip this lab.
In this lab, you will:
1. Move issues through a workflow.
2. Add a Review column to the board.
3. Verify that your Review column is working.
4. Add a rule to your board.
Note: These instructions assume you have created a projectAng next-gen kanban project with issues.
1:Moveissuesthrougha workflow.
1. Log into Jira (if necessary). https://[your site name].atlassian.net
2. Navigate to your projectAng project (click the Projects tab, you may need to click the Jira icon first).
This is your next-gen kanban project. These instructions DO NOT APPLY to classic projects.
3. Click on the Board tab in the sidebar to view your board. This board was automatically created when you
created the project and selected Kanban for the project template.
4. You should see three issues on the board from the previous next-gen kanban lab.
5. Drag and drop issues to new columns.
6. Click on an issue to open its details. Notice that the dropdown in the upper right matches the name of the
column on the board. This is the value of the Status field for the Jira issue. Change the status value. Close
the issue details and notice that your issue has changed columns on the board.
7. Again view an issue's details. Notice that the Assignee field is Unassigned . Click on the Unassigned
value and select Assign to me. This lets the team know that you are responsible for working on the issue in
this status. Close the issue details and notice that your user avatar appears with the issue on the board.
Congratulations, you have moved issues through a workflow, both by dragging and dropping and by changing
the issue's status field value.
2:Adda Review columntotheboard.
1. To create a column, click on the plus sign (+) the right of the DONE column. This feature is available to
administrators of the board and to Jira administrators. The user that created the board is automatically an
administrator of the board. In the free version of Jira, all users can administer the board.
2. Name the column Review and click the check mark.
3. Drag the header of the REVIEW column so that DONE is the last column on the board.
Congratulations, you have added a column to your board.
3:Verifythatyour Review columnis working.1. On your board, drag issues to the Review column.
2. View an issue's details and change the Status to and from a value of Review . The issue should move to
the new column on the board.
Congratulations, you have verified that your Review column is working.
4:Addaruletoyourboard.
Rules help you streamline your process by automatically updating fields when moving issues across columns
on a board. Project administrators can manage the rules on a board.
1. Click the more icon (...) in the upper right of your board and select Manage rules.
2. Click Add rule.
3. Add a rule that removes the assignee when you move an issue to the Review column. This helps ensure
that the person who did the work in the previous column does not review their own work. Follow these
steps to accomplish this:
Click Assign an issue to someone. Click Select.
For Choose a status, select REVIEW .
For Assign to, select No one .
Click Add.
4. Test your rule by assigning an issue to yourself, then moving the issue to the REVIEW column. You should
see that the issue is no longer assigned to you.
Congratulations, you have added a rule to your board and completed this lab.
