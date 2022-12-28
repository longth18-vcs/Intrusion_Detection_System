
<div align="center">

```ocaml
" Wellcome to my ebook " 
```

```css

██╗██████╗ ███████╗    ███████╗███████╗███╗   ██╗███████╗ ██████╗ ██████╗ ███████╗
██║██╔══██╗██╔════╝    ██╔════╝██╔════╝████╗  ██║██╔════╝██╔═══██╗██╔══██╗██╔════╝
██║██║  ██║███████╗    ███████╗█████╗  ██╔██╗ ██║███████╗██║   ██║██████╔╝███████╗
██║██║  ██║╚════██║    ╚════██║██╔══╝  ██║╚██╗██║╚════██║██║   ██║██╔══██╗╚════██║
██║██████╔╝███████║    ███████║███████╗██║ ╚████║███████║╚██████╔╝██║  ██║███████║
╚═╝╚═════╝ ╚══════╝    ╚══════╝╚══════╝╚═╝  ╚═══╝╚══════╝ ╚═════╝ ╚═╝  ╚═╝╚══════╝
                                                                                  

                                                                          
                                                                          
[ FROM : longth18_vcs ]
```

</div>



## :fallen_leaf: ‎ <samp>INTRODUCE</samp>

<details>
<summary><b>INTRODUCE</b></summary>
  
* An Intrusion Detection System (IDS) is a system that monitors network traffic for suspicious activity and issues alerts when such activity is discovered. It is a software application that scans a network or a system for the harmful activity or policy breaching. Any malicious venture or violation is normally reported either to an administrator or collected centrally using a security information and event management (SIEM) system. A SIEM system integrates outputs from multiple sources and uses alarm filtering techniques to differentiate malicious activity from false alarms.

* Although intrusion detection systems monitor networks for potentially malicious activity, they are also disposed to false alarms. Hence, organizations need to fine-tune their IDS products when they first install them. It means properly setting up the intrusion detection systems to recognize what normal traffic on the network looks like as compared to malicious activity.

* Intrusion prevention systems also monitor network packets inbound the system to check the malicious activities involved in it and at once send the warning notifications.

* Classification of Intrusion Detection System:
IDS are classified into 5 types:

* Network Intrusion Detection System (NIDS):
Network intrusion detection systems (NIDS) are set up at a planned point within the network to examine traffic from all devices on the network. It performs an observation of passing traffic on the entire subnet and matches the traffic that is passed on the subnets to the collection of known attacks. Once an attack is identified or abnormal behavior is observed, the alert can be sent to the administrator. An example of a NIDS is installing it on the subnet where firewalls are located in order to see if someone is trying to crack the firewall.
* Host Intrusion Detection System (HIDS):
Host intrusion detection systems (HIDS) run on independent hosts or devices on the network. A HIDS monitors the incoming and outgoing packets from the device only and will alert the administrator if suspicious or malicious activity is detected. It takes a snapshot of existing system files and compares it with the previous snapshot. If the analytical system files were edited or deleted, an alert is sent to the administrator to investigate. An example of HIDS usage can be seen on mission-critical machines, which are not expected to change their layout.
* Protocol-based Intrusion Detection System (PIDS):
Protocol-based intrusion detection system (PIDS) comprises a system or agent that would consistently resides at the front end of a server, controlling and interpreting the protocol between a user/device and the server. It is trying to secure the web server by regularly monitoring the HTTPS protocol stream and accept the related HTTP protocol. As HTTPS is un-encrypted and before instantly entering its web presentation layer then this system would need to reside in this interface, between to use the HTTPS.
* Application Protocol-based Intrusion Detection System (APIDS):
Application Protocol-based Intrusion Detection System (APIDS) is a system or agent that generally resides within a group of servers. It identifies the intrusions by monitoring and interpreting the communication on application-specific protocols. For example, this would monitor the SQL protocol explicit to the middleware as it transacts with the database in the web server.
* Hybrid Intrusion Detection System :
Hybrid intrusion detection system is made by the combination of two or more approaches of the intrusion detection system. In the hybrid intrusion detection system, host agent or system data is combined with network information to develop a complete view of the network system. Hybrid intrusion detection system is more effective in comparison to the other intrusion detection system. Prelude is an example of Hybrid IDS.
Detection Method of IDS:

* Signature-based Method:
Signature-based IDS detects the attacks on the basis of the specific patterns such as number of bytes or number of 1’s or number of 0’s in the network traffic. It also detects on the basis of the already known malicious instruction sequence that is used by the malware. The detected patterns in the IDS are known as signatures.
Signature-based IDS can easily detect the attacks whose pattern (signature) already exists in system but it is quite difficult to detect the new malware attacks as their pattern (signature) is not known.

* Anomaly-based Method:
Anomaly-based IDS was introduced to detect unknown malware attacks as new malware are developed rapidly. In anomaly-based IDS there is use of machine learning to create a trustful activity model and anything coming is compared with that model and it is declared suspicious if it is not found in model. Machine learning-based method has a better-generalized property in comparison to signature-based IDS as these models can be trained according to the applications and hardware configurations.
Comparison of IDS with Firewalls:
IDS and firewall both are related to network security but an IDS differs from a firewall as a firewall looks outwardly for intrusions in order to stop them from happening. Firewalls restrict access between networks to prevent intrusion and if an attack is from inside the network it doesn’t signal. An IDS describes a suspected intrusion once it has happened and then signals an alarm.
  
</details>


  ## :blossom: ‎ <samp> INSTALLATION </samp>
<details>
<summary><b>Install IDS on Linux ussing Snort </b></summary>
<summary><b>What is snort </b></summary> 
SNORT is a network based intrusion detection system which is written in C programming language. It was developed in 1998 by Martin Roesch. Now it is developed by Cisco. It is free open-source software. It can also be used as a packet sniffer to monitor the system in real time. The network admin can use it to watch all the incoming packets and find the ones which are dangerous to the system. It is based on library packet capture tool. The rules are fairly easy to create and implement and it can be deployed in any kind of operating system and any kind of network environment. The main reason of the popularity of this IDS over others is that it is a free-to-use software and also open source because of which any user can be able to use it as the way he wants. 
Features: 

+ Real-time traffic monitor
+ Packet logging
+ Analysis of protocol
+ Content matching
+ OS fingerprinting
+ Can be installed in any network environment.
+ Creates logs
+ Open Source
+ Rules are easy to implement
</details>
<details>
<summary><b>Install for Linux </b></summary>
  
* You must enable the Linux WSL feature to use the tool
</details>

</details>

## :herb: ‎ <samp>HOW TO USE</samp>
<details>
<summary><b>USE</b></summary>

* very simple you just need to run the tool with python3
* Enter the time you want to change your IP (/s)
* Enter the number of IPs you need to change
  </details>


