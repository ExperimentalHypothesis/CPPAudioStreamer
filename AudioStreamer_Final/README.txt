To stream uncompressed .wav files with the AudioClient applicaiton:
====================================================================================
1. Run the AudioServer.exe located in the debug or release folder first. 
====================================================================================
2. Run the AudioClient.exe and if streaming locally enter the IP address 127.0.0.1 when prompted to.
====================================================================================
2a. If streaming from another device then get the server computers IP address by running ipconfig in the command line and then enter this in the AudioClient when prompted to. N.B. Entering the IP incorrectly can lead to the client crashing. 
====================================================================================
3. You will now be presented with a range of self explanatory options to view music or quit, follow as desired. 
====================================================================================
4. When presented with the music enter the number associated with the track you wish
to stream. 
====================================================================================
5. To play the song press 'p' and then if you wish to pause the song press 'a' and to stop the song press 's'. Repeated pauses and plays in one session may lead to the client crashing e.g. 'papapapapapa'. 
====================================================================================
5a. Songs may take a second or two to buffer before playing so this isn't anything to worry about. 
====================================================================================
6. To go back to the main menu from the streaming window in the console press 'x'. 
====================================================================================
7. To use your own .wav files simply paste them into the music folder in either the debug or release folder and rebuild the solution for good measure. 