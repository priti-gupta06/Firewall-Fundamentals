# Firewall-Fundamentals
study how firewall control network traffic and create a simple conceptual firewall policy


Task 17: Firewall Fundamentals

Description

Study how firewalls control network traffic and create a simple conceptual firewall policy.

Objective

To understand network traffic filtering and identify allowed and denied traffic categories.

Introduction

A firewall is a security system that monitors and filters incoming and outgoing network traffic based on predefined security rules. It helps prevent unauthorized access and protects computers and networks.

Key Concepts

1. Firewall

A firewall monitors network traffic and allows or blocks connections according to security rules.

2. Packet Filtering

Packet filtering checks information such as source IP address, destination IP address, protocol, and port number to decide whether to allow or block network packets.

3. Stateful Firewall

A stateful firewall tracks active network connections and checks connection states when deciding whether to allow traffic.

Basic Firewall Policy

Allowed Traffic

- Approved outgoing web traffic.
- DNS queries to approved DNS servers.
- Responses belonging to permitted network connections.
- Traffic to approved public services on required ports.

Denied Traffic

- Unauthorized incoming connections.
- Unnecessary or unknown network services.
- Public internet access to remote administration services by default.
- Unauthorized access to firewall management.
- Traffic that is not explicitly permitted by the security policy.

Monitoring

- Record important firewall events.
- Review denied traffic and suspicious connection attempts.
- Regularly review firewall rules.
- Update the policy when network requirements change.

Importance of a Firewall

- Protects networks from unauthorized access.
- Controls incoming and outgoing traffic.
- Reduces unnecessary network exposure.
- Helps monitor suspicious network activity.
- Supports an organization's network security policy.

Interview Questions

Q1. What is a firewall?

A firewall is a security system that monitors and filters network traffic according to predefined rules.

Q2. What is packet filtering?

Packet filtering checks packet details, such as IP addresses, protocols, and port numbers, to allow or block traffic.

Q3. What is a stateful firewall?

A stateful firewall tracks active network connections and considers their state when filtering traffic.

Conclusion

Firewalls are an important part of network security.
A properly planned firewall policy allows necessary traffic, blocks unauthorized connections, and helps reduce security risks.
