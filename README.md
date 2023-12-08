## A Network Topology designed using Cisco Packet Tracer

I designed this network configuration for the network of three companies, given some constraints. This problem was presented in our CST8288 Final. I am looking to revise and review previous some of my previous course work. The main role was to subnet the IP addresses correctly.

It's an interesting problem demonstrating the concepts of Classless IP Subnetting and using RIPv2 Protocol. I am sharing this working solution so that it might be of help to others looking to learn these concepts with a practical real world example.

# Designed Network


# Problem Statement
Suppose that you are the CEO of a startup which deals with network configuration for various companies. After 100 days of struggle, you have finally received your first assignment to configure the network for three different companies in such a way that all the PCs in each company must be able to communicate with each other as well as with all the PCs of any other company.

The companies are named as CompanyX, CompanyY and CompanyZ.

CompanyX has 5 Rooms with 1 PC in each room.
CompnayY has 3 Rooms with 3 PCs in each room.
CompanyZ has 2 Rooms with 4 PCs in each room.
The IP address that have been assigned are the following IP network addresses to each of the company:

CompanyX: 144.186.96.0/19
Company: 50.152.0.0/15
CompanyZ: 210.98.169.64/26

As part of the agreement, all three companies have asked you to bear the expense of all the switches and routers used to interconnect all the computers in a merged network for three companies and further instructed you that all the PCs in a single room must be on the same sub-network and all the rooms of a single company must be on a different sub-network which will be assigned after sub-netting the assigned network address only for the relevant company (no outside network or the network of other company will be accepted) e.g, each room for CompanyX will be assigned a different sub-network after sub-netting the address of 144.186.96.0/19 only and not any other network address. The companies have further informed you that companies plan to extend the number of their PCs in each room in the future.

You decide to install old switches (Generic Switches in Cisco Packet Tracer) with only three Ethernet ports working out of four and routers (Generic Routers in Cisco Packet Tracer) to configure the network for three companies in such a way that you use as much less routers and switches as possible.

You have also bought the following IP network address for the serial communication between different routers which will be connecting different Inter-Company and Intra-Company subnets. You plan to form the subnets of the following address in order to cater the serial communication between all the routers: Routers Serial Communication: 199.210.121.160/28

# Constraints
You, being very cautious, decide to simulate the topology on Cisco Packet Tracer to optimally design the network considering the number of devices (switches, routers etc.) used to maximize the profit margins of your company. However, you must simulate the topology strictly following the rules and regulations described below:

1- Use Straight-through wires, cross-over cables or Serial DCE wires where necessary and applicable.

2- Use Generic Routers and Generic PCs for your design

3- Use Generic Switches such that you attach only 3 of the 4 available Ethernet Interfaces for a single switch, however, you can attach as many switches as considering optimal design.

4- You have to assign IPs to the PCs using Static IP allocation.

5- Although you have to use GUI of the router to configure its interfaces but you must use CLI of the router to configure the RIPv2 Protocol for Classless Subnet Addressing.

# How to Run
Install Cisco Packet Tracer and then simply open the main file. pkt. The whole network is in working condition. You can check it by sending a packet from one system to another or through using the PING command in the Cisco Packet Tracer.

This solution works for version 6.2 or above of Cisco Packet Tracer.

