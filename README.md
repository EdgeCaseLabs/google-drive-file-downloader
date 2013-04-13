# Google Drive File Downloader

This is a little app that I modified from Google's Javascript Drive examples located at [https://developers.google.com/drive/quickstart-js](https://developers.google.com/drive/quickstart-js)

It's purpose is to automate the downloading of multiple Google Docs uploaded files.


## To use this code…

1. Visit [https://code.google.com/apis/console](https://code.google.com/apis/console) and create a new API Project and enable the Drive API.


1. Under the console's API Access tab, create a new OAuth 2.0 access code. Make sure you have added the correct Auhtorized javasciprt origins.

1. Copy the "Client ID" into the CLIENT_ID var of index.html.

1. I've include the node webserver for easy testing. If you already have node, just…

		$ node web-server.js
	
	Otherwise load up the page on your own webserver.

1. Navigate to [http://localhost:8000/index.html](http://localhost:8000/index.html) and paste in some Google Docs URLs.

1. The files will be downloaded via your browser after you confirm your wish to proceed.