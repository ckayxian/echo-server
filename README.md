Echo Server
==================

A simple "echo" server.

* The server can automatically return to any client that connects exactly what it receives (it should echo all messages).
* When run the Python script, it will send a message to the server and receive the reply, printing it to stdout.


To Try it Out:
--------------
* Open one terminal while in this folder and execute this command:

  `$ python echo_server.py`
   
* Open a second terminal in this same folder and execute this command:

  `$ python echo_client.py "This is a test message."`
  
The server should print out a message indicating the message that it received from the client, and the client should print out a message indicating that it received the message back from the server.

To Run the Tests:
-----------------

* Open one terminal while in this folder and execute this command:

    `$ python echo_server.py`

* Open a second terminal in this same folder and execute this command:

    `$ python tests.py`
