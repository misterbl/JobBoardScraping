# JobBoardScraping

The application needs the 'nokogiri' and the "open-uri" to be installed first.
On the command line type:

$ gem install nokogiri

Once nokogiri is install, type:

& gem install open-uri


To scrap the job board for a particular industry, use the name of the industry as parameter
The parameter doesn't need to be written with quotation marks
on your command line, navigate to the folder containing the project and type:

$ rake scrap_jobs[parameter]



Example of task for marketing jobs:

$ rake scrap_jobs[marketing]
