# jira-issue-details-enhancements
Enhance your JIRA issue details page

Creates nice copypasteable text in JIRA issue package
This text can be used for instance in copyTextSlack
Format: ISSUESID - Issuetitle
Format: ISSUESID - Issuetitle (StoryPoints)
The IssueID is linked to the story
Example DBI-2334 - Create new form (8)

## INSTALL
1. Install 'User JavaScript and CSS' extension for Chrome https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld?hl=en
2. Open a random JIRA issue in your browser. The url probably contains "/jira/browse/" now.
3. Click 'User JavaScript and CSS' icon in Chrome (Blue/red dotted lines-icon)
4. Click 'Add new'
5. fill in:
Name: JIRA issue details
URL: replace url by '*/browse/*'
Options: enable JavaScript and JQuery 3
Copypaste this whole script in the JS-pane. Keep CSS pane empty
6. Save
7. Go to JIRA issue and refresh. The copypasteable link should appear now directly under the issue action buttons [Edit | Comment etc].