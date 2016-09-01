# ParseGoogleSheetWithJavascript
Sample Code and Application to Parse a Google Sheet with JavaScript

### Create a Google Spreadsheet: 

The Spreadsheet URL will look like this: `https://docs.google.com/a/georgetown.edu/spreadsheets/d/<ID>/edit#gid=0`

Sample: https://docs.google.com/a/georgetown.edu/spreadsheets/d/1hbHqrnYa4oMUquZcq8WkTJk0kI0t9scGBwro-EH-ALA/edit#gid=0

Note that the id of this spreadsheet is *1hbHqrnYa4oMUquZcq8WkTJk0kI0t9scGBwro-EH-ALA*

### Share the spreadsheet if others will collaborate on the document

The sharing permissions affect the viewing/editing of the spreadsheet.  To programmatically access the data in the spreadsheet, publish the spreadsheet.  Note that published spreadsheet data is accessible regardless of the sharing settings.

### Publish the spreadsheet

The Published URL will look like this: `https://docs.google.com/spreadsheets/d/<ID>/pubhtml`

Sample: https://docs.google.com/spreadsheets/d/1hbHqrnYa4oMUquZcq8WkTJk0kI0t9scGBwro-EH-ALA/pubhtml

### Access the data in the spreadsheet as XML/RSS

The Published RSS URL will look like this: `https://spreadsheets.google.com/feeds/cells/<ID>/1/public/values`

Sample: https://spreadsheets.google.com/feeds/cells/1hbHqrnYa4oMUquZcq8WkTJk0kI0t9scGBwro-EH-ALA/1/public/values

### Access the data as JSON feed

The Published JSON URL will look like this: `https://spreadsheets.google.com/feeds/cells/<ID>/1/public/values?alt=json-in-script`

Sample: https://spreadsheets.google.com/feeds/cells/1hbHqrnYa4oMUquZcq8WkTJk0kI0t9scGBwro-EH-ALA/1/public/values?alt=json-in-script

### Add a JavaScript callback to process the JSON feed

The Published JSON URL + callback will look like this: `https://spreadsheets.google.com/feeds/cells/<ID>/1/public/values?alt=json-in-script&callback=doData`

Sample: https://spreadsheets.google.com/feeds/cells/1hbHqrnYa4oMUquZcq8WkTJk0kI0t9scGBwro-EH-ALA/1/public/values?alt=json-in-script&callback=doData

### View the spreadsheet parsed by JavaScript (display as a simple table)

Example: https://rawgit.com/Georgetown-University-Libraries/ParseGoogleSheetWithJavascript/master/samples/GoogleSpreadsheet.html

Code: https://github.com/Georgetown-University-Libraries/ParseGoogleSheetWithJavascript/blob/master/samples/GoogleSpreadsheet.html

JsFiddle: http://jsfiddle.net/terrywbrady/2ufjmwqu/

### View the spreadsheet parsed by JavaScript (display as a simple table with filters)

Example: https://rawgit.com/Georgetown-University-Libraries/ParseGoogleSheetWithJavascript/master/samples/GoogleSpreadsheetFilter.html

Code: https://github.com/Georgetown-University-Libraries/ParseGoogleSheetWithJavascript/blob/master/samples/GoogleSpreadsheetFilter.html

JsFiddle: http://jsfiddle.net/terrywbrady/op8g6drb/


***
[![Georgetown University Library IT Code Repositories](https://raw.githubusercontent.com/Georgetown-University-Libraries/georgetown-university-libraries.github.io/master/LIT-logo-small.png)Georgetown University Library IT Code Repositories](http://georgetown-university-libraries.github.io/)


