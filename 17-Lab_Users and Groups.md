Lab: Users and Groups
Estimated time: 15 minutes
In this lab, you will:
1. Invite a new user to your site.
2. Log in as the new user.
3. Create a group and add the new user.
Note: These instructions assume that you are a site administrator.
1:Inviteanew user toyoursite.
Note: If you have a second email address, you can use that for this lab. You can have up to ten users for Jira
sites that use the free plan.
1. Invite a second user to your site:
Click on the Switch to... icon (it looks like nine squares) and select Administration. This takes
you to https://admin.atlassian.com. This is where you can administer your site(s). You have access to
this because you are the site administrator for this account. Notice that under the Users tab, you can
invite a new user.
2. Select Site access. Explore the options available, including the checkbox allowing users to invite other
users (under "User invites"). If this box is checked, project administrators can invite new users using
Project settings > People.
Congratulations, you have invited a new user to your site.
2:Loginasthenew user.
1. Open the invitation email and accept the invitation. This user will become a member of the site with default
permissions. For the free Jira plan, this user will be a project administrator for all projects, but will not be a
Jira or site administrator.
2. In a separate browser window (you may want to use incognito mode so that you can be logged in as both
users at the same time), log in as the new user.
3. Notice that this user can create issues and view projects. Also notice that this user does not have Jira or
site administration capabilities.
Congratulations, you have logged in as the new user.
3:Createagroupandaddthenew user.
We will create a group that contains users who are external to our company.
1. Using the site administrator account, open site administration and click Groups from the sidebar.
2. Explore the existing groups, along with their access and administration rights.
3. Click the Create group button and create a group named jira-software-users-external with a
description of Users external to our company. .4. Notice the box on the right that states that this group currently has no product access. Click the Edit
group's access link. You are brought to the Product access tab.
5. Notice that your new group is not shown as having product access. Click the Add group button and add
your jira-software-users-external group to provide Jira access.
6. Click the Groups tab and notice that your new group allows access to the product (you may need to
refresh your browser window).
7. Click on the new group and add your new user to the group. Remove the user from the jira-softwareusers group. This user was added because jira-software-users is set as the default group.
8. Verify that your standard user can still log into Jira. You can do this by refreshing that user's browser
window.
Congratulations, you have created a group and added the new user and completed this lab.