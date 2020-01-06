# Lejos EV3 Example Programs:

* TunePlayer.java
This class creates a Thread to play a tune whilst the main Thread counts up on the screen.  
You must download the Trumpet.wav file to your brick to make the music player work.
It is not a standalone program, but can be run inside any other program, for example MainClass.java
* PathFinding.java
This program is a working Navigation example.
* MainClass.java
This program waits for a BlueTooth or USB connection.  It then prints whatever arrives over this connection and also echoes it back to the sender.
It works well with the EV3Sensors Android program, but any simple network connection program (like telnet) will work from a PC as well.
It relies on the TUnePlayer Thread since it (annoyingly) also plays music while it is chatting over the network.
* ClapFilter.java
The clap filter as shown in Worksheet Three. 