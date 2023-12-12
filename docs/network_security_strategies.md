# Network Security Strategies
## Introduction

Welcome to the "Network Security Strategies" section of this documentation. In this segment, we dive into the vital realm of protecting and safeguarding network infrastructures and data. The world of network security is diverse and complex, encompassing a wide range of practices, theories, and tools designed to combat the ever-evolving landscape of cyber threats.

## Understanding the Fundamentals
Network security is not a one-size-fits-all concept; it involves a layered approach combining multiple strategies to create a robust defense mechanism. Here, we will explore the fundamental strategies that form the backbone of network security, from physical security measures to sophisticated software-based defenses.

## Physical Security Measures
In the "Physical Security Measures" section of our network security documentation, we explore the foundational aspect of safeguarding network infrastructure from physical threats and environmental risks. Physical security is a critical layer in a comprehensive network security strategy, often overlooked in favor of more technical measures. This section discusses various methods and best practices to physically protect network hardware and infrastructure, ensuring the safety and integrity of these critical components.

### Overview
* **Physical Security Importance:** 
Emphasizes why physical measures are crucial in protecting network resources from physical damage, theft, or tampering.

* **Environmental Controls:**
 Details the significance of maintaining optimal environmental conditions for network hardware.

* **Access Control Strategies:** Explores methods to regulate physical access to network resources, preventing unauthorized personnel from gaining access.

### Physical Security Importance

Although physical security is absolutely critical to maintaining network security, it is among the most often forgotten aspects of protecting a network. Physical security is defined as protecting physical access to your network and all network components, such as computers, servers, and routers. Neglecting physical security can result in serious damage.

### **Environmental Controls**

Environmental security controls protect assets from accidental, intentional, and natural events, including fire and water damage or power disruption.

### Access Control
Physical access controls restrict the entry and exit of personnel (and often equipment and media) from an area, such as an office building, suite, data center, or room containing a LAN server. (NIST, 1995)

According to Chapter 15 of SP 800-12: An Introduction to Computer Security published by National Institute of Standards and Technology main strategy for physical security is access control.

Physical access controls should address not only the area containing system hardware, but also locations of wiring used to connect elements of the system, the electric power service, the air conditioning and heating plant, telephone and data lines, backup media and source documents, and any other elements required system's operation.

## Firewalls and Intrusion Detection Systems (IDS)

Delving into the first line of defense in network security.

### What Is a Firewall?

A firewall is a network security device that monitors incoming and outgoing network traffic and decides whether to allow or block specific traffic based on a defined set of security rules.

Firewalls have been a first line of defense in network security for over 25 years. They establish a barrier between secured and controlled internal networks that can be trusted and untrusted outside networks, such as the Internet. 

A firewall can be hardware, software, software-as-a service (SaaS), public cloud, or private cloud (virtual).

### Different types of firewalls

* **Proxy firewall**
An early type of firewall device, a proxy firewall serves as the gateway from one network to another for a specific application. Proxy servers can provide additional functionality such as content caching and security by preventing direct connections from outside the network. However, this also may impact throughput capabilities and the applications they can support.



* **Stateful inspection firewall**
Now thought of as a “traditional” firewall, a stateful inspection firewall allows or blocks traffic based on state, port, and protocol. It monitors all activity from the opening of a connection until it is closed. Filtering decisions are made based on both administrator-defined rules as well as context, which refers to using information from previous connections and packets belonging to the same connection.



* **Next-generation firewall**
Firewalls have evolved beyond simple packet filtering and stateful inspection. Most companies are deploying next-generation firewalls to block modern threats such as advanced malware and application-layer attacks.

According to Gartner, Inc.’s definition, a next-generation firewall must include:

Intelligence-based access control with stateful inspection
Integrated intrusion prevention system (IPS)
Application awareness and control to see and block risky apps
Upgrade paths to include future information feeds
Techniques to address evolving security threats
URL filtering based on geolocation and reputation
While these capabilities are increasingly becoming the standard for most companies, NGFWs can do more.

### Choosing Firewall
Choosing the right firewall for your usage is crucial, as firewalls operate at different layers of the OSI (Open Systems Interconnection) model to meet specific security requirements and needs. Traditional firewalls work primarily at the network layer (Layer 3) to filter traffic based on IP addresses and ports. Advanced versions extend their functionality to the transport layer (Layer 4) for stateful packet inspection and the application layer (Layer 7) for in-depth content inspection. This adaptability enables firewalls to offer nuanced security control, tailoring traffic monitoring and management to various network layers, thereby reinforcing the network's overall security. The choice of firewall should align with the specific security needs of the network it is protecting.

### What is an Intrusion Detection System (IDS)

An intrusion detection system (IDS) is an application that monitors network traffic and searches for known threats and suspicious or malicious activity. The IDS sends alerts to IT and security teams when it detects any security risks and threats.

Most IDS solutions simply monitor and report suspicious activity and traffic when they detect an anomaly. However, some can go a step further by taking action when it detects anomalous activity, such as blocking malicious or suspicious traffic.

IDS tools typically are software applications that run on organizations’ hardware or as a network security solution. There are also cloud-based IDS solutions that protect organizations’ data, resources, and systems in their cloud deployments and environments.

