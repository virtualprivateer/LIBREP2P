# LIBRE P2P
---


A project aimed for complete private and secure chatting privacy. No images, No metadata. Synchronous only ("ephemeral by design") texting experience with sha-256 fingerprint comparison and DHE (Diffie-Hellman Ephemeral) handshake before trusting. (Tho, out of band verification will be needed for full
privacy.)

 
 
## How?

The goal is making each device into it's own signaling server (STUN/TURN included for peer discovery) . in wich you are given a public IP (Routed trough TOR) , and a unique ID. 
You will need both in order to connect wit other people, and other people need both to conect to you. 
(Possibly compatible with VPNs)


All messages will be stored on ram, so all you need to do is close the TUI program, and its like you didn't even chat with other people.

---

## About encryption

- User ID's will be created using SHA-256. 
- AES-GCM session keys will be shared using RSA.


