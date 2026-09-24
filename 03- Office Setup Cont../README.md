24/09/2026
19:40

OFFICE CONNECTIONS

Continued working on the Maths Department Network as I wanted to add a printer and a Firewall 

Network of choice: 192.168.1.0/24

New Device: Printer
IP Address: 192.168.25

Made it static so that the server does not assign the printer with a new IP

On the Mascom Router I used this command to exclude the IP address from the pool

Router(config)# ip dhcp excluded-address 192.168.1.25

New Device: ASA1 5505 firewall device

Whilst the firewall I have not configured it to the desired security, adding it to simulate the network traffic to be monitored is still worthwhile. To be configured tomorrow
