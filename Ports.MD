https://www.youtube.com/watch?v=RDotMcs0Erg

Well-Known Ports (0–1023)
Port Number	Protocol	Service	Description
20	TCP	FTP Data	File Transfer Protocol data transfer
21	TCP	FTP Control	File Transfer Protocol command/control
22	TCP	SSH	Secure Shell for encrypted remote login and file transfer (SCP/SFTP)
23	TCP	Telnet	Unencrypted remote login service
25	TCP	SMTP	Simple Mail Transfer Protocol for sending emails
53	TCP/UDP	DNS	Domain Name System for resolving domain names
67	UDP	DHCP (Server)	Dynamic Host Configuration Protocol (server to client)
68	UDP	DHCP (Client)	Dynamic Host Configuration Protocol (client to server)
69	UDP	TFTP	Trivial File Transfer Protocol
80	TCP	HTTP	Hypertext Transfer Protocol (web traffic)
110	TCP	POP3	Post Office Protocol version 3 (retrieving emails)
123	UDP	NTP	Network Time Protocol for clock synchronization
137-139	TCP/UDP	NetBIOS	NetBIOS services for local network file sharing
143	TCP	IMAP	Internet Message Access Protocol (email retrieval)
161/162	UDP	SNMP	Simple Network Management Protocol
179	TCP	BGP	Border Gateway Protocol for internet routing
194	TCP	IRC	Internet Relay Chat
443	TCP	HTTPS	Secure HTTP (HTTP over TLS/SSL)
445	TCP	SMB/CIFS	Windows file sharing
465	TCP	SMTPS	Secure SMTP for sending emails over SSL
514	UDP	Syslog	System logging protocol
636	TCP	LDAPS	LDAP over SSL for secure directory services
989/990	TCP	FTPS	FTP over SSL/TLS
993	TCP	IMAPS	Secure IMAP (email retrieval over SSL/TLS)
995	TCP	POP3S	Secure POP3 (email retrieval over SSL)
Registered Ports (1024–49151)
Port Number	Protocol	Service	Description
1433	TCP	MS SQL Server	Microsoft SQL database server
1521	TCP	Oracle DB	Oracle database service
1723	TCP/UDP	PPTP	Point-to-Point Tunneling Protocol for VPN
2049	TCP/UDP	NFS	Network File System
2082/2083	TCP	cPanel	cPanel website management
3306	TCP	MySQL	MySQL database service
3389	TCP	RDP	Remote Desktop Protocol
5432	TCP	PostgreSQL	PostgreSQL database service
5900-5901	TCP	VNC	Virtual Network Computing for remote desktop access
5985	TCP	WinRM (HTTP)	Windows Remote Management (HTTP)
5986	TCP	WinRM (HTTPS)	Windows Remote Management (HTTPS)
8000	TCP	HTTP Alt	Alternative HTTP port (commonly used for web servers)
8080	TCP	HTTP Proxy	Alternative HTTP port used for web proxies and servers
8443	TCP	HTTPS Alt	Alternative HTTPS port
9090	TCP	Openfire Admin Console	Admin console for Openfire
Dynamic/Private Ports (49152–65535)
These ports are used for temporary or private connections, often assigned dynamically by the operating system for client-side services (also known as ephemeral ports).

Port Categories by Function
Web Traffic:

80 (HTTP), 443 (HTTPS), 8080 (Alternative HTTP)
File Transfer:

20 (FTP Data), 21 (FTP Control), 69 (TFTP), 989/990 (FTPS)
Email:

25 (SMTP), 110 (POP3), 143 (IMAP), 465 (SMTPS), 993 (IMAPS), 995 (POP3S)
Remote Access:

22 (SSH), 23 (Telnet), 3389 (RDP), 5900 (VNC), 5985/5986 (WinRM)
Databases:

1433 (MS SQL), 1521 (Oracle DB), 3306 (MySQL), 5432 (PostgreSQL)
Networking/Infrastructure:

53 (DNS), 67/68 (DHCP), 161/162 (SNMP), 514 (Syslog), 123 (NTP)
