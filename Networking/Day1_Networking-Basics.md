# Day 1 (Tue, 23 June 2026) - Networking Basics

## Objective

Learn the basic concepts of networking and understand how devices communicate on the internet.

## Topics Learned

###1) IP Address

An IP address is a unique address assigned to a device on a network. Computers use IP addresses to send and receive data.

Example:

* 192.168.1.100 (local IP)
* 8.8.8.8 (public IP)

###2) Domain Name

A domain name is a human-readable name used to identify a website.

Examples:

* google.com
* github.com

Humans use domain names because they are easier to remember than IP addresses.

###3) DNS (Domain Name System)

DNS converts domain names into IP addresses.

Example:

google.com → IP Address

Without DNS, users would need to remember IP addresses for every website.

###4) Ping

The ping command is used to test connectivity between my device and another device/server.

It can show:

* Whether the target is reachable
* Response time
* Packet loss

## Commands Practiced

### Check IP Address

```bash
ip addr
```

### Check Computer Name

```bash
hostname
```

### Test Connectivity

```bash
ping google.com
```

### DNS Lookup

```bash
nslookup google.com
```

## What Happens When I Visit google.com?

1. I enter google.com in the browser.
2. DNS converts google.com into an IP address.
3. The browser connects to that IP address.
4. A request is sent to Google's server.
5. The server responds with the webpage.
6. The browser displays the page.

## Key Takeaways

* Computers communicate using IP addresses.
* Humans use domain names.
* DNS translates domain names into IP addresses.
* Ping helps test network connectivity.
* DNS is required when I do not know the IP address of a website.

## Resources Used

* Cloudflare Learning Center
* NetworkChuck
* TryHackMe Pre-Security Path

## Day 1 Status

Completed ✅
