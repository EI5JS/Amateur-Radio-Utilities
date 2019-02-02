# Amateur-Radio-Utilities
A collection of Amateur Radio utilities.

I am new to coding. I am coding in Python 3 at the moment. I currently have two Ham Radio related
applications here. One is a completed "Spaceweather" app that tells you the current Spaceweather.
The second is a work in progress, though it works as is. It is currently in two parts, a contact 
logger and a logbook viewer. A third party database editor is used to edit the database.

These two run flawlessly on my PC. If you run them on yours, they should run just as well. Your 
screen resolution will likely be different to mine so there may be some geometry issues but the 
code is easy to understand and you should be able to tweak the dimensions if needed. 

I am working on v2 of the Logbook which will combine the files into one and add database editing
and management functionality. 

I would be very grateful if anyone downloading and running these files could send any tips and 
improvements back to me so I can learn from them and improve the apps as needed.

_________________________________________________________________________________________________

The following are details of how the Spaceweather and Logbook apps should be run:


EI5JS Spaceweather:

The space weather app requires Python 3 to be installed on the PC. When run, it reads the current 
noaa.txt document from the NOAA website and presents the data it in a small window showing the Ap, Kp, 
solar flux index, the time the document was uploaded by NOAA (usually no older than 3 hours) and 
whether Solar Storm alerts exist. Clicking the Solar Storm line opens Spaceweather.com in your browser.
Because the Window is so small, geometry should not be an issue. Bear in mind this was my first attempt 
at coding. It runs flawlessly on my PC and should run flawlessly on yours. 





EI5JS Logbook v1:

This is v1 of what will eventually be a very nice, elegent and efficient logbook. Currently the code
is in two files. 'EI5JS Logbook v1' is the main file and it's the file which should be run. It is a simple
and efficient logging screen. The log viewer file called 'Logbook' is called and run by a button press
on the main Logging screen. Both files therefore should be kept in the same folder. When the Logbook 
viewer is open, all contacts are listed, the last contact at the bottom. There is a button on that screen
called "Edit contacts in DB Viewer". It opens the database in 'DB Viewer for SQLite' for editing and 
management of contacts. Therefore, DB Browser for SQLite needs to be installed.  

Version 2 of this app will include logbook editing and negate the need for DB Browser but v1 is limited
to logging contacts and viewing the logbook.

Requirements:  'Python 3' and 'DB Browser for SQLite' from https://sqlitebrowser.org



John Clavin   |   EI5JS   |   February 2019




