The .json file (Github API Test - César Rivera Franco.postman_collection.json) located in the folder "Postman_Collection" includes two different folders as requested by assignment "Auth" and "Request".

Folder "Content" contains a file named "API documentation" that includes information about the endpoints used in the test
 
Postman test information:

Auth: Includes a GET endpoint where I test the connection to my personal GITHUB account.

Request: This folder includes five different GET requests to test my personal repository on Github including:

Getrepos: Testing connection to my personal Github account.

Get-Data-Source-API-Analyst-Test: Testing connection repository named Data-Source-API-Analyst requested in the assignment.

TrackIssues: Track issues in the connection to Github API Rest, currently with no issues.

Pagination: I test paginatation endpoint, due to the fact my repository does not includes many information paginitation is not visible.

Rate limit: Fetching ratelimit to Github API which shows different resources related to limit information such as "limit" that displays quantity of request allowed by the API.

Most of the errors I encountered occurred when I setting enviroments variables and adding them to the endpoints requests, the most common error I got was "404 not found" due to incorrect endpoint sintax including enviroment variables.

This assignment was very interesting and help me learn API Testing concepts and troubleshooting using Postman.
