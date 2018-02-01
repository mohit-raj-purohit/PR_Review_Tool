
Run the server by: 

node githubApi.js

I have used the on Node JS and GitHub APIs to identify the PR review comments.
In this user has to fill the GitHub credential and the pull request number and the application gives the pdf generated report about the number of TODOs present in the PR.
For accessing the “GitHub API” and “PDF generation”, I have used the “octonode”  and “pdfkit” node module respectively.

This application completely based on the PR review comments, therefore the PR review comments should start from a ‘TODO:’, so that application can count the same.

