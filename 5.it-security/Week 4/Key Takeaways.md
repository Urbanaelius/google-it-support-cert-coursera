# Network Hardening Best Practices

- Network hardening is securing a network by reducing vulnerabilities through configuration changes and specific steps.
- Best practices for implementing network hardening include disabling unnecessary extra services and restricting access to them.
- Implicit deny is a security principle where anything not explicitly permitted should be denied.
- Monitoring and analyzing network traffic is important to establish a baseline of normal traffic and identify potential attack traffic.
- Analyzing logs is helpful in highlighting potential intrusions, **signs of malware infections**, or atypical behavior.
- Log and analysis systems are best practices for IT support specialists to utilize and implement.
- Alerts are sent to alert security engineers of potential threats.
- Correlation analysis matches events across systems, and detailed logging and analysis can help determine the extent and severity of a breach.
- Splunk is a popular and powerful logs analysis system.
- Flood guards provide protection against DoS or Denial of Service Attacks, ensuring availability of the network


# Network Hardware Hardening

- DHCP is a protocol for assigning configuration information to devices on a network, making it a target for attackers.
- Rogue DHCP server attacks can occur when attackers deploy a fake DHCP server on a network to hand out malicious information.
- DHCP snooping is a feature on enterprise switches that can help prevent rogue DHCP server attacks by monitoring DHCP traffic and mapping IP assignments to physical switch ports.
- Dynamic ARP inspection (DAI) is another feature on enterprise switches that prevents man-in-the-middle ARP attacks by dropping forged gratuitous ARP packets.
- IP Source Guard (IPSG) can be enabled along with DHCP snooping to prevent IP spoofing attacks by dropping packets that don't match IP addresses in the DHCP snooping table.
- 802.1X is an IEEE standard for encapsulating EAP traffic over 802 networks, which can help secure network communication.
- EAP-TLS is a common and secure EAP method that uses TLS to provide mutual authentication of both the client and the authenticating server.
- EAP-TLS requires client-side certificates for authentication.
- HTTPS also uses SSL-TLS cryptographic protocols and can require client-side certificates for authentication.
- Understanding these protocols can help with troubleshooting and securing networks.


# Network software hardening

- Network software hardening techniques are important for securing networks and their traffic for an organization.
- Firewalls are critical to securing a network and can be deployed as dedicated network infrastructure devices or host-based as software that runs on a client system.
- It's recommended to deploy both network-based and host-based firewalls to provide protection for mobile devices and other hosts on the internal network.
- VPNs are commonly used to provide secure remote access and link two networks securely.
- Proxies can be useful to protect client devices and their traffic, provide secure remote access without using a VPN, and can be configured to block content that might be malicious, dangerous, or against company policy.
- A reverse proxy can be configured to allow secure remote access to web-based services without requiring a VPN and can be secured even more by requiring the use of client TLS certificates and specific ACLs.
- Popular proxy solutions that support a reverse proxy configuration include HAProxy, Nginx, and Apache web server.


