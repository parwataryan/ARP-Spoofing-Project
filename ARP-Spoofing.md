# ARP Spoofing (ARP Poisoning)

## 📌 Overview
ARP Spoofing (also known as ARP Poisoning) is a **Man-in-the-Middle (MITM)** attack technique used in local area networks (LAN).  
In this attack, an attacker sends fake ARP replies to associate their MAC address with the IP address of another device (usually the gateway).

---

## 🧠 What is ARP?
**ARP (Address Resolution Protocol)** maps an IP address to a MAC address in a local network.

Example:
- IP: `10.150.65.1`
- MAC: `00-0c-29-b1-59-c9`
<img width="850" height="303" alt="Image" src="https://github.com/user-attachments/assets/bb8ba9f7-48d3-4b20-9cdc-48c4f3f0b050" />

<img width="1063" height="446" alt="Image" src="https://github.com/user-attachments/assets/fef75091-899b-43fd-8298-e65dac7c3579" />
ARP has **no authentication**, which makes it vulnerable.

---

## ⚔️ How ARP Spoofing Works
1. Attacker scans the local network
2. Attacker sends forged ARP replies
4. Victim believes attacker is the router
5. Traffic passes through attacker
6. Attacker can sniff, modify, or block data

 
 Screen Before attack


<img width="1919" height="1079" alt="Image" src="https://github.com/user-attachments/assets/07e6de3d-7d5a-4b9d-a736-3919d45aad94" />
 
 Screenshot after attack


<img width="703" height="982" alt="Image" src="https://github.com/user-attachments/assets/70feb543-8af8-41d4-8f4d-f0933daa0f5a" />
---

## 🎯 Impact of ARP Spoofing
- Packet sniffing
- Session hijacking
- Credential theft
- DNS spoofing
- MITM attacks

---

## 🛡️ Prevention Techniques
- Use **Static ARP entries**
- Enable **Dynamic ARP Inspection (DAI)**
- Use **HTTPS / TLS**
- Monitor ARP tables
- Use IDS/IPS systems

---

## 🧪 Learning Environment
This concept should be practiced only in:
- Virtual labs
- Test networks
- CTF challenges
- Authorized environments

---

## ⚠️ Disclaimer
This repository is created **strictly for educational and ethical purposes only**.  
Any misuse of this knowledge is the sole responsibility of the user.

---


