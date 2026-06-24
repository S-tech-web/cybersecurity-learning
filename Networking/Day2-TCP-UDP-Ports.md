# Day 2 - TCP, UDP and Ports

## What is TCP?

TCP (Transmission Control Protocol) is a communication protocol that focuses on reliability.

Before sending data, TCP establishes a connection between the sender and receiver.

Features:

* Reliable
* Error checking
* Data arrives in order
* Slower than UDP

Examples:

* Web browsing
* Email
* File downloads
* SSH

Analogy:
TCP is like sending a registered parcel. The receiver confirms that it arrived safely.

---

## What is UDP?

UDP (User Datagram Protocol) is a communication protocol that focuses on speed.

UDP sends data without checking whether every packet arrives successfully.

Features:

* Fast
* Lightweight
* No connection setup
* No guarantee of delivery

Examples:

* Online gaming
* Video calls
* Live streaming
* DNS queries

Analogy:
UDP is like shouting information to a crowd. It is fast, but you do not know if everyone heard it.

---

## TCP vs UDP

| TCP                          | UDP                        |
| ---------------------------- | -------------------------- |
| Reliable                     | Fast                       |
| Connection-oriented          | Connectionless             |
| Error checking               | Minimal checking           |
| Ordered delivery             | No guaranteed order        |
| Used for websites, downloads | Used for streaming, gaming |

---

## What is a Port?

A port is a logical communication endpoint on a device.

An IP address identifies a device.

A port identifies a service running on that device.

Example:

IP Address:
192.168.1.10

Port:
80

This means:
Web server running on device 192.168.1.10

---

## Common Ports

Port 22  → SSH

Port 53  → DNS

Port 80  → HTTP

Port 443 → HTTPS

---

## Client and Server

Client:
The device requesting information.

Examples:

* Browser
* Mobile app

Server:
The device providing information.

Example:

Browser → Google Server

Request:
"Give me google.com"

Server:
Returns the webpage.

---

## Key Takeaways

* TCP focuses on reliability.
* UDP focuses on speed.
* IP identifies a device.
* Port identifies a service.
* Clients request services.
* Servers provide services.
