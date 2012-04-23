User-Identification-System_Group-6
==================================

User Identification System by Group 6 for EE 579

Group mates:
1. Abhishek Sharma
2. Venkatraman
3. Sneha Patil

Description of project:

In this project, we are creating an User Identification System which will provide seamless interaction between users 
at different locations attending the same meeting independant of their personal contact information. This system will 
just use the name of the attendee. 

In the download folder, we have uploaded two uncompleted code. 

The first one is the server code which will be running on a static server. The server will be the one which will have 
the list of the attendees and it will authenticate the android users according to that list. The server will sent a 
GETINFOMSG  to all the android phones for retrieving their contact info and then it will check it against the users list.
Once the user has been authenticated, the welcome package will be sent to the android phones and then it wait for any
request from the android phones.

The second file contains the code for the androd devices and how they will interact with the seerver. The phones will 
register themselves Mikrotik routers and obtain the Ip address. Then once the user start the application, the phone
will wait for the welcome package from the server. in the background, the phone is establishing a cliet connection 
with the server in order to get itself authencicated, send its contact info and then proceed to view the attendees
list (only names).

We still in the process of developing the full functionality and we believethat we will be able to setup the 
fully functional app pretty soon. 
