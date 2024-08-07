# Incident-Report-Analysis

## Scenario 
As a cybersecurity analyst for a multimedia company offering web design, graphic design, and social media marketing, you experienced a DDoS attack that compromised the internal network for two hours due to a flood of ICMP packets. The incident management team mitigated the attack by blocking incoming ICMP packets, shutting down non-critical services, and restoring critical services. Investigation revealed that the attack exploited an unconfigured firewall, allowing the network to be overwhelmed. To address this, the network security team implemented a firewall rule to limit incoming ICMP packet rates, source IP address verification, network monitoring software, and an IDS/IPS system to filter suspicious ICMP traffic. Your task is to use this event to create a network security improvement plan following the NIST Cybersecurity Framework (CSF), analyzing the event and integrating your findings into a comprehensive security strategy.

### Summary

A multimedia company recently experienced a Distributed Denial of Service (DDoS) attack that compromised its internal network for two hours. The attack caused the network services to stop due to a flood of ICMP packets. The response team blocked the source IP addresses of the incoming ICMP packets and temporarily shut down non-critical services to restore critical ones. An investigation revealed that the attack was facilitated by an unconfigured firewall, allowing the malicious actor to send masses of pings for an extended period.

### Identify

The incident response team identified that the company was under a DDoS attack, specifically an ICMP flood attack. This type of attack sends a large number of ICMP pings to a server, causing bandwidth issues and overloading the network, rendering it incapable of normal operations. The internal network was compromised for two hours, with network resources becoming inaccessible and non-critical services shut down.

### Protect

The team has now configured the firewall to limit ICMP packets and added source IP address verification. They have also implemented network monitoring software for anomaly detection and an IPS/IDS to filter incoming ICMP packets and monitor network traffic flow continuously.

### Detect

With the newly configured firewall and additional IPS/IDS protection, the team can now include this specific area of the overall security posture in their regular monitoring and maintenance activities.

### Respond

The team will deploy automation tools such as SOAR, SIEM, and IPS/IDS for regular updates. They will offer regular seminars and training sessions to prepare for future incidents, including theoretical and practical courses to simulate real-life scenarios. The incident results have been reported to upper management, local authorities, and customers, informing them about the attack. The organization may also engage in crowdsourcing activities to enhance security awareness among employees.

### Recover

The team has restored the compromised internal network to normal operations, bringing all network services back online. The identified unconfigured firewall has been modified and strengthened. Staff, employees, and customers have been informed about the network shutdown caused by the attack. A dedicated team will review, monitor, and update the physical infrastructure to the latest security patches. Critical data asset security, although unaffected, has been further tightened to reduce the attack surface.
