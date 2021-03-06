Lab: Issue Types with Classic Projects
Estimated time: 30 minutes
In this lab, you will:
1. Create issues of different types.
2. Create subtasks.
3. Add a custom issue type to your project.
4. Create a swimlane for the custom issue type.
Note: These instructions assume that you have Jira Administrator permission. They also assume that you
created a classic kanban project named projectA in an earlier lab.
These instructions DO NOT APPLY to next-gen projects.
1:Createissuesofdifferent types.
1. Navigate to your projectA classic kanban project.
2. If your kanban board has a separate backlog (a Backlog tab), move the backlog back to the board using
the Columns tab under board settings. This is so you can see the issues on the board when you create
them.
3. Create an issue with a summary/title named add item 4 (or the next item number on your board). Assign
an Issue Type of Story to the issue.
4. Create an issue with a summary/title named fix bug 1 . Assign an Issue Type of Bug to the issue.
5. Create an issue with a summary/title named complete task 1 . Assign an Issue Type of Task to the
issue.
6. Move the issues through some of the statuses on the board. Notice that they all behave in the same way,
because they all use the same workflow.
Congratulations, you have created issues of different types.
2:Createsubtasks.
1. Using the same procedure as in the previous step, try to create an issue with an issue type of Subtask .
Notice that this option is not available. This is because subtasks must have a parent issue. Cancel the
attempt to create this issue.
2. From the board, open the add item 4 issue. Click on Create subtask to create a subtask for this story.
3. Create a subtask with a summary/title of add item 4a . Notice that a new issue key and status are
assigned to the subtask.
4. Create another subtask with a summary/title of add item 4b .
5. View the board. Notice that the subtasks have been added under the add item 4 story in the BACKLOG
status, independent of the status of the parent issue.
6. Move the subtasks to different statuses. Notice that subtasks have independent statuses.7. On the project's sidebar, select Issues and filters to view the issues of the project. Click on All issues.
Notice that the subtasks are shown in the list. Subtasks are issues- they just need to have a parent issue.
8. Select the add item 4b subtask. Click the more icon (...) on the right to bring up a menu. Convert the
subtask to an issue by selecting Convert to Issue. Select Story as the new issue type. Select the
defaults for other values and click Finish to convert the issue. Notice by the icon that what was a subtask is
now a story.
9. View the kanban board. Move the add item 4 story to the Selected for Development status. Move
the add item 4a subtask to the Done status. Jira should notice that all of the subtasks for the story are
done and ask you if you want to update the parent issue to match the status. Click Update to move the
parent issue to the Done status.
10. Add subtasks to the fix bug 1 and complete task 1 issues. Notice that subtasks for bugs and tasks
behave the same way as with stories.
Congratulations, you have created subtasks.
3:Addacustomissuetypetoyourproject.
Custom issue types allow your team to create issues that are appropriate for the types of work that the team
does.
1. With your projectA project selected, click Project settings from the sidebar.
2. Click on Issue types. You are shown the issue type scheme for your project. An issue type scheme is the
collection of issue types used by your project. You should see the default issue types for classic kanban
projects. (These are also the default issue types for classic scrum projects.)
3. In the upper-right corner, click Actions, then select Edit issue types.
4. Notice that the default issue type is Story . This is the issue type that will be selected by default when
you first create an issue. View the order of the issue types under Issue Types for Current Scheme. You
can rearrange these to change the order of the types in Jira dialogs.
5. In the upper right corner, click + Add issue type. Name the type Small . Add a description of A work
item that is tracked but takes a small amount of time to complete. For the Type, keep
the current value of Standard Issue Type. Click Add to add the issue type to your project. You should now
see your custom issue type at the bottom of the list on the left. You can rearrange the order if you would
like.
6. Click Save to save your issue type scheme.
7. Change the avatar (icon) of your issue type.
Because an issue type can be used by any project, the configuration is under the Jira application
settings. To reach Jira settings, click on the gear icon near your user avatar.
Click Issues, and then Issue types.
Click the Edit link to the right of the Small issue type.
Click select image to change the issue type avatar.
Select the minus (-) sign, or upload your own avatar for your issue type.
Click Update to update the avatar for your issue type. The Small issue type should now have the
new icon.8. Navigate back to your projectA project. Create an issue of type Small named small item 1 . View
the item on the kanban board. Notice your icon. Open the issue and notice that you can add subtasks to the
issue.
Congratulations, you have added a custom issue type to your project.
4:Createaswimlanefor thecustomissuetype.
1. Use basic search to search for issues of your new custom type. There should be a single issue. Switch to
JQL search and view the query. Copy the query to your clipboard.
2. Navigate to the Swimlanes tab under the the projectA board's settings.
3. Explore the Base Swimlanes on dropdown to view the options for swimlanes. For example, you can create
swimlanes for each team member easily by selecting Assignees .
4. Under Base Swimlanes on select Queries.
5. Add a swimlane named Small Tasks , paste the JQL issuetype = Small and a description of
Issues that should be tracked but take a small amount of time. . Make sure to click
Add .
6. View your swimlane on the board.
7. Experiment with other swimlanes.
Congratulations, you have created a swimlane for the custom issue type and completed this lab.
