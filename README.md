# Server_LSA

Technical Guide 

This project consists of 3 components; the Question-Setting Application, the location-based Quiz Application, and the Server. The corresponding repositories are Queastion_LSA, Quiz_LSA, Server_LSA respectively. Besides, this project has also used PostgreSQL/PGAdmin4 to storing data in this project.
Some details about these three repositories will be introduced in the following.

1 Web Application: Question-Setting App
The Queastion_LSA is displayed in a web browser, accessible to the creators/administrators of the project.
Installation Guide
o	Install the “Queastion_LSA” repository by typing: git clone https://github.com/Clover1122/Queastion-LSA.git
o	Before operating this app, httpServer.js needs be run first which will be introduced in the part of Server_LSA.
o	Operating phonegap server in Queastion_LSA directory: "~/code/ Queastion_LSA/uczl203", then type"phonegap serve" to start the phonegap.
o	Using the following URL to load and check the app: http://developer.cege.ucl.ac.uk:31284/
o	To understand how to use this app, please click: http://developer.cege.ucl.ac.uk:31284/UserGuide.html
Technical Information
This app has been inspecting using the following browsers:
o	Google Chrome v66.0.3359.139 (Official Build) (64-bit)
o	Microsoft Edge v41.16299.371.0

2 Mobile Application: Location-Based Quiz app
This quiz application is created specifically for android mobile devices, and the users are required to connect to the UCL VPN network.
Installation Guide
o	Install the 'Quiz_LSA' repository by going on terminal and typing: git clone https://github.com/Clover/Quiz_LSA.git
o	To operate this app - the httpServer.js needs to be run in the background.
o	Go to the Quiz_LSA directory and operate the phonegap server: "~/code/Quiz_LSA/uczl203" and then type "phonegap serve"
o	In one of the specified ports highlighted in the technical information section, use the following URL to load and check the app: http://developer.cege.ucl.ac.uk:31284/
o	To understand how to use this app, please see the user guidance: http://developer.cege.ucl.ac.uk:31284/UserGuide.html
Technical Information
This app has been operated and inspected using the following browsers:
o	Google Chrome v66.0.3359.139 (Official Build) (64-bit)
o	Microsoft Edge v41.16299.371.0
And the mobile operating system mentioned above: Android Marshmallow 6.0.1

3 NodeJS Server: httpServer
The Server_LSA repository consists of server-side code to process, upload/download and store data in both the web and mobile applications. It is a HTTP server used in both Quiz App and Question Setting App. GET and POST commands are used to download and upload the data in Quiz App and Question Setting App.
Installation Guide
•	Install the Server repository by going on terminal and typing: git clone https://github.com/Clover1122/Server_LSA.git
•	Go to the Server directory using the terminal: "~/code/Server"
•	To operate the server, type: "node httpServer.js &". The addition of the '&' allows the server to run in the background.
•	To stop the servers, type: "fg 1" which will display the current running servers and then type :"Ctrl+C".
•	Having run the httpServer.js in the background, navigate to a phonegap app directory e.g. Quiz App, inside the folder “uczl203” and type: phonegap serve
•	Once the phonegap server has been started successfully, check: http://developer.cege.ucl.ac.uk:31284/
•	To stop the phonegap server, press Ctrl+C.
Technical Information
The following port numbers were used in the project and are assigned to each server:
•	HTTP: 30284
•	HTTPS: 31084
•	Phonegap: 31284
•	Code are sourced from: https://github.com/claireellul/cegeg077-week5server/blob/master/httpServer.js ; https://github.com/claireellul/cegeg077-week5app/blob/master/ucfscde/www/js/appActivity.js ; https://github.com/claireellul/cegeg077-week6formcode .

