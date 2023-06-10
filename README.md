# statusmonitor
This project uses the pi sense hat to display the status of various systems. 
A system sends status file to the pi that the pi then uses to determine
the color of the LED light associated with that system.  The expected 
frequency of the status file updates is also provided so that the pi can
monitor that the client system is still sending data. 