23/09/2026
20:37

OFFICE CONNECTIONS

Today I learned more about manually assigning IP Addresses and I will simulate an office building (Mathematics Department) which has the following

5 computers - for staff to use
A Server - To assign the computers with IP Addresses dynamically
A Switch - 

IP SCHEME

Since this is not a large setup we shall use Class C Network as it is the smallest while also providing the network room to grow

Network of choice: 192.168.1.0/24

Mascom Router IP address: 192.168.1.1 (255.255.255.0)
Server IP address static:  192.168.1.100 (255.255.255.0) 

CONFIGURATION OF DCHP
I want to have the server to allow a maximum of 40 users starting from the IP 192.168.1.10
its default gateway will point to the Mascom Router

TESTING
I pinged from Computer 1 to check if the device can communicate with the others and connection was successfull
