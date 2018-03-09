# TCP 
# This program is used to send information between client and server in TCP Connection using socket programming
# Steps below are instructions on how to run the program (Mac OS Terminal was used to run this code)

Step 1. Open two terminal windows
Step 2. Go to the location of the files on both terminals e.g. Terminal 1: cd desktop/lab1-010576072/TCP 
Step 3. Run the server file first in one terminal : python ./TCP_Server.py (The terminal will show the server is ready and waiting for client connection)
Step 4. Run the client file on the other terminal: python ./TCP_Client.py (The client will request an integer from the user)
Step 5. Type any number. If the number enter is less then 0 the program will output an error message saying it is not a valid integer and it will request a new integer
Step 6. Client sends the integer to the server to square root it and the server sends back the result and the client prints out the result.

Test Case:
Alondras-MacBook-Pro:~ alondracabrera$ cd desktop/lab1-010576072/TCP
Alondras-MacBook-Pro:TCP alondracabrera$ python ./TCP_Server.py
Server is Ready
Server waiting for Connection
Connection Made...Waiting for Data
Integer Recieved: 25
Square Rooting Integer
Calculating result

Alondras-MacBook-Pro:~ alondracabrera$ cd desktop/lab1-010576072/TCP
Alondras-MacBook-Pro:TCP alondracabrera$ python ./TCP_Client.py
Server: localhost, Port: 8000
Type the Integer you want the client to pass:25
Send ing Integer 25
The integer sent was: 25, The result is: 5.0
Finished
