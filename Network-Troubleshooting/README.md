Network Troubleshooting – macOS

Project Overview

This project demonstrates basic network troubleshooting techniques using macOS Terminal commands.

The objective was to identify network interfaces, test internet connectivity, and verify DNS name resolution.

Environment

Operating System: macOS

Device: MacBook

Tools: macOS Terminal

1. Network Interface Identification

Command:

ifconfig

Purpose:

To identify active network interfaces and inspect their IP configuration.

Findings:

Identified the active network interface.

Confirmed the local IPv4 address.

Observed additional virtual network interfaces.

2. Internet Connectivity Test

Command:

ping -c 4 8.8.8.8

Purpose:

To test connectivity to an external IP address using ICMP packets.

Results:

Packets transmitted: 4

Packets received: 4

Packet loss: 0%

Average latency: 22.583 ms

Conclusion:

The device successfully communicated with the external IP address, with no packet loss during the test.

3. DNS Resolution Test

Command:

nslookup google.com

Purpose:

To verify whether the DNS resolver could translate a domain name into an IP address.

Results:

Domain queried: google.com

DNS resolution: Successful

Resolved IP address: 172.217.162.206

Conclusion:

The DNS resolver successfully returned an IP address for the requested domain.

Final Assessment

All three diagnostic checks completed successfully.

Network interface identification: Successful

External IP connectivity: Successful

DNS name resolution: Successful

This exercise provided practical experience with basic network diagnostics and troubleshooting using macOS Terminal.
