macys
=====

scripts I use at dayjob

train.py        - Notifies me when bart train departs my local train stop in 6 minutes(must have Growl installed)
checkEnvExpire.sh - Parses webpage for days left to expire, if it's under 6 it will notify me (must have Growl installed)
triggerBrightsBuild.py - Uses JenskinsAPI to automatically start a Jenkins job.
sendMessageToSkype.py - Send text message to a Skype chat room
getWSSGVersion2.py - post json to rest api. I use this to verify the artifact version number.
BuildWatch.py - Monitors a webpage for specific text.  Notifies via growl popup message.
heartBeat.py - pings and checks http response codes, if a server is offline it notifies.
latestVersions.sh - Returns version numbers from Hudson's 'last successful build' url
RAPADlogin.py - Selenium to automate logging in to a website.
harvestGmails.py - Searches imap for subject title, parses email body w/ regex, adds to google spreadsheet doc
scrapeHtmlLinks2.py - Uses beautifulsoup to scrape html links from webpage
setIPsforEnv.sh - sets environment variiables of IPs for environment specified as argument 1  via command line
hoursPlus.py    - Displays X amount of time from current time (used to calculate when env will be back up)

