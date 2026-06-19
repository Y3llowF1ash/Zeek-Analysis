As an analyst at a Security Operations Center (SOC), you check alerts for the past week and find a signature hit for ET MALWARE Lumma Stealer Victim Fingerprinting Activity that triggered on traffic from 153.92.1[.]49 over TCP port 80. The alert triggered on 2026-01-27 at 23:05 UTC.

Using the information, you retrieve a packet capture (pcap) of the traffic from the internal IP address that triggered the alert. Based on the pcap, you write up an incident report, so the incident responders can track down the computer and associated user.

The characteristics of your environment are:

LAN segment range:  10.1.21[.]0/24   (10.1.21[.]0 through 10.1.21[.]255) <br>
Domain:  win11office[.]com <br>
AD environment name:  WIN11OFFICE <br>
Active Directory (AD) domain controller:  10.1.21[.]2 - WIN-LU4L24X3UB7 <br>
LAN segment gateway:  10.1.21[.]1 <br>
LAN segment broadcast address:  10.1.21[.]255 <br>
Malicious_IP: 153.92.1[.]49

Having found a pcap with traffic from the infected host, you are happy to begin reviewing it!

For this exercise, answer the following questions for your incident report:

What is the IP address of the infected Windows client? <br>
What is the MAC address of the infected Windows client? <br>
What is the host name of the infected Windows client? <br>
What is the user account name from the infected Windows client? <br>
What is the full name of the user from the user account? <br>
What is the domain from 153.92.1[.]49 that triggered the alert for Lumma Stealer? <br>

Tool Used: Zeek

Password for PCAP: infected_20260131