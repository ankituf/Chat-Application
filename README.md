# Chat Application
This is our computer networks project for Fall 2016.
Author: Aishwarya Saxena and Ankit Aggarwal

## So what our Chat Application do?
Our console based application aims to form a network to provide basic functionalities of transfering data between the clients.
The data can be any type of file e.g image, music, text, zip files etc.

## How Does it work 
1. Run the ChatServer.java on a terminal using the commands "javac ChatServer.java" followed by "java ChatServer".
2. The Server will start and will wait for the clients to connect.
3. Run the ChatClient.java on a new terminal using the commands "javac ChatClient.java" followed by "java ChatClient".
4. Enter the Unique username and a new directory will get created for that Client.
5. Connect as many use you want by repeating steps 2-4.


## Usage Instructions
1. "BCM Hello World!" this instruction Broadcasts the text message "Hello World!" to all clients.
2. "BCF Hello_World.txt" this instruction Broadcasts the file "Hello_Worls.txt" to all the clients.
3. "UCM Hello World! ClientC" this instruction Unicast the text message "Hello World!" to the client "ClientC". 
4. "UCf Hello World.txt ClientB" this instruction Unicast the file "Hello World.txt" to the client "ClientB". 
5. "BKM Hello World! ClientC" this instruction send the text message "Hello World!" to the all clients except client "ClientC". 
