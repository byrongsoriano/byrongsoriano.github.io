---
layout: project
type: project
image: img/client_server2.png
title: "Client Server"
date: 2023
published: true
labels:
  - C
  - Socket Programming
  - Data structures and Algorithms
  - TCP/IP
    
summary: "A semester long project that implements a TCP (Transport Control Protocol) developed in EE367L."
---

In this project, I had the opportunity to create both a client and a server which required me to learn socket programming. The server, acting as a responsive entity, patiently awaits requests or commands. Upon receiving a request, it processes the request and promptly returns a thoughtful reply. The client is the counterpart in this dynamic interaction, responsible for initiating requests. As their names imply, their functions closely resemble those of a client and server in a restaurant setting, where the client orders an item, and the server fulfills the request by delivering the chosen item back to the client. Below is a visual representation illustrating this dynamic process. Below is a diagram of the complete implementation of the ClientServer.

<img class="img-fluid" src="../img/client_server_diagram.png">


The most crucial part to making this project work was implementing processes correctly. A process is a running program, which includes
the executable program (or machine program), the CPU and the memory to store data. The “state” of the computer are the values stored in the variables in memory (static global variables, and variables in the heap and stack), and registers in the CPU. Processes also create processes which require system calls to manage these. Some system calls that I used were fork(), exit(), and wait() to name a few. We also implemented pipes which allows for multiple processes to work together. It serves as a memory buffer in the computer that multiple processes can
access. Data is entered and retrieved from the pipe with systemcalls such as read() and write(). Once this was done, we also had to create sockets which are used for communicating between processes on a network. This would establish a connection between machines.

Source: <a href="https://github.com/theVacay/vacay">theVacay/vacay</a>
