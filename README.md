Usage
===
* clone the scripts
* ensure you have Python 3 installed (from a windows OS. If you are running from a linux/Mac OSX machine, you may need to twist the script a bit to make it work (due to different new line in the output)
* update config.txt with your workspace information.
* run python linechartgen.py or python piechartgen.py You should have reports like below,
![alt text](https://luohuahuang.files.wordpress.com/2017/12/code_report_1.png)
* for every project you configure in config.txt, you should see the same items as above are generated. *-piechart* is reports in the form of pie chart. *-linechart* is reports in the form of line chart. The date before .html in the names is the date the reports are generated.  *-1-month-ago* means the report is for last last month.

Example
===
* pie chart for project ‘first’ since 1200 months ago (100 years ago… so it means since the init commit)
![alt text](https://luohuahuang.files.wordpress.com/2017/12/code_report_2.png?w=776)
* line chart for project ‘first’ in the past 1 year.
![alt text](https://luohuahuang.files.wordpress.com/2017/12/code_report_3.png?w=776)

Thanks
===
* The javascript to generate reports are from https://canvasjs.com/html5-javascript-pie-chart/ and http://jsfiddle.net/1g23upct/

