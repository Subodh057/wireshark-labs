# Project 4: DNS Tunneling Detection using Wireshark

## Objective

Identify suspicious DNS patterns that may indicate data exfiltration.

---

## Tools

* Wireshark
* nslookup

---

## Activities

Captured DNS traffic from normal browsing and simulated suspicious DNS queries.

---

## Filter Used

dns

---
## MITRE ATT&CK Mapping

* Tactic: Command and Control (TA0011)
    * Technique: Application Layer Protocol (T1071) (DNS-based communication)
* Tactic: Exfiltration (TA0010)
    * Technique: Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol (T1048)

## Observations

* Normal DNS queries were human-readable and random
* Suspicious queries showed repeated structured patterns
* Rapid DNS requests indicated automated behavior

---

## Screenshots

* dns_normal.png
* dns_suspicious_pattern.png
* dns_multiple_queries.png

---

## Conclusion

DNS tunneling can be detected by analyzing unusual query patterns and repeated structured domain names.

