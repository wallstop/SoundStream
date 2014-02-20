SoundStream
===========

4/19/14
########
Currently in prototype-only phase.This means that the software has known bugs, known crash causes, etc etc. No warranty is issued of any kind - 

#USE AT YOUR OWN RISK.#

Binary-only atm. Windows-only.

To use:
On the computer that you wish to use as a "sound source", open up a command window where "SoundStream_server.exe" is located, and run the following:
SoundStream_server.exe 192.168.1.2 4444

Where 192.168.1.2 is the IP of the computer that you wish to stream to (local network preferred), and 4444 is the port.
Note: Currently the client defaults to listening on 4444, so make sure you match up the client and server

On the comptuer that you wish to listen from, simply double click "SoundStream_client.exe".
Note: Currently this will only close forcefully.

That's it.

Source coming sometime.
Updates too.
