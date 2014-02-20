SoundStream
===========
SoundStream is a Client-Server program that streams whatever sound is playing on one computer to another computer over the network, with as little introduced latency as possible.


4/19/14
------------------
Currently in prototype-only phase.This means that the software has known bugs, known crash causes, etc etc. No warranty is issued of any kind - 

_USE AT YOUR OWN RISK._
It's probably fine.

Binary-only atm. Post Windows Vista only.

To use:
On the computer that you wish to use as a "sound source", open up a command window where "SoundStream_server.exe" is located, and run the following:
```cmd
ssServer.exe 192.168.1.2 4444
```
or
```cmd
ssServer.exe 192.168.1.2
```
Where 192.168.1.2 is the IP of the computer that you wish to stream to (local network preferred), and 4444 is the port.

Note: Currently the client defaults to listening on 4444, so make sure you match up the client and server

On the computer that you wish to listen from, simply double click on "ssClient.exe". If you want to specify a port, navigate to the command window and run:
```cmd
ssClient.exe 4444
```
Where 4444 is whatever port you'd like to listen on.

To close the server, press enter in the command window. Pressing ctrl-c in either the ssClient or the ssServer command window will probably force-close all threads of execution. Worst case, close the windows and go into task manager.


That's it.

Source coming sometime.
Updates too.
