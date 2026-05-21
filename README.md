# Advanced DNS Security Lab

This project demonstrates advanced DNS security implementation on Windows Server 2022 in a simulated enterprise environment.

The environment was designed to provide secure DNS services for both internal (INTRANET) and external (INTERNET) users using Split-Horizon DNS and DNS Policies.

The project focuses on improving DNS security, availability and traffic control in a corporate infrastructure.

---

# Architecture

<img width="603" height="345" alt="topology" src="https://github.com/user-attachments/assets/124d0e76-7bab-441f-b96d-c57073b9245d" />

---

# Technologies Used

- Windows Server 2022
- DNS Policies
- Split-Horizon DNS
- DNSSEC
- PowerShell
- Wireshark

---

# DNS Infrastructure

## DNS Zones

<img width="818" height="188" alt="dns-zones" src="https://github.com/user-attachments/assets/773e6a9d-f918-4c92-b313-31c874c10487" />

## DNS Client Subnets

<img width="570" height="104" alt="client-subnets" src="https://github.com/user-attachments/assets/2bffcdff-71ed-445a-94a1-e781e9c4061e" />

---

# Split-Horizon DNS

## DNS Query Resolution Policies

<img width="1338" height="166" alt="query-policies" src="https://github.com/user-attachments/assets/498732c8-8ddb-44dd-8706-17a552de1914" />

## Internal vs External DNS Resolution

<img width="1141" height="452" alt="Przechwytywanie" src="https://github.com/user-attachments/assets/062d7070-dd12-46da-8b57-e0cd5ea78f97" />


---

# DNS Security Hardening

## Response Rate Limiting (RRL)

<img width="1108" height="269" alt="3" src="https://github.com/user-attachments/assets/16018446-f716-4f7d-a8ff-def09bee2952" />

---

# DNSSEC Implementation

## DNSSEC Signing Keys

<img width="869" height="159" alt="3" src="https://github.com/user-attachments/assets/093e8f5a-9ecc-4de1-ab0e-ffac0f53e0b8" />


---

# DNS Traffic Analysis

## Wireshark DNS Inspection

<img width="1908" height="972" alt="TEST INTERNAL" src="https://github.com/user-attachments/assets/e1e4ebbf-bab5-4b71-a14f-95bb1732a7ca" />


---

# Validation

The implementation was tested using:

- nslookup
- Wireshark packet analysis
- DNS resolution policy verification
- Internal vs External DNS response testing

---

# Documentation

Full project documentation is available in the PDF file:

- [Full Project Documentation](./windows-server-dns-security-lab-FilipMalinowski.pdf)

---

# Author

Filip Malinowski
