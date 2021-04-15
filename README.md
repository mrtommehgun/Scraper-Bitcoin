# Scraper-Bitcoin
Database Advanced Blockchain scraper

## How to use?
Everything will be explained below.


### Pre-requisites
Python version 3

#### In Python3 you will need to have a few modules installed. The pip-commands are listed next tot the module.
	-re: Default with 3.9.4
 	-time: Default with 3.9.4
 	-requests: "pip install requests"
    -BeautifulSoup4: "pip install BeautifulSoup"

#### How it works:
        When you start the program, it gives the highest value BTC transaction and it will write it to a log-file. 
        The program will wait 60 seconds before triggering again. 
        It will output to a console in 2 cases: writing when it has scaped data and when the wait-time is over.

#### How to run?
        cd to the right directory, you can use ls to see the items in your current directory. 
        When you are in the right directory use "python scraper.py" and it will start running.
        
#### Where can I find the log-file?
        The log-file will appear in the same folder as the script. So it is recommended to place the script in a special folder that you can easily find.
        I suggest exporting the content to another file or location. 
        Starting with a fresh file will always look better or you could change the code to add the date and time to the file name in the code
        
#### how to stop the script?
        use "exit()","CTRL+C" or "pkill -f scraper.py"
        
