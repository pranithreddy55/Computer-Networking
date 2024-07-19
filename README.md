# Computer Networking
---

## **Resources**
- [Abhishek Veeramalla's YouTube Channel](https://www.youtube.com/@AbhishekVeeramalla) - The primary resource for learning these concepts.

---
## **DAY 1**

This repository documents my journey through learning the fundamental concepts of Computer Networking, inspired by Abhishek Veeramalla's YouTube series. The goal is to understand key networking concepts, their applications, and practical implications in real-world scenarios.

---

## **Topics Covered**

### 1. IP Addressing
- **IPv4**: Understanding the structure and significance of IPv4 addresses.
- **Classes of IP Addresses**: Overview of classes A, B, C, D, and E, along with their uses.

### 2. Subnets
- **Subnetting**: Techniques for dividing a larger network into smaller, manageable sub-networks.
- **Subnet Masks**: Understanding the role of subnet masks in network identification.

#### Calculating a Subnet Mask
1. **Identify the Network Size**: Determine how many hosts you need in your subnet.
   - For example, if you need 100 hosts, ensure you have enough IP addresses in your subnet.

2. **Choose the Right Subnet**: Use the formula \(2^n - 2\) (where n is the number of bits for hosts) to determine the number of hosts.
   - For 100 hosts: \(2^7 - 2 = 126\) (you need at least 7 bits for hosts).

3. **Determine Subnet Mask**: 
   - Since you need 7 bits for hosts, the remaining bits (32 total bits - 7 bits = 25 bits) will be for the network. In CIDR notation, this is **/25**.

4. **Convert to Dotted Decimal**: Convert /25 to its subnet mask.
   - **/25** corresponds to **255.255.255.128**.

#### Example Calculation
- **Required Hosts**: 100
- **Subnetwork Size Needed**: /25
- **Subnet Mask**: 255.255.255.128

### 3. CIDR (Classless Inter-Domain Routing)
- **CIDR Notation**: Introduction to CIDR and its advantages over traditional IP addressing methods.
- **Subnetting with CIDR**: How to apply CIDR for efficient IP address allocation.

### 4. Ports
- **Understanding Ports**: Importance of ports in networking and their role in enabling communication between devices.
- **Commonly Used Ports**: Overview of well-known ports (e.g., HTTP, HTTPS, FTP, SSH).

---

## **Objectives**
- Develop a solid understanding of how IP addressing works in networking.
- Gain practical experience in subnetting and CIDR.
- Learn the significance of ports and their role in network communication.

---

## **DAY 2**

## **Topics Covered**

### 1. OSI Model
- **Introduction**: Understanding the 7 layers of the OSI model and their functions.

### 2. VPC (Virtual Private Cloud)
- **Concept**: Introduction to VPC and its importance in cloud networking.

### 3. DNS Resolution
- **Process**: Understanding how DNS resolution works, including the role of DNS servers.

### 4. TCP Handshake
- **Mechanism**: Detailed study of the TCP three-way handshake process for establishing a reliable connection.

### 5. Network Components and Concepts
- **Gateway**: Theory and role of gateways in networking.
- **Public Subnet**: Understanding what a public subnet is and its applications.
- **Load Balancer**: Introduction to load balancers and their function in distributing network traffic.
- **Route Tables**: Learning the purpose of route tables and how they manage traffic flow within networks.
- **Security Groups and NACL (Network Access Control Lists)**: Studying the differences and uses of security groups and NACLs in securing network traffic.

---

## **Objectives**
- Develop a comprehensive understanding of the OSI model and its layers.
- Learn the significance of VPCs and their role in cloud networking.
- Gain insights into the DNS resolution process and how it translates domain names to IP addresses.
- Understand the TCP handshake process for establishing network connections.
- Familiarize with key networking components such as gateways, public subnets, load balancers, route tables, security groups, and NACLs, and how they function within a network 
- Explore Network Security Best Practices: Understand key network security principles such as encryption, firewalls, intrusion detection systems (IDS), and intrusion prevention systems (IPS), and learn how to apply these practices to protect network infrastructure and data.