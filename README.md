# Network Configuration Guidelines

## 1. Initial Setup
### Steps:
- Open the provided topology layout.
- Locate your unique IP address in the "IPaddresses" file attached.
- Identify network addresses assigned to you and commence configuration.

## 2. Hosts and Subnetting
### Tasks:
- Find the number of required hosts per subnet from the attached file.
- Each student has a specific count of required hosts per subnet.
- Networks are alphabetically labeled in the "IPADDRESSES" file.

## 3. Routing Configuration
### Recommendations:
- Utilize the appropriate routing method specified for each network block.
- Implement redistribution on routers connecting different blocks.

## 4. Dynamic Host Configuration Protocol (DHCP)
### Instructions:
- Employ DHCP for assigning IP addresses to hosts in EIGRP, OSPF areas 1, 2, and RIP.
- Utilize the "DHCP Server" located in the last block for IP address allocation.

## 5. Variable Length Subnet Masking (VLSM)
### Guidelines:
- Apply VLSM in each network of the topology.
- Remember, four IP addresses are required between two routers.
- Refer to the attached file for host requirements in other networks.

## 6. Network Address Translation (NAT)
### Implementation:
- Implement NAT on Router20 for Network J.
- Use the assigned Private IP Address from the attached file for NAT configuration.

## 7. Web Access Control
### Restrictions:
- Prohibit one PC in Network A from accessing the web server.
- Deny web server access to all hosts in Network D.

## 8. Email Configuration
### Configuration:
- Set up email configuration on hosts in the first block.
- Enable hosts to send emails to each other.
- Explore email configuration independently.

*Note: Ensure to follow the guidelines meticulously and refer to the provided files for accurate IP addresses, subnetting details, and specific network configurations.*

## 9. Table for IP Address
| Public IP       | Private IP      | A-Hosts | B-Hosts | C-Hosts | D-Hosts | E-Hosts | F-Hosts | G-Hosts | H-Hosts | I-Hosts | J-Hosts | K-Hosts |
|-----------------|-----------------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|
| 64.154.214.116  | 192.168.139.243 | 112656  | 22729   | 29488   | 112258  | 18408   | 11968   | 103750  | 68145   | 57400   | 100499  | 16335   |
