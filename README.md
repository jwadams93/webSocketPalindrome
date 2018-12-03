#webSocketPalindrome

Instructions and Testing by Kaiser Clipston

This program takes in a string input over a network and determines if the string is a palindrome or not. If it is a palindrome the string “This is a palindrome!” is returned to the client. However, if the string is found to not be a palindrome the string “This is not a palindrome” is returned. 

 

Pre-requisite: System must be running python 3.7 or newer for successful program execution. 

 

Steps to execute program: 

 

Start the server by running the PalindromeCheckerServer.py file. The command to do this in a command line is “python PalindromeCheckerServer.py” 

By default, if called with no arguments, the server is started on localhost (127.0.0.1) on port 8000. 

If you wish to start the server on a different IP/Port, provide the desired IP and port upon starting the server. (ex. python PalindromeCheckerServer.py 146.20.54.132 1221) 

Start the client from either a different terminal window or a different machine entirely. To start the client connection, type the command, “python PalindromeCheckerClient.py” 

Like before, by default, if called with no arguments, the client will connect to localhost (127.0.0.1) on port 8000. 

Like the server, you can choose which IP or port you would like to connect to by supplying the desired IP or port upon launching the client. (ex. python PalindromeCheckerClient.py 146.20.54.132 1221) 

Once both client and server are online, provide a string through the client window, and send the data to the server by pressing enter. 

The server will respond, notifying the client if the data provided was a palindrome or not and list each string that comes in from the client.


