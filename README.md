# webSocketPalindrome
Jake Adams

First, start the server


python PalindromeCheckerServer.py


If called with no arguments, the server is started on localhost (127.0.0.1) on port 8000.

If you wish to start the server on a different ip/port, provide the desired ip and port upon starting the server


python PalindromeCheckerServer.py 146.20.54.132 1221


Next, start the client


python PalindromeCheckerClient.py


Again, if the client is started without arguments, the client connects to local host (127.0.0.1) on port 8000.

Like the server, You can choose which ip or port you would like to connect to by supplying the desired ip or port upon launching 
the client.


python PalindromeCheckerClient.py 146.20.54.132 1221


Once both client and server are online, provide data through the client window, and send the data to the server by pressing enter. 
The server will respond, notifying the client if the data provided was a palindrome or not. 
