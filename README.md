# jira-trigger
A Lambda function that takes a http payload and pops it in a SNS queue

The aim of this is so we can take inputs from a number of different sources ( webhooks ) and route them to the right SNS channel for processing. 
There are a number of systems that need input from web applications that are on perm. 


