# Project 3: ARP Spoofing Concept and Detection

## Objective

Understand how ARP spoofing works and how it can be detected using Wireshark.

---

## Tools

* Wireshark

---

## Activities

Captured ARP traffic to observe normal IP to MAC address mapping.

Studied how ARP spoofing manipulates this mapping to redirect traffic.

---
## MITRE ATT&CK Mapping

* Tactic: Credential Access (TA0006)
    * Technique: Adversary-in-the-Middle (T1557)
* Tactic: Collection (TA0009)
    * Technique: Network Sniffing (T1040)

## Observations

* ARP resolves IP addresses to MAC addresses
* Fake ARP replies can associate attacker MAC with router IP
* This leads to traffic interception (MITM)

---

## Screenshots
multiples pictures.

---

## Conclusion

ARP spoofing is a technique used to intercept network traffic by poisoning ARP tables. It can be identified by analyzing abnormal ARP behavior.

