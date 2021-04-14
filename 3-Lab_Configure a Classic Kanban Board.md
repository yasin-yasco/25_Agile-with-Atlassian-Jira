Lab: Configure a Classic Kanban Board
Estimated time: 20 minutes
In this lab, you will:
1. Configure a kanban board to use a separate backlog.
2. Assign work in progress limits on kanban board columns.
3. Add a "Development Done" column as a queue.
4. View a cumulative flow diagram.
5. View a cycle time control chart.
Note: These instructions assume that you have created a classic kanban projectA project. They also
assume that you are a project administrator for the project (see the previous lab).
1:Configureakanbanboardtouseaseparatebacklog.
1. In your classic projectA project, move some issues to the BACKLOG column of your kanban board.
2. Navigate to the board settings (... > Board settings) .
3. Click the Columns tab.
4. Drag the BACKLOG status (the box at the bottom of the Backlog column- not the column itself) from the
first column to the Kanban backlog section on the left. You should now see the BACKLOG status in the
kanban backlog and the Backlog column of the board should not contain any statuses.
Note: You can drag any status(es) except DONE to the kanban backlog. The status does not have to be
named BACKLOG .
5. View your kanban board. You should now see SELECTED FOR DEVELOPMENT as the first column. The
BACKLOG column has been moved to the kanban backlog.
6. Click on the Backlog tab (this was added by Jira when you enabled the kanban backlog).
7. Move issues between the backlog and the first visible column on the kanban board ( Selected for
Development ). This is where you can work on the backlog while the rest of the team is focussing on the
issues that are ready to be worked on.
Congratulations, you have configured a kanban backlog.
2:Assign workinprogress(WIP) limitsonkanbanboardcolumns.
Work in progress limits help ensure that started work gets finished and allows the team to easily see
bottlenecks in their workflow. You must be a project administrator or board administrator to specify WIP limits.
Project administrators are specified under the People tab of Project settings. Board adminstrators are
configured under the Administrators heading of the General tab in Board settings.
1. From your projectA kanban board, click the ... button and select Board settings.
2. Click the Columns tab.
3. Verify that the Column Constraint is set to Issue Count .4. In the Selected for Development column, specify a minimum issue count of 2 . This means that the
column will be highlighted if there are less than two issues in the column, notifying the team that more
issues need to be added to the column.
5. In the In Progress column, specify a maximum issue count of 2 . This means that the column will be
highlighted if there are more than two issues in the column, notifying the team that there is too much workin-progress in that column.
6. Click Back to board.
7. You should now see a Min 2 indication in the Selected for Development column and a Max 2
indication in the In Progress column. These are the WIP limits.
8. Drag issues to the columns to violate the constraints. You may need to change the status of issues in the
backlog. You should see a highlighted column when the minimum or maximum constraint is violated.
Congratulations, you have created WIP limits.
3:Adda"DevelopmentDone"columnasaqueue.
Right now, your kanban board should have a Review column before the Done column (the previous lab
added a Review column). In this part of the lab, you will add a Development Done column before the
Review column. This is so that an issue can be moved to Development Done when the In Progress
work is complete. When a reviewer is ready for another issue, they can pull the issue from the Development
Done column. This prevents a developer from pushing an issue into the Review column directly.
1. Using a procedure similar to the previous lab, add a Development Done column (which also adds a
status) to your kanban board. Make sure to drag it to the column before Review .
2. Using a procedure similar to this lab, set a WIP limit of Max 2 for the Development Done column.
3. Test that your new column is working as expected.
Congratulations, you have added a queue to your board.
4:View acumulativeflow diagram.
1. Move all issues of the project to the Done column.
2. Click on the Reports tab in the sidebar.
3. Click on Cumulative Flow Diagram. Notice that Jira automatically creates reports for you. This report
might not look that great, but it shows the changing of issues' status that you have done so far.
4. Zoom into any section of the report by clicking and dragging the cursor across the top chart or the small
chart below it. You can double-click on the small chart to reset the top chart.
Congratulations, you have viewed a cumulative flow diagram.
5:View acycletimecontrolchart.
1. Click on the Control Chart tab.2. View the chart. This shows the cycle time for the issues of the project. This is the time between when an
issue is moved from the backlog to In Progress until the time that the issue is moved to the Done
column. Use the controls below the chart to change the horizontal timeframe of the chart. This chart also
might not look that great. A continuously improving team should show a cycle time that decreases over
time.
3. Explore the other reports related to your kanban project. Jira provides a lot of ways to analyze what your
team is doing.
Congratulations, you have viewed a cycle time control chart and completed this lab.
