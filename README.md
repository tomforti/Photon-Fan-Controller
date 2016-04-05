# Photon-Fan-Controller
Use of Photon to control hampton bay fan remote via smartthings

To set up 
1. Put the INO code on your Photon
2. Put the Groovy code as a device type on smartthings
3. Add a new deivce and use the newly made device type
4. In preferences of the new device add you photons token and device ID
5. In preferences tell smartthings which Fan it will control.
6. Code is all setup for use with eagle fan board see zip file for eagle board. 

Just a note with this. When I installed my fans i had turned all the dip switches ON. 
So 
Fan 1 is Pin 1-4 on
Fan 2 is pin 1 off and 2-4 on
Fan 3 is pin 1 on, 2 off, 3-4 on
Fan 4 is pin 1-2 on, 3 off, 4 on

Cat5 cable layout
1-Pin1
2-Pin2
3-Pin3
4-Fan Off
5-Fan Low
6-Fan Med
7-Fan High
8-Ground

When soldering up the remote to the cat5 cable to the pins pin 1-3 need to be off and pin 4 needs to be on
