# sdmx
Python Flask server that converts uploaded csv files to an SDMX file 

There are two files:

app.py: the main Flask app - does a whole lot of checks of the uploaded file. It has to be a CSV or PDF file. 

conv.py: does the main conversion - from CSV to SDMX - fairly simple but does the job. 
