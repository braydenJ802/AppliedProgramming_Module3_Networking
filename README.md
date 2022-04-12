# AppliedProgramming_Module3_Networking

# Overview
This is a small project featuring a client-server model network. The goal of this was to create a simple connection between two computers. Simple messages about a succesful connection will be dsiplayed if a connection is made.

I was only able to connect on the local, internal ip addresss, "127.0.0.1", but the way I did so proves that a network connection was happening though I didn't connect to some other device via the internet. My testing didn't confirm that other connection types were possible, however my base server/client code is robust enough to handle those connections so long as the correct ports and addresses are provided. Everyone would have to supply their own addresses anyway, so I don't think this a major concern.


[Software Demo Video](https://youtu.be/gRTyXrCHCgo)

# Development Environment

* Godot v3.4.4 stable
* AndroidStudio (version: 2021.1.1 Patch 2 for Windows 64-bit)
* OpenJDK (version: jdk-17.0.2+8)

# Useful Websites

* [JDK Installation](https://adoptium.net/?variant=openjdk8)
* [Godot Docs](https://docs.godotengine.org/en/stable/index.html)
* Youtube

# Future Work

* Test connecting more clients than one to this single server (This being a server-client network model, many clients could connect to this server)
* Add communication, or the ability to send data/information through a network
