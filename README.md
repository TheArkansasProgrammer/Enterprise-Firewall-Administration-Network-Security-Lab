
## Overview

Designed and configured a simulated enterprise firewall to secure a segmented network by creating firewall rules for DNS, Web, Email, Database, and VoIP traffic. Implemented Stateful Packet Inspection (SPI), monitored live firewall logs, and validated the configuration through simulated attack scenarios to ensure only authorized traffic was allowed.

**Skills Demonstrated**

- Firewall Administration
- Network Security
- TCP/IP
- Firewall Rule Configuration
- Stateful Packet Inspection (SPI)
- Traffic Filtering
- DNS
- Network Monitoring
- Firewall Logging
- Security Validation

---

## 1. Configured Enterprise Firewall Rules

Configured firewall rules to allow only approved network services while enforcing a default-deny security policy. Rules were created for DNS, Web, Email, Database, and VoIP traffic.

**Image:**

<img width="727" height="281" alt="All Active Rules" src="https://github.com/user-attachments/assets/52ab9905-ea50-4b29-a03b-be7249354fea" />
---

## 2. Created Individual DNS Firewall Rule

Configured a dedicated firewall rule allowing DNS traffic over **UDP Port 53**, ensuring clients could resolve domain names while blocking unauthorized DNS requests.

**Image:**

<img width="522" height="310" alt="All 5 Rules" src="https://github.com/user-attachments/assets/d2ab106b-5497-4c18-9aac-e7d70405c482" />
---

## 3. Validated Legitimate Network Traffic

Verified that approved traffic successfully traversed the firewall. Live firewall logs confirmed DNS, Web, Email, Database, and VoIP communications were functioning as expected.

**Image:**

<img width="724" height="431" alt="FireWall Pass" src="https://github.com/user-attachments/assets/c0e57dec-9aa0-4fa8-a666-82dabce905fc" />
---

## 4. Observed Real-Time Network Traffic

Monitored live network traffic flowing between internal devices and the Internet while firewall policies remained enforced.

This visualization confirms that approved traffic continued through the firewall without interruption.

**Image:**

<img width="215" height="403" alt="Good Traffic" src="https://github.com/user-attachments/assets/b47168ae-a7d1-4a9d-8cc0-26e518637a86" />
---

## 5. Tested Firewall Against Simulated Attacks

Executed simulated attack scenarios to verify that the firewall detected and blocked unauthorized traffic before it reached internal systems.

**Image:**

<img width="716" height="425" alt="Attacks Failing" src="https://github.com/user-attachments/assets/85f778db-46b5-4240-825f-b04c820281c4" />
---

## 6. Final Security Validation

Performed a final validation of the firewall configuration. All configured firewall rules successfully protected the network while allowing legitimate communications.

**Image:**

<img width="363" height="393" alt="Zero Attack Go Through" src="https://github.com/user-attachments/assets/36e9b6a6-9d94-406e-930e-744b4b7e64a4" />
---

## Optional Screenshot

This screenshot demonstrates the firewall successfully blocking multiple attack attempts after all firewall rules were configured.

**Image:**

<img width="950" height="575" alt="Attacks Failing ALL RULES" src="https://github.com/user-attachments/assets/998482fd-3b3b-4d66-979a-7d065b37abb0" />
---

