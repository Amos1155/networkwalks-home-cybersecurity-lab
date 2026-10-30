Building a Home Cybersecurity Lab Using VirtualBox and Kali Linux

Programme: Networkwalks Virtual Internship
Project: Home Lab Setup
Category: Virtualisation and Network Configuration

1. Introduction

As part of my Networkwalks virtual internship, I completed a practical exercise involving the deployment and configuration of a home cybersecurity lab using Oracle VirtualBox and Kali Linux.

The purpose of this exercise was to establish a virtual environment that could serve as a foundation for practical cybersecurity activities, including network reconnaissance, security testing and vulnerability assessment.

Kali Linux was deployed as the attacking machine, while VirtualBox provided the virtualisation platform and network infrastructure.

2. Project Objectives

The objectives of this project were to:

- Install and configure Oracle VirtualBox.
- Create a NAT Network using the "10.0.0.0/24" subnet.
- Deploy Kali Linux as the attacking machine.
- Configure Kali Linux with the IP address "10.0.0.2/24".
- Establish internet connectivity.
- Enable shared folders between the host and guest operating systems.
- Enable shared clipboard and drag-and-drop functionality.

3. Tools and Technologies

Technology| Purpose
Oracle VirtualBox| Virtualisation platform
Kali Linux| Security testing operating system
NAT Network| Virtual network connectivity
IPv4| Network addressing
VirtualBox Guest Additions| Host-to-guest integration

4. Network Configuration

The following network configuration was implemented:

Parameter| Configuration
Network mode| NAT Network
Network address| 10.0.0.0
Subnet mask| 255.255.255.0
CIDR| /24
Kali Linux IP| 10.0.0.2/24
Default gateway| 10.0.0.1

The NAT Network configuration provides internet access to the virtual machine while allowing communication between virtual machines connected to the same NAT Network.

5. Implementation Process

5.1 VirtualBox Setup

Oracle VirtualBox was used as the base virtualisation platform for creating and managing the virtual machine.

5.2 Network Configuration

A NAT Network was created using the "10.0.0.0/24" subnet.

5.3 Kali Linux Deployment

Kali Linux was installed as the attacking machine within the VirtualBox environment.

5.4 IP Address Configuration

The Kali Linux network interface was configured with the required address:

"10.0.0.2/24"

5.5 Internet Connectivity

Internet connectivity was tested to verify that the Kali virtual machine could access external networks.

5.6 Shared Folder Configuration

The host machine's Downloads folder was configured as a shared folder for file exchange between the host and Kali Linux.

5.7 Clipboard and Drag-and-Drop

Shared clipboard and drag-and-drop functionality were enabled to improve interaction between the host and guest operating systems.

6. Testing and Verification

The following checks were used to verify the lab configuration:

Test| Expected Result
IP address verification| 10.0.0.2/24
Internet connectivity| Successful
DNS resolution| Successful
Shared folder access| Accessible
Shared clipboard| Operational
Drag-and-drop| Operational

7. Project Evidence

Screenshots documenting the VirtualBox setup, network configuration, Kali Linux deployment and connectivity verification are included in the "screenshots" directory.

8. Skills Acquired

Through this practical exercise, I gained experience in:

- Virtualisation and virtual machine management.
- NAT Network configuration.
- IPv4 addressing and subnetting.
- Linux network configuration.
- Network connectivity verification.
- Host and guest operating system integration.

9. Conclusion

This exercise provided practical experience in building a virtualised cybersecurity environment using VirtualBox and Kali Linux.

The completed lab provides a controlled foundation for further cybersecurity learning and authorised security testing.

Scope: All future testing within this environment will be conducted only on systems for which permission has been granted.
Project Evidence

The following screenshots document the configuration, implementation and verification of the home cybersecurity lab.

1. VirtualBox Environment

"VirtualBox Manager" (screenshots/01-virtualbox.jpg)

2. NAT Network Configuration

"NAT Network" (screenshots/02-nat-network.jpg)

3. Kali Linux Network Adapter

"Kali Network Settings" (screenshots/03-kali-network-settings.jpg)

4. Kali Linux IP Address

"Kali IP Address" (screenshots/04-kali-ip-address.jpg)

5. Default Gateway

"Default Gateway" (screenshots/05-kali-default-gateway.jpg)

6. Internet Connectivity

"Internet Connectivity" (screenshots/06-internet-connectivity.jpg)

7. DNS Resolution

"DNS Resolution" (screenshots/07-dns-resolution.jpg)

8. Shared Folder Configuration

"Shared Folder" (screenshots/08-shared-folder.jpg)

9. Clipboard and Drag-and-Drop Configuration

"Clipboard Settings" (screenshots/09-clipboard-settings.jpg)

Additional verification: The shared Downloads folder was successfully accessed from Kali Linux. Bidirectional clipboard sharing and file drag-and-drop were also tested successfully.
