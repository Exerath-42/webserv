# Webserv - C++ HTTP Server

Welcome to the Webserv project! Webserv is a C++ HTTP server designed to introduce you to Object-Oriented Programming (OOP) concepts and the intricacies of web server development. This project serves as an opportunity to delve into HTTP and build a functional HTTP server from the ground up using C++98.

## Introduction

In the Webserv project, you'll explore the world of web servers and HTTP. We've chosen C++ as the programming language because of its close relationship with C and its capacity for OOP. While modern C++ has evolved significantly, we'll stick to the C++98 standard to emphasize core OOP principles.

## Prerequisites

Before you dive into the Webserv project, ensure you have the following prerequisites:

- A C++ compiler (e.g., g++) for compiling your code.
- The `make` utility for managing the build process.
- Basic knowledge of HTTP and web server concepts.

## Getting Started

To begin using Webserv, follow these steps:

1. Navigate to the exercise directory.

   ```
   cd exercise_directory
   ```

2. Compile the exercise using the provided `Makefile`.

   ```
   make
   ```



3. Run the compiled program. Specify the configuration file as an argument.

   ```
   ./webserv <config_file>
   ```
   - Configuration files are located in the `configs` folder.
   - By default, the server will run on `http://localhost:8001`.