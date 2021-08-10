# Firewall 

Table of Contents:
- [Firewall](#firewall)
  - [Definition:](#definition)
  - [What is a firewall?](#what-is-a-firewall)
  - [Why are firewalls important?](#why-are-firewalls-important)
  - [What does a firewall do?](#what-does-a-firewall-do)
  - [How does a firewall work?](#how-does-a-firewall-work)
  - [Types of firewalls](#types-of-firewalls)
      - [There are two categories of a firewall:](#there-are-two-categories-of-a-firewall)
      - [Types of firewalls, based on filtering method:](#types-of-firewalls-based-on-filtering-method)
  - [Uses](#uses)

## Definition:
A firewall is a security device that protects networks by monitoring data traffic, filtering, and blocking unauthorized access to private data or a computer using a set of rules.

## What is a firewall?
A firewall is like a barrier between a private internal network and a public network.
The firewall's core purpose is to keep dangerous traffic out.
Along with blocking unwanted traffic, it can also prevent malicious software from infecting the computer.

## Why are firewalls important?
When a computer is accessible by a network, it is prone to cyber-attacks. Cybercriminals can easily gain access to a computer connected to the internet. Without a firewall, they will penetrate the system and gain access to personal or large-scale data, which they might destroy or use as leverage over us.
Firewalls work as a mainline defence mechanism for a network or a computer blocking any unauthorized access.

## What does a firewall do?
As the saying goes:

**``` Your network is as safe as its least protected device. ```**

A firewall should not only be securing the network. It is important to secure all the devices present in a network and ensure that they have the latest OS, applications and security software.
It follows the rules defined in its code or as per the configurations made by the user. Rule sets can be based on several things indicated by packet data, including:
- Their source.
- Their destination.
- Their content.


## How does a firewall work?
A firewall creates a boundary between the public network ( i.e. the internet in general ) and the private network ( i.e. the network it protects). 
It only allows those incoming connections that the rules have configured to be safe. 
A firewall works as a security guard, only trusted sources, or IP addresses are allowed in.
As it inspects, it used pre-configured rules to identify packets as benign or malicious. A packet contains information about themselves separate from the data (body) in a block known as a header. The data from the header is matched with the set of rules for checking allowed( i.e. source and destination).

## Types of firewalls

#### There are two categories of a firewall:
1. Software Firewall:   
    These firewalls are in-built in OS and can distinguish programs from on the OS. These programs thus allow the users to use specific data and channel out data that is not required. 
2. Hardware Firewall:
    A firewall is the one that intervenes between public and private networks, to protect the private network.

#### Types of firewalls, based on filtering method:
1. A **packet-filtering firewall** examines packets in isolation and does not know the packet's context.
2. A **stateful inspection firewall** examines network traffic to determine whether one packet is related to another packet.
3. A **proxy firewall** inspects packets at the application layer of the OSI reference model.
4. A **Next-Generation Firewall (NGFW)** uses a multilayered approach to integrate enterprise firewall capabilities with an intrusion prevention system and application control.

## Uses
- It prevents unwanted incoming content.
- It blocks any unauthorized remote access to the system.
- It blocks indecent and NSFW content based on the user configuration.
- It can filter traffic and alert user to intrusions or any unauthorized attempts.
- It guarantees security based on protocols and IP address
- In addition to this immediate threat defence, it performs necessary logging and audit functions by keeping a record of events which may help to identify patterns and stop future attacks.
