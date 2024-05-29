---
permalink: /
title: "Research Overview"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am with the Ministry of Education Key Laboratory for Intelligent Networks and Network Security, School of Cyber Science and Engineering, Xi’an Jiaotong University, Xi'an. I am also working at AFEU, Xi'an. My research interests include Cyber Physical System/Internet of Things Security, AI and Security, Physical Layer Security, and so on. I am an editor of IET Information Security and International Journal of Energy Research. 

Email: tianjiwei2016@163.com; jiweitian@xjtu.edu.cn.

The executed attacks includes stealthy False data injection, evil twin, replay, de-authentication, evasion attacks, reinforcement learning to attack a drone swarm, etc.



# Practical Testbed
We have developed a practical testbed for the execution of cyber attacks and designed a system thats capture the cyber data (communication pattern between the drone and ground station) and physical data (physical behavirol characteristics of the drone). It consists of Tello EDU drones, WiFi access point, ALFA AWUS036ACH network adapter, and two computers. 

- Computer-1 mimics a ground station that is used to
monitor and control the swarm of UAVs. This computer
has a number of Python scripts that are used to connect
the legitimate operator to the UAVs, pass commands, and
receive telemetry physical/behavioral data of the UAVs.

- The WiFi access point establishes a connection between
the ground controller (Computer-1) and the two UAVs to
provide smooth communication and control.

- Computer-2 along with the ALFA AWUS036ACH antenna have dual roles. This computer is running Kali Linux that runs software such as Aircrack-ng, Tcpdump, and Wireshark. First, Computer-2 and the antenna are used to collect the cyber features when operating in the monitoring mode. Also, Computer-2 and the antenna can mimic the attacker and launch cyber-attacks on UAV. 

![Testbed](/images/Tello_Inspection.png)


<iframe width="560" height="315" src="https://www.youtube.com/embed/d680G6HrBtQ?si=Wa4FoAwTbEV6jak6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>



The demo video shows a cyber attack on a drone swarm. It depicts how the coordination among the drones disrupts once the attack is launched.
