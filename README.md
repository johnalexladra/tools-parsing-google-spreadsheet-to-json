# parsing-google-spreadsheet-to-json
Parse Google Spreadsheet to JSON with JavaScript

### Create a Google Spreadsheet: 

The Spreadsheet URL will look like this: `https://docs.google.com/spreadsheets/d/<ID>/edit#gid=0`

Sample: https://docs.google.com/spreadsheets/d/1eLuYSUbzx9Fx-DYYzxGeB_SUdRDc_XOrHgorAjKLK6I/edit#gid=0

Note that the id of this spreadsheet is *1eLuYSUbzx9Fx-DYYzxGeB_SUdRDc_XOrHgorAjKLK6I*

### Share the spreadsheet if others will collaborate on the document

The sharing permissions affect the viewing/editing of the spreadsheet.  To programmatically access the data in the spreadsheet, publish the spreadsheet.  Note that published spreadsheet data is accessible regardless of the sharing settings.

### Publish the spreadsheet

The Published URL will look like this: `https://docs.google.com/spreadsheets/d/<ID>/pubhtml`

Sample: https://docs.google.com/spreadsheets/d/1eLuYSUbzx9Fx-DYYzxGeB_SUdRDc_XOrHgorAjKLK6I/pubhtml

### Access the data in the spreadsheet as XML/RSS

The Published RSS URL will look like this: `https://spreadsheets.google.com/feeds/cells/<ID>/od6/public/values`

Sample: https://spreadsheets.google.com/feeds/cells/1eLuYSUbzx9Fx-DYYzxGeB_SUdRDc_XOrHgorAjKLK6I/od6/public/values

### Access the data as JSON feed

The Published JSON URL will look like this: `https://spreadsheets.google.com/feeds/cells/<ID>/od6/public/values?alt=json-in-script`

Sample: https://spreadsheets.google.com/feeds/cells/1eLuYSUbzx9Fx-DYYzxGeB_SUdRDc_XOrHgorAjKLK6I/1/public/values?alt=json-in-script

### Add a JavaScript callback to process the JSON feed

The Published JSON URL + callback will look like this: `https://spreadsheets.google.com/feeds/cells/<ID>/od6/public/values?alt=json-in-script&callback=doData`

Sample: https://spreadsheets.google.com/feeds/cells/1eLuYSUbzx9Fx-DYYzxGeB_SUdRDc_XOrHgorAjKLK6I/od6/public/values?alt=json-in-script&callback=doData



