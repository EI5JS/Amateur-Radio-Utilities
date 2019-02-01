# Amateur-Radio-Utilities
A collection of Amateur Radio utilities. Please read the ReadMefirst file for app details.

I am new to coding. I am coding in Python 3 at the moment.I currently have two Ham Radio related
applications here. One is a completed "Spaceweather" app that tells you the current Spaceweather.
The second is a work in progress, though it works as is. It is currently in two parts, a contact 
logger and a contact database viewer. A third party database editer should be used to edit the db.

These two run flawlessly on my PC. If you run them on yours, they should run jsut as well. Your 
resolution will likely be different to mine so there may be some geometry issues but the code is
well commented and you should be able to tweak the GUI if needed. 

I am working on v2 of the Logbook which will combine the files into one and add database editing
and management functionality. 

I would be very grateful if you could send any tips and improvements back to me so I can improve 
these apps and my coding in general.

_________________________________________________________________________________________________


The following are updated details of how the Amateur Radio apps should be run:




EI5JS Spaceweather:

The space weather app requires Python 3 to be installed on the PC. When run, it reads the current 
noaa.txt document from the NOAA website and presents it in a small window showing the Ap, Kp, 
solar flux index, the time the document was uploaded by NOAA (usually no older than 3 hours) and 
whether Solar Storm alerts exist. Clicking the Solar Storm line opens Spaceweather.com in your browser.
Because the Window is so small, geometry should not be an issue. Changes can be easily made to the code
as it is well commented. Bear in mind this was my first attempt at coding which runs flawlessly on my 
PC and should run flawlessly on yours. 





EI5JS Logbook v1:

This is v1 of what will eventually be a very nice, elegent and efficient logbook. Currently the code
is in two files. The first is the contact input screen (EI5JS Logbook v1) which has save, clear and logbook buttons.
Save creates a database (.db) file if none already exists and saves the contact information in there. 
The second file (Logbook) opens the database and presents the contacts in a viewer screen. A button
under the log entries called "Edit contacts in DB Viewer" does just that. It opens the database in 'DB Viewer
for SQLite' for editing and management as needed. Therefore, DB Browser for SQLite needs to be installed.  

Version 2 of this app will include logbook editing but for now it is limited to logging and log viewing.
DB Browser for SQLite is used for logbook editing for now.

Requirements:  Python 3 and DB Browser for SQLite from https://sqlitebrowser.org



John Clavin   |   EI5JS   |   February 2019




