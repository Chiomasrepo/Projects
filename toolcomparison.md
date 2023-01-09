## Penetration Testing Tools Comparison- A Technical Guide

There is a vast number of tools used in cybersecurity and it is almost impossible to keep up with all of them. 
This guide is a comparison of some penetration testing tools used across the industry. There are laws that govern the possession and use of these tools. It is always recommended to abide by the law within your region.

## Penetration Testing Tools

Penetration testing is a simulated attack against a network to uncover vulnerabilities and misconfigurations. There are various stages of a penetration testing and several tools can be used in each phase.

- Phase 1: Information Gathering and Reconnaissance
This involves collecting data and gathering intelligence about the target.
Tools used for this phase include
1. Shodan - https://www.shodan.io/
Shodan  is an open-source project. Shodan is a search engine for internet connected devices. It allows users to conduct searches based on IP address, device name, city etc. It offers both free and paid service.
2. Maltego - https://www.maltego.com/
Maltego is an open-source intelligence tool that is used to aggregate  information from all over the internet. It can be used to gather data linked to person's name such as phone numbers, email addresses, social groups, telephone number etc. 
3. The Harvester - https://www.kali.org/tools/theharvester/
The Harvester comes pre-installed on Kali Linux. It is a tool for gathering sub domain names, email addresses, employee names from different public sources. 

- Phase 2: Scanning and Enumeration
This phase involves the enumeration to determine the open ports on the target system and the versions of application running. One of the most common tools used in this phase is Nmap- https://nmap.org/.
Nmap is a free and open-source network discovery tool that supports a large number of scanning techniques. It has capability for port scanning, OS detection, stealth scanning, service scanning etc. 

- Phase 3: Vulnerability Identification
This phase involves searching for known vulnerabilities for the software/application version which can serve as an entry point into the network for the adversary. Tools that can be used for this phase include
1. Nessus- https://www.tenable.com/products/nessus
Nessus is a vulnerability scanning tool with scan analysis for remediation prioritization. It is a commercial tool but it has the Nessus home which is a free version for consumers. 
2. OpenVAS- https://www.openvas.org/
 OpenVAS (Open Vulnerability Assessment Scanner) is full featured scanner with capabilities for both authenticated and unauthenticated testing. 

- Phase 4: Exploitation
This phase involves gaining access into the network.  Exploitation frameworks are the next evolution of vulnerability scanners as it enables the users to test and eliminate false positives. Some of which include:
Metasploit- https://www.metasploit.com/
Metasploit is a free and open-source exploitation framework that has the capability to scan for a vulnerability, verify that the system is vulnerable and exploit the vulnerability. It is preinstalled on Kali Linux.

- Phase 5: Post Exploitation
This phase involves activities performed once an initial foothold is gained on the network. It ranges from lateral movement/pivoting, privilege escalation, data exfiltration and maintaining access.  Several tools can be used in this phase, some of them include Metasploit, Empire, Covenant, Cobalt Strike.
1. Empire- https://github.com/BC-SECURITY/Empire/blob/main/README.md
Empire is a Powershell post exploitation tool that can be used to create a script, make connection from the target machine and extract password hashes with Mimikatz. The original project is no longer maintained but a fork was created and can be found in the above link.
2. Covenant- https://github.com/cobbr/Covenant
Covenant is an open-source tool, it is a command-and-control framework that uses the .NET framework to achieve similar results as Empire. It includes a web-based interface that allows multi-user collaboration.
3. Cobalt Strike- https://www.cobaltstrike.com/
This is a commercial adversary simulation tool focusing on post exploitation and covert channels to emulate a quiet long-term embedded actor in a network.


## References
https://www.imperva.com/learn/application-security/penetration-testing/

https://www.sunnyvalley.io/docs/network-security-tutorials/what-is-osint#what-are-the-best-osint-tools

https://www.techtarget.com/searchsecurity/feature/Tenable-Nessus-Vulnerability-Scanner-Product-overview

https://www.openvas.org/

https://www.cobaltstrike.com/

https://www.alpinesecurity.com/blog/empire-a-powershell-post-exploitation-tool/






