HELLO EVERYONE! 
This is my write-up for OverTheWire Bandit Level 14.

WHAT I LEARNED: 
First, I learned about communication using the nc (NetCat) command, It's so interesting because i can communicate with a network service.
Although the challenge itself was simple, it introduced me to an important concept used in networking and cybersecurity.

HOW I SOLVED IT: 
i ran the following command: nc (localhostip) 30000 
and after estabilishing the connection, the service waited for my input.
I entered the password from Level 13-14, and the server
responded with the password for the Level 14-15

WHY IT WORKS?: 
The service was listening on TCP port 30000. Netcat acted as a TCP client, established a connection to that port,
and allowed me to send datadirectly to the service.
After validating the submitted password, the server returned the password for the next level.

KEY CONCEPTS: 

- Netcat (`nc`)
- TCP communication
- Client-server interaction
- Listening services
