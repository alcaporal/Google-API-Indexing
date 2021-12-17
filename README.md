# Google-API-Indexing

Send requests to Google APIs.

The code takes in input, a character vector of maximum 200 URLs and returns in a data frame the response of the API (see the screenshot below).

You can use the script to update or delete pages. You just have to change the line 38:

Use type = “URL_UPDATED” if you have to update the page
Use type = “URL_DELETED” if you have to remove the page
