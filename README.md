# Network-Scanning-using-Nmap
Network Scanning using Nmap Perform reconnaissance using Nmap 
The first phase where the attacker collects as much information as possible about the target.

Tool:

**Nmap** – Scans networks and identifies open ports and services.

It's a command-line utility primarily used to scan networks, identify hosts, and detect open ports, services, and vulnerabilities.

Mostly Nmap is preinstalled in kali linux, But if it is not used the following command to install the Nmap.

- **sudo apt-get install nmap**

![image](https://github.com/user-attachments/assets/32b79a61-3a51-4b20-abd7-0d8644811071)

- **sudo nmap --help** 

will display the help menu for the Nmap command-line tool

![image](https://github.com/user-attachments/assets/84b741d0-1f70-4db4-a2d0-03b747b81e1f)

- **sudo nmap tagretwebsite.com**

This scan will attempt to identify open ports, running services, and potentially operating system information of the target system. 

![image](https://github.com/user-attachments/assets/461c8ee7-3f4e-4f7d-a659-1f423ceebb41)

**-F** flag use to speed up the scanning process. 

-**sudo nmap -F tagretwebsite.com**

![image](https://github.com/user-attachments/assets/ceb495aa-079c-497f-bcf9-66759dfe7206)

We can also use IP address to do scanning.

- **sudo nmap IP-address**

![image](https://github.com/user-attachments/assets/ac50b45f-3e57-4c66-a7d9-bdfd19d02d29)

If want to scanm the range of Ip addresses

- **sudo nmap IP-address-range**

![image](https://github.com/user-attachments/assets/58be3b82-b8f2-475d-8928-349c5db66ed7)

If you have a list of IP addresses to scan in a file The -iL flag in Nmap is used to specify an input file that contains a list of target hosts or IP addresses to scan.

![image](https://github.com/user-attachments/assets/71e41b6f-78c4-47b6-b874-a8f01884498a)

**-p** use to scan the specific port or number of ports to know which service is running on that port. 

- **sudo namp -p range-of-port targetwebsite.com**

![image](https://github.com/user-attachments/assets/0c129857-ff0f-461f-8d59-e62955d1ad95)

If want to find out the specific service is running on which port.

- **sudo namp -p service targetwebsite.com**

![image](https://github.com/user-attachments/assets/0e1c1ebf-ba83-4d30-aac1-78e7981f918b)

To scan all the ports that are availabe on targeted website

![image](https://github.com/user-attachments/assets/4f4e2f91-78d6-4374-9ad9-efddc79c39ad)


**-A** falg use for aggressive scanning, which provides detailed information about the target.

![image](https://github.com/user-attachments/assets/e17ee0c5-f132-4464-a56c-b9ebb96048e0)

![image](https://github.com/user-attachments/assets/7c904bbc-28a1-491e-9726-801dfcb2d940)






