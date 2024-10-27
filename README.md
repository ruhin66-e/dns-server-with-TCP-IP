Expanding my Networking Knowledge! 

<b>DNS (Domain Name System):</b> DNS servers translate human-readable domain names into IP addresses that computers use to identify each other on the Internet. It’s like the phonebook of the Internet!<br>
<b>TCP/IP (Transmission Control Protocol/Internet Protocol):</b> TCP/IP is the core communication protocol of the Internet. TCP ensures reliable data transfer by breaking data into packets, sending them, and reassembling them. IP handles the addressing and routing of these packets to ensure they reach the correct destination.

First I need 2 pc or laptops
after that take a 2960-24TT switch and 5 pcs server.
one for Facebook server, 2nd one DNS server, 3rd one Google server, 4th one Facebook server and 5th one Skillset server.
then set the IP address 

1st Ruhin PC IP---192.168.1.3
2nd Ikbal PC IP---192.168.1.2
YouTube server IP---192.168.1.240
DNS server IP-------192.168.1.250
Google server IP----192.168.1.100
Facebook Server IP---192.168.1.230
Skillset-bd server IP---192.168.1.220

After setting all IP then go Service on HTTP and edit the index.html file.
then go to DNS set www.youtube.com address:192.168.1.240 click Add button.
Then go to DNS server, and go to service, click DNS option & add www.youtube.com address:192.168.1.240 click Add button.
Then go to Ruhin pc search web browser www.youtube.com
