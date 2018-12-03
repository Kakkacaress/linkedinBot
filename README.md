# linkedinBot
A bot that uses selenium to log into your linkedin account, and make connection requests using the suggested page.
Requests everyone on the page, and then repeats that for a specified amount of rounds.
#### One request page is one "round".
All of this is done headlessly, so you can use your computer as you please.
Uses the credentials specified by "creds.txt", and logs all activity into "log.txt". These files must be in the
same folder as "connect.py". 

I have mine running as a cron job, at 5 rounds a day (approx. 65 requests a day).
However, I'd suggest trying it out in your command line first. All output to the logfile logs to terminal as well.

## This program requires the following installs:
  - python 2.7 (prob already have this)
  - geckodriver: https://www.npmjs.com/package/geckodriver
  - selenium: "pip install selenium" (if you don't have pip, get pip)
  
## Account safety:
Haven't been banned or recieved a warning. I've been using it rather intensely. I believe it's safe to use! Enjoy.

#### Update
I am no longer maintaining this project. If some of the element paths are no longer valid - please submit an issue with the correct path and I'll update. Thanks
