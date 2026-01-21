# Aero Redis Server

A simple Redis-like server written in C++ to understand
network programming and how Redis commands work internally.

This project was built as a learning exercise using ASIO
for asynchronous TCP communication.

## Features
- Handles multiple clients using async I/O
- Supports basic Redis commands
- Simple in-memory key-value store
- Cross-platform (Windows/Linux/macOS)

## Supported Commands
- SET key value
- GET key
- DEL key
- PING

Server runs on port 6377 by default.

## Build Instructions
Requirements:
- C++ compiler (C++20 or above)
- CMake

Steps:
```bash
mkdir build
cd build
cmake ..
cmake --build .
