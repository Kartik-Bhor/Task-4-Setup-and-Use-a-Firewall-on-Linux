## Task 4: Setup and Use a Firewall on Linux (Kali)

### Objective
To configure and test basic firewall rules using UFW on Kali Linux.

### Tools Used
- UFW (Uncomplicated Firewall)
- Telnet client

### Steps Taken
1. Installed UFW using sudo apt install ufw.
2. Enabled UFW using sudo ufw enable.
3. Listed rules with sudo ufw status numbered.
4. Blocked Telnet port (23) using sudo ufw deny 23.
5. Verified the block using telnet localhost 23.
6. Allowed SSH (port 22) using sudo ufw allow 22 to avoid losing access.
7. Removed the Telnet rule with sudo ufw delete deny 23.
8. Summarized rules using sudo ufw status verbose.

### Firewall Summary
UFW filters traffic by allowing or denying connections based on rules set for ports and IPs. It helps protect systems by controlling which services are reachable.

*Added screenshots as Proof*
