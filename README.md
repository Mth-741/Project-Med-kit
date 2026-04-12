# Project-Med-kit V1
A high school project intended  to first place learn about data storing and server/client type communication , an intelligent locker intended to manage medicines from distance providing a personal and specific health care for a group or and individual patient ,the project could reach his potential due to time complication and teammates inefficiency

#What it does
What the project does concretly ?
Not that much but it could have a bigger impact in the future , for now it's a python server using Flask library , basically setting up multiple routes (Flask-cors), it's possible to enter multiple web pages stored in the system  choosen (it's primarly used for raspberry but it can  be adapted ) , coded in html/css , with the client functions managed by javascript component , using http protocol , basic stuff.
There is a login , register , reset password , state (patient) and medic page , state gives the possibility to do absolutely nothing for now , but medic ones permits to save for a registered patient(user) a time for take  and  the name of the medecine.
The medicines are put manually in the locker , the operator knows ( or will know ) where to put it ,  in wich drawer , everything is stocked in a json constantly modified by the server itself 

#Roles
Server : routes instructions , gives and receives data from/to the client in js (POST/GIVE methods),  saves up in the json , coordinates other components like rfid manager or temperature fans (soon coming)
Client : What users sees , web pages html/css , also the script.js that manages the http communication (thanks Fetch utilities)
Rfid   : Script in python used to read rfid tags and send them to the server during registation  procedures
Admin Pannel : script in python used to send instructions to ban an ip , the most inefficient and insecure features so far , good luck 

#about
I'm a high school student , getting warm up  in software engineering and bunch other stuff , like you noticed neither my english is good but you need to start at some point right ? for the V2 i promise i gonna clean up my repo properly :)
