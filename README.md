# GistAPI_Postman

The repository got the collection for GistAPI. The GistAPI is the github API, this collection got three test cases to create, list and delete the Gists by showing the result either true or false.

# To get Started

Need to install postman from the url 'https://www.postman.com/downloads/', postman is the open source tool for API testing and validations.
Once Postman is installed, copy the url from the current repository 'https://github.com/pavana1/GistAPI_Postman.git' and click on download.
Collection will be downloaded in your workspace.

# Run the test cases

After downloading the collection. Follow below steps.
1) Go to postman and click on import -> Open API -> select the file from the path downloaded
2) Click on eye button to add the variable, 
    add Variable name as 'Endpoint' and value for Endpoint is 'https://api.github.com/gists'
    add Variable name as 'Token' and value for Token is the personal access token which can be generated from github.
3) Run the collection and check the results, Results should be as per the attachment in issue.

# Generating token from github

1) Login to the github, click on your name on right top corner, dropdown will be displayed.
2) Select the setting option from the dropdown.
3) scroll down until 'Developer Setting', click on 'Developer Setting'.
4) In the left hand section, click on 'Personal access token'
5) Once 'Personal access token' is clicked, click on 'Generate New Token'
6) Provide the Valid note name and select the required checkboxes and click on 'Generate Token'
7) Copy and paste the token generate from above step in postman.
