---
title: Linux Programming Project
summary: April 2023 - June 2023
date: 2024-10-04
type: docs
featured: true
tags:
    - linux
---

Linux Programming Personal Project for the First Semester of 2023

Developing a program that runs on a Linux operating system

Outline
- Develop server/client processes to request and receive files

Server

- While the server is running, it transmits files requested by clients through IPC-Socket.
- If a non-existent file (or an incorrectly named file) is requested, a failure message is sent.
- The server outputs the requested file to standard output and transmits the file to the requesting client.
- The server must be designed with multi-threading and be capable of handling simultaneous requests from multiple clients.
- There is no separate shutdown routine.

Client

- Upon execution, the client receives the file to request through argv[1].
- It connects to the server, requests a file, and terminates the process when the transfer is complete.
- If a non-existent file (or an incorrectly named file) is requested and a failure message is received from the server, it is printed to standard output, and the client terminates.

### Results Report
{{< icon name="download" pack="fas" >}} {{< staticref "uploads/linux.pdf" >}} Download{{< /staticref >}} Results report.
