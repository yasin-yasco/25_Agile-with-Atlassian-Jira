Lab: Configure a Next-gen Kanban Board
Estimated time: 10 minutes
In this lab, you will:
1. Turn on the backlog feature.
2. Create a WIP (work in progress) limit.
Note: This lab is optional. If you are not interested in working with next-gen projects, you can skip this lab.
Note: These instructions assume that you have created a next-gen kanban projectAng project.
1:Turnonthebacklogfeature.
Notice that by default, there is no separate backlog for a next-gen kanban project. The separate backlog is
implemented as a feature in next-gen projects. Features are turned on by the project team as they are
needed. Features are turned on under Project settings for the project.
Note: As an alternative to creating a separate backlog, as we will do here, you could create a Backlog
column on the board, similar to creating the Review column in the previous lab. Unlike turning on the
backlog feature, this creates a Backlog status.
1. Navigate to your projectAng project.
2. In the sidebar, click Project settings and then Features.
3. Browse through the list of features. Notice, that some features are already turned on, some are off and
some may be disabled (grayed out).
4. Turn on the Backlog feature for this project by clicking the slider. The slider should turn green (assuming it
wasn't already turned on).
5. Navigate back to the board and notice that there is now a Backlog tab in the sidebar. This is a separate
location for issues. You may be prompted to move issues in your first column to the backlog. If so, select
yes. This will move the issues to the backlog. It does not change their status. In next-gen projects, the
backlog is a location for issues, not a status. Issues with any status can be in the backlog.
6. Click on the Backlog tab in the sidebar. Notice the following:
You can view all of the issues that are on the board and in the backlog.
You can move issues from the board to the backlog. Notice that this doesn't change the issue's
status. The separate backlog is a location, not a status.
You can move issues from the backlog to the board. An issue's status is not changed.
You can create issues on the board or in the backlog. The created issues by default will have the
status of the first column on the board ( To Do in our case).
To the right, you can see the circled number of issues in each general category. Gray means to do ,
blue means in progress and green means done . (Categories were discussed in more detail in a
previous lab.)
7. Move issues between the backlog and the board. This is where you can work on the backlog while the rest
of the team is focussing on the issues that are ready to be worked on.
Congratulations, you have turned on the backlog feature.2:CreateaWIPlimit.
Work in progress limits help ensure that started work gets finished and allows the team to easily see
bottlenecks in their workflow. You must be a project administrator or Jira administrator to specify WIP limits.
Project administrators are specified under the People tab of Project settings.
1. From your projectAng board, highlight the heading for the In Progress column, select ... and select
Set column limit.
2. Under Maximum issues, specify 2 . This means that the column will be highlighted if there are more than
two issues in the column, notifying the team that there is too much work-in-progress in that column. Click
Save.
3. You should now see a Max: 2 indication in the In Progress column. This is the WIP limit.
4. Drag issues to the column to violate the constraint. You may need create issues or move them out of the
backlog. You should see a highlighted column when the maximum constraint is violated.
At the time of this writing, minimum WIP limits are not a feature of next-gen boards.
Congratulations, you have created a WIP limit and completed this lab.