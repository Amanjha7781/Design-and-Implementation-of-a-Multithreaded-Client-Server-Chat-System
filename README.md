 Chat-On  : A Python Based Chat Room

This is a basic yet robust **Python-based Chat Room** project. It is implemented through **Socket Programming** in Python. A server is operated on a defined IP Address and Port, and several clients may connect to it. After connecting, each user is prompted to input a nickname, and then all the messages are broadcasted to the group in real time.

---

  Introduction

 What are Sockets?
Sockets are employed for communication between various computers over a network. We can send and receive messages with the assistance of socket APIs. In this project, sockets are employed to enable several users to chat with one another within a single chat room.

TCP Socket
The chat system is implemented employing **TCP sockets**, which ensure that all the messages will be delivered reliably from one client to another through the server.

---

⚡ Usage

1. Initialize the server with:
   ```bash
   python Server.py
Ensure you verify and modify the IP address and Port number within the script if necessary. It defaults to localhost:5555.

Initialize the client by running:

bash
Copy code
python Client.py
Input your nickname, and you are now ready to chat with other people in the room.

 Features (v1.2)
Admin controls implemented for enhanced management:

Kick: Admin can kick a user out of the chat room.

Ban: Admin can ban a user permanently from joining again.

Minor bug fixes and stability enhancements.

 Demo
Here's a brief demo of the project working:

    

What I Learned
From working on this project, I learned:

How socket programming is done using Python.

Server-side and client-side program difference.

Basics of real-time communication between multiple systems.

How admin functionality such as kick/ban can be done.

Future Improvements
Some things I would like to implement in the future:

Adding a basic GUI interface instead of command line.

Implementing encrypted chat for greater security.

Adding functions like private messaging.

Contribution
If anyone wants to enhance this project, go ahead and fork it, make modifications, and open a pull request. I would love to cooperate.

Contact
Developed and hosted by Aman Kumar Jha
Email: amanjha7781@gmail.com
