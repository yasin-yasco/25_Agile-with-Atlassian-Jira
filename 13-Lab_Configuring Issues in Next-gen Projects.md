Lab: Configuring Issues in Next-gen Projects
Estimated time: 15 minutes
In this lab, you will:
1. Add labels to issues.
2. Search for issues by label.
3. Turn on estimation and enter story points.
4. Create a custom field.
Note: These instructions assume that you have created a next-gen kanban project named projectAng in an
earlier lab.
These instructions DO NOT APPLY to classic projects.
1:Addlabelstoissues.
1. Add labels named refactor and/or database to some of the issues in projectAng . If you hover over
an issue's card on the board, you can click on the more icon (...) and select Add label. You could also do
this by adding entries to the Labels field of an issue. Make sure to click the checkmark to add the label.
2. View your board to verify that the labels appear. Next-gen project cards are automatically configured to
show labels.
Congratulations, you have added labels to issues.
2:Searchfor issuesbylabel.
1. Open an issue with a label of database .
2. Under Labels , click on the database label. You should be brought to the Filters area with a search for
all issues with the database label. This is the easiest way to search for issues with a certain label.
3. Use basic search to search for issues with a label of refactor . You will have to use the More dropdown
to add Label as a search criteria.
Congratulations, you have searched for issues by label.
3:Turnonestimationandenterstorypoints.
1. While in your projectAng project, click Project settings > Issue types.
2. If Story does not show as an issue type, click + Add issue type and add Story.
3. Create an issue of type story, with a summary of add item X , where X is the next item number for your
board.
4. Open the new story and verify that Story Point Estimate is not shown. This is because story points
are not commonly used in kanban projects and the estimation feature is turned off.
5. Click on the more icon (...) in the upper right and select Configure. You are brought to the Project settings
> Issue types > Story screen. Notice that Story Points are not present. This is because the estimation
feature is not enabled.6. While in your projectAng project, navigate to Project settings > Features and turn on Estimation.
7. From the board, open the story and verify that there is now a Story point estimate field. Enter a story point
value for the issue.
8. Navigate to Project settings > Issue types > Story and notice that Story point estimate is now a primary
field. This is because you turned on the Estimation feature.
Congratulations, you turned on estimation and entered story points.
4:Createacustomfield.
1. From your projectAng project board, open an issue of type Story.
2. Click on the more icon (...) in the upper right and select Configure. This takes you to Project settings >
Issue types > Story.
3. In the toolbar on the right, click the Short text icon under CREATE A FIELD.
4. The field will be added under Context fields.
5. Enter a new field named Acceptance Criteria . For Describe how people should use this field, enter
A list of user-centered tests that must pass for the story to be considered done. .
6. Drag and drop to reorder the fields as desired.
7. Click Save changes.
8. Verify that your new Acceptance Criteria field is shown when you view a story's details. In the text
area, enter something like User must be able to enter an email address. .
9. Open the create issue dialog and verify that your Acceptance Criteria field is available when creating
issues.
This new "Acceptance Criteria" field only applies to the projectAng project. Unlike with classic
projects, adding a custom field to a next-gen project is not a global configuration. This keeps each
project configuration separate and in control of the project team.
10. Perform an advanced/JQL search for issues with an Acceptance Criteria field that is not empty. Type
A and notice that there are now two Acceptance Criteria field choices (assuming you did the classic
version of this lab). One of those choices is the globally configured field from the classic lab and the other
is the field created in this lab. You can query for one of those choices by selecting from autocomplete, or
query for all issues that have a non-empty Acceptance Criteria field using "Acceptance Criteria" is
not EMPTY .
Congratulations, you have created a custom field and completed this lab.
