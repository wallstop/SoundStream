SoundStream
===========

4/19/14
Currently in prototype-only phase. This means that the software has known bugs, known crash causes, etc etc. No warranty is issued of any kind - USE AT YOUR OWN RISK.

Binary-only atm. Windows-only.

To use:
On the computer that you wish to use as a "sound source", open up a command window where "SoundStream_server.exe" is located, and run the following:
SoundStream_server.exe _IP_OF_COMPUTER_TO_STREAM_TO_ 4444

Where _IP_OF_COMPUTER_TO_STREAM_TO_ is the IP of the computer that you wish to stream to (local network preferred), and 4444 is the port.
Note: Currently the client will only listen on port 4444, so make sure to enter that exactly.

On the comptuer that you wish to listen from, simply double click "SoundStream_client.exe".
Note: Currently this will only close forcefully.

That's it.

Source coming sometime.
Updates too.
