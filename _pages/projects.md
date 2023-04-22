---
layout: archive
title: "Software Project Development Experience"
permalink: /projects/
author_profile: true
---

<!-- {% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %} -->


- [AutoDrive Challenge II (Penn State Advanced Vehicle Team Object Detection Department)](#autodrive-challenge-ii-penn-state-advanced-vehicle-team-object-detection-department)
- [Software Security](#software-security)
- [Access Control](#access-control)
- [Web Security](#web-security)
- [Network Security](#network-security)
- [Dynamic Memory Allocator](#dynamic-memory-allocator)
- [MiniOS](#minios)
- [Channels (concurrent programming)](#channels-concurrent-programming)
- [2D Drawing Application](#2d-drawing-application)
- [CPU](#cpu)
- [Room Scheduling System](#room-scheduling-system)
- [MDADM Linear Device](#mdadm-linear-device)
- [Iterative Methods Comparison](#iterative-methods-comparison)



## AutoDrive Challenge II (Penn State Advanced Vehicle Team Object Detection Department)

- Explored high-definition (HD) map used in autonomous driving and converted it into a database
- Designed and implemented algorithms based on HD map for the highway challenges in Python and PostgreSQL
- Communicated with other departments to test the correctness and performance of the developed algorithms
- Gave Alpha, Beta, and final prototype presentation and co-authored Statement of the Work Report and Final Report



## Software Security

- Implemented Buffer Overflow, Heap Overflow, Shell Code Injection, and Returned Oriented Programming attacks in C
- Examined how stack changes during a function call and program control flow.



## Access Control

- Programmed an access control reference monitor in C that enforces various Mandatory Access Control (MAC) policies (e.g., Biba Integrity policy, Windows Mandatory Integrity Control (MIC) policy, Low Water-Mark Mandatory Access Control (LOMAC) policy) to protect integrity and confidentiality



## Web Security

- Learned and implemented Structured Query Language (SQL) Injection attack, Cross Site Scripting (XSS) attack, and Cross-site request forgery (CSRF) attack



## Network Security

- Implemented the Secure Shell Protocol (SSH) in C using the OpenSSL library
- Developed a client-server system that provides secure file transfer
- Developed a machine-in-the-middle (MITM) attack - Server Spoofing



## Dynamic Memory Allocator

- Implemented a dynamic memory allocator in C
- Supported malloc, free, realloc, coalesce, split, and mm_init functions
- Wrote a heap checker to check invariants of heap memory
- Utilized a segregated list to keep track of free blocks of different sizes for the best balance of throughput and memory utilization



## MiniOS

- Implemented 4-level user and kernel space page table in C; Integrated dynamic memory allocator into MiniOS



## Channels (concurrent programming)

- Developed a synchronization primitive channel in C
- Used semaphore to implement a buffered channel that supports send, receive, close, destroy, and select functionalities



## 2D Drawing Application

- Wrote a 2D drawing application in Java
- Implemented undo and clear button and a status bar showing the mouse’s current location
- Supported common shapes (e.g., line, oval, rectangle) - filled/unfilled, line width, color, and gradient effect



## CPU

- Designed and implemented a five-stage pipeline CPU using the Xilinx design package for FPGAs with Verilog codes for the R-type, I-type, and J-type instructions



## Room Scheduling System

- Designed a database-driven application with Graphical User Interface (GUI) in Java and SQL for room scheduling with a given date and the number of seats
- Implemented methods to add a room, drop a room, cancel a reservation, check the status by faculty and by date, and add to the waitlist



## MDADM Linear Device

- Built a user-space application in C that manages the storage system with networking features
- Implemented read, write, seek to disk, seek to block functionalities that allows user to interact with multiple disks as one linear device; Developed Least Recently Used (LRU) cache with 89.2% hit rate for random input with 4096 cache entries



## Iterative Methods Comparison

- Compared the convergence rate and accuracy of widely-used iterative methods to solve linear systems, including Newton’s method, Gauss-Seidel method, and successive over-relaxation (SOR) method for linear systems with different entries and dimensions using MATLAB


