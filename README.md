# Seveur and Client TCP 

# TCP Server and Client in Python

This repository contains two Python scripts: `server_TCP.py` and `client.py`. These scripts demonstrate a basic TCP server and client communication setup. They are useful for understanding the basics of TCP socket programming and can be used for educational purposes, network testing, and basic penetration testing scenarios.


## Introduction

The `server_TCP.py` script sets up a simple TCP server that listens for incoming connections and can handle basic communication with a TCP client. The `client.py` script connects to a TCP server and allows for sending and receiving messages.

## Features

- Simple TCP server that listens for incoming connections
- TCP client that connects to the server
- Basic message exchange between server and client
- Configurable server IP and port

## Requirements

- Python 3.11.8 


## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/ahmedargoubi/Serveur-et-client-TCP.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Serveur-et-client-TCP
    ```

## Usage

### Running the TCP Server

1. Open a terminal window.
2. Run the server script:

    ```bash
    python server_TCP.py
    ```

### Running the TCP Client

1. Open another terminal window.
2. Run the client script with the server's IP address and port number as arguments:

    ```bash
    python3 client.py <server_ip> <port>
    ```

    Replace `<server_ip>` with the IP address of the machine running the server and `<port>` with the port number the server is listening on.


