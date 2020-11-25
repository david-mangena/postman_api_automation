# postman_api_automation

You can also download the collection file from this repo, then import directly into Postman.

Prerequisites
Postman The collection is for use by the Postman app. Postman is a utility that allows you to quickly test and use REST APIs. 
https://home.openweathermap.org/api_keys API key To use our API, you must have an API key with permissions enabled for which resource you want to use. For instance, for the Metrics endpoints, your API key must have the "Metrics: Read-only" permission.
Usage
The collection is arranged in folders according to the API endpoints.

Almost all requests require a valid Openweathermap API key. 

The collection requests have a placeholder variable called API_KEY for this. This should be set in your Postman environment i.e. outside the collection itself. This should help avoid accidental commits of API keys to repos.

A collection-scope variable BASE_URL points to the usual host https://openweathermap.org/api.

# Getting Starting
Download the files from given repo

Import the files to Postman respectively

Executes the tests by clicking Send 
