# HMAC-arduino-uno
In a project to build an android app with android studio 3.2.1  to control door lock over bluetooth with arduino UNO as a door lock controller, the effort is to apply HMAC for user authentication.

Libaries:  
The SHA256 Libraries are taken from https://github.com/simonratner/Arduino-SHA-256 

Example:  
In this test, the example was taken from https://github.com/Cathedrow/Cryptosuite/blob/master/Sha/examples/hmacsha256test/hmacsha256test.pde; 

Changes:  
To get the example working, added Sha256 sha and replace all Sha256 calls to sha calls. Thanks to the help from 
https://arduino.stackexchange.com/questions/65038/hmac-sha256-in-arduino-use-case/65041#65041

Tested on Arduino IDE 1.8.9 as of May 2019. Windows 10 platform.
