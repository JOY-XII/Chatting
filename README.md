# Chat Server and Client

This repository contains a Python-based chat server and client implementation, where the server listens for connections from multiple clients, and clients can send messages to each other in real-time. The server is capable of handling multiple clients simultaneously and broadcasts messages to all connected clients. The communication can be done using **Netcat** (`nc`).

## Features

- Server can handle multiple clients concurrently.
- Messages from clients are broadcasted to all other connected clients.
- Each client can send and receive messages in real-time.
- Clients and server use **Netcat** (`nc`) for communication.

## Requirements

- Python 3.x
- Netcat 

## Installation

### Server

1. Clone this repository to your local machine:
   ```bash
   apt update
   apt upgrade -y
   pkg install python -y
   pkg install git -y
   pkg install netcat-openbsd
   git clone --depth=1 https://github.com/JOY-XII/Chatting.git
   cd Chatting
   python main.py
   ```
# PREVIEW 

   
   
