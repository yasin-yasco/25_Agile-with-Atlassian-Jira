Lab: Classic Scrum Project
Estimated time: 25 minutes
In this lab, you will:
1. Create a scrum project.
2. Create issues.
3. Create and plan a sprint.
4. Execute a sprint.
5. Complete a sprint.
1:Createascrumproject.
This lab creates a classic scrum project. These instructions DO NOT APPLY to next-gen scrum projects.
1. Log into Jira (if necessary). https://[your_site_name].atlassian.net
2. Click Projects. (You may need to click on the Jira icon in the upper left to see it.)
3. Click Create project.
4. Select the classic project option. DO NOT select the "next-gen" option. These instructions only apply to
classic projects.
5. For the project name, enter projectB .
6. Click Change template. Verify that that message at the top the screen says that you are choosing a classic
template.
7. Select the Scrum template.
8. Click Create. You should see your projectB project.
Congratulations, you have created a scrum project.
2:Createissues.
1. The issues of your project are initially placed in the product backlog. Click the Backlog tab to view it. It
should be empty.
2. Create three issues in the product backlog of type Story with summaries of add item 1 , add item 2
and add item 3 . You can do this by clicking on Create (or the + sign) or by typing directly in the
Backlog .
Congratulations, you have created a product backlog with three issues.
3:Createandplanasprint.
A sprint is a period of time where you complete a certain number of issues.
1. Click the Backlog tab.
2. Click Create sprint. You now should see Sprint 1 along with the product backlog.The start of the sprint includes a sprint planning meeting. In this meeting, the sprint team usually
decides on the sprint goal, estimates the amount of work of issues and decides which issues to
complete during the sprint. The development team decides how to accomplish the work of the sprint.
All projects and sprint planning meetings are unique.
3. Add estimates as story points to the issues. We will arbitrarily say that add item 1 is 1 point, add item
2 is 2 points and add item 3 is 4 points.
Click on each issue in the product backlog and add its estimate under the Story Points field.
After entering an estimate, you should see the estimate in gray next to each issue in the product
backlog.
The development team usually is responsible for estimating story points. Story points are relative units
indicating the effort involved in completing the issue.
4. Prioritize the product backlog. We will arbitrarily give the 2 point story ( add item 2 ) the highest priority
and the 4 point story the lowest priority.
Drag and drop the stories into their correct order in the backlog (with add item 1 at the top).
The product owner is usually responsible for prioritizing stories in the product backlog.
5. Add stories to the sprint. We will arbitrarily assume that the team can execute up to four story points per
sprint. This is known as the team's velocity.
Drag the add item 2 and add item 1 stories to the sprint. The set of stories in the sprint are
called the sprint backlog.
6. Notice that the team has estimated that its velocity for this sprint will be 3 story points.
The development team is usually responsible for deciding how many of the top issues to move to the
sprint backlog.
Congratulations, you have created and planned a sprint.
4:Executeasprint.
1. Click the Start sprint button associated with the sprint backlog. Change the duration of the sprint to 1
week . Add a sprint goal of Create the first product increment. Click Start.
The scrum team agrees to the sprint goal during the sprint planning meeting.
2. Under the Active sprints tab, you should see the board for your current sprint. Notice that you have two
issues in the TO DO column. Notice that the other columns are IN PROGRESS and DONE . Also notice
that the sprint goal is under the sprint name.
3. View the workflow for the issues. Do this by clicking Project settings > Workflows. Click on the diagram
link to view the workflow. Notice that there are three statuses in the workflow, TO DO , IN PROGRESS and
DONE . These are the default statuses in the workflow when you choose the scrum template while creating
a project. Notice that there is no BACKLOG status. Navigate out of the project settings.
The workflow for projects created with the classic kanban template is different from the workflow for
projects created with the classic scrum template. The statuses in the classic kanban template workflow
are BACKLOG , SELECTED FOR DEVELOPMENT , IN PROGRESS and DONE .4. Click the Backlog tab for your project. Click to view the status of the add item 3 issue that is still in your
product backlog. Notice that its status is To Do , the same status as the issues in the first column of the
sprint board. The items in the product backlog are there because they have not been added to any sprints.
In classic scrum projects, the status of each issue is independent of the product backlog. (You could
change the status of the add item 3 issue to IN PROGRESS and it would not appear on the sprint
board.)
The classic kanban backlog functions differently than the classic scrum backlog. Unlike classic scrum,
the items in the classic kanban backlog are related to the issue's status.
5. Click the Reports tab. View the burndown chart for this sprint. Jira has added guidelines for story point
completion during the sprint. The starting value is the total number of story points that you added to the
sprint backlog. For the duration of the sprint, a linear decrease in the number remaining story points is
assumed, except for non-working days.
6. View the Sprint Report. Notice that this contains a burndown chart, as well as a list of issues in the current
sprint.
Sprint reports are a great way to quickly view the current status of the sprint.
7. Navigate back and view your board under the Active sprints tab. Let's assume that you are a member of
the development team and that you will work on the add item 2 issue. Open the issue. Under the
Assignee field, click Assign to me.
8. Navigate back to the sprint board. Notice your icon in the add item 2 card. Drag the add item 2
issue to the IN PROGRESS column.
9. Let's assume that you have finished the work of the add item 2 issue. Drag it to the DONE column.
10. Repeat the process above and complete the add item 1 issue.
Congratulations, you have executed a sprint.
5:Completeasprint.
1. Now that the issues of the sprint are done, you can end the sprint. In the upper right above the board, click
Complete sprint. Click Complete.
You usually only complete a sprint at the end of the planned sprint duration. We are ending it early just
for learning purposes.
2. View the sprint report. It shows a summary of the sprint, including the issues that were completed in the
sprint. The chart in this sprint report looks a little strange because we accelerated the completion of this
sprint.
3. Click on the tabs to view the other reports that are automatically created by Jira, such as the velocity chart.
You estimated and completed three story points in this sprint, so your velocity for sprint 1 was three story
points.
4. At this point, you would usually have a sprint review meeting to show the increment to the scrum team and
optionally to its stakeholders.
5. After the sprint review meeting is a meeting called the sprint retrospective. This is a meeting for the scrum
team to discuss how the team can execute better next time.
Congratulations, you have completed a sprint and completed this lab.