# Project Walkthrough

## 1. Configured Enterprise Firewall Rules

Created firewall rules to allow only approved network services while enforcing a default-deny security policy. Rules were configured for DNS, Web, Email, Database, and VoIP traffic, with Stateful Packet Inspection (SPI) enabled to securely manage established connections.

**Skills Demonstrated**

- Firewall Rule Configuration
- Access Control
- Stateful Packet Inspection (SPI)
- Network Security

![Firewall Rules](images/all-active-rules.png)

---

## 2. Configured DNS Firewall Rule

Created a dedicated firewall rule allowing DNS queries over **UDP Port 53**. This allows internal systems to resolve domain names while preventing unauthorized DNS traffic.

**Skills Demonstrated**

- DNS
- UDP
- Port-Based Access Control
- Firewall Administration

![DNS Rule](images/dns-rule.png)

---

## 3. Validated Legitimate Network Traffic

Verified that approved network traffic successfully traversed the firewall. Live firewall logs confirmed that DNS, HTTP, Email, Database, and VoIP communications were permitted according to the configured security policies.

Examples observed:

- DNS (UDP 53)
- HTTP (TCP 80)
- Email (TCP 25)
- Database (TCP 3306)
- VoIP Traffic

![Traffic Validation](images/firewall-pass.png)

---

## 4. Verified Firewall Traffic Flow

Observed real-time traffic moving through the protected network while the firewall filtered communications between internal networks and the Internet. Legitimate traffic continued normally while firewall policies remained enforced.

**Skills Demonstrated**

- Network Monitoring
- Traffic Analysis
- Firewall Logging
- Enterprise Network Security

![Traffic Flow](images/good-traffic.png)

---

## 5. Tested Firewall Against Simulated Attacks

Executed multiple simulated attack scenarios to verify that the firewall detected and blocked unauthorized traffic before it could reach internal systems.

Examples included:

- Operating System Exploits
- Unauthorized Connections
- Malicious Traffic
- External Attack Attempts

![Attack Simulation](images/attacks-failing.png)

---

## 6. Final Security Validation

Performed a final validation of the completed firewall configuration. The firewall successfully blocked simulated attacks while continuing to allow legitimate network communications.

**Validation Results**

✅ DNS Allowed

✅ Web Traffic Allowed

✅ Database Traffic Allowed

✅ Email Allowed

✅ VoIP Allowed

✅ Unauthorized Traffic Blocked

✅ Simulated Attacks Prevented

![Final Validation](images/zero-attack-go-through.png)
