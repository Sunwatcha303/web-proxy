# Web Proxy Lab

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/Sunwatcha303/web-proxy-lab/actions)  

## Description
The Web Proxy Lab is a learning project to implement a multi-threaded, caching web proxy server.

## Installation Instructions
To set up and run the Web Proxy Lab:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Sunwatcha303/web-proxy-lab.git
   cd web-proxy-lab

2. **Install Dependencies**
- A C compiler (e.g., GCC).
- Make utility.

3. **Build the Project**
   ```bash
   make

4. **Assign Ports**

   Use the provided scripts to assign a free port
   ```bash
   ./port-for-user.pl

5. **Run the Proxy**
   ```bash
   ./proxy <port-number>

6. **Clean the Build**
   ```bash
   make clean

## Usage
After starting the proxy, configure your browser or HTTP client to use the proxy. Use the assigned port from Step 4.

## Features
- HTTP request forwarding.
- Multi-threaded processing for concurrent clients.
- Caching of frequently accessed resources.
