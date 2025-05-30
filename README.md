1. Opened the Windows Advanced Firewall Rules on Windows.
2. On the Firewall there is Inbound rules
3. On the Inbound rules there added a new rule to block the port 23 (Telnet)
4. After it is verified using the Powershell terminal on running the command "Test-NetConnection -Port 23 -ComputerName 127.0.0.1"
5. After verification created a new rule to allow port 22 (SSH)
6. Then, the block rule is deleted to restore the settings.
