# Chat in Terminal via LAN

The Chat in Terminal via LAN project is a Java-based application that allows two computers connected via a LAN cable to communicate and chat with each other through the terminal. This project, developed during high school, provides a simple and non-GUI solution for real-time communication between two connected devices.

## Features

- **LAN Communication**: The application leverages the LAN network connection to establish a communication channel between two computers. It enables users to chat and exchange messages in real-time without the need for internet connectivity.

- **Terminal Interface**: The project utilizes the terminal interface, providing a command-line environment for users to input and display messages. It offers a straightforward and lightweight solution for communication between the client and server machines.

- **Client-Server Architecture**: The project follows a client-server architecture, where one computer runs the client Java file, and the other computer runs the server Java file. This architecture enables bidirectional communication and allows users to take turns sending and receiving messages.

- **Real-Time Communication**: The application ensures instant messaging capabilities, allowing messages to be transmitted and received in real-time. Users can engage in dynamic conversations and experience near-instantaneous communication.

## Usage

1. Connect the two computers using a LAN cable.

2. Compile the Java files on both computers using the Java compiler:
   ```
   javac Client.java
   javac Server.java
   ```

3. Run the server file on one computer:
   ```
   java Server
   ```

4. Run the client file on the other computer:
   ```
   java Client
   ```

5. The terminal interface will prompt users to enter and send messages. Messages sent from one computer will be received and displayed on the other computer's terminal, allowing for seamless chat communication.

## Contributing

Contributions to the Chat in Terminal via LAN project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgements

The Chat in Terminal via LAN project was developed as a high school project, showcasing the developer's skills in Java programming and networking. Special thanks to my school i.e BWBS,Ranchi for providing the opportunity and support to work on this project and gain valuable experience in computer networking and communication.
