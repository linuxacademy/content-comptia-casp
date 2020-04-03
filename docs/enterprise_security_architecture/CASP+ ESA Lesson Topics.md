### CASP+ Exam Objective Map

#### Enterprise Security Architecture

##### 1. Analyze a Scenario and Integrate Network and Security Components, Concepts, and Architectures

### Video Lesson 1 

- Physical or Virtual network and security devices (Common Components)
	- **Switch** - Switches facilitate the sharing of resources by connecting together all the devices, including computers, printers, and servers, in a network. Connected devices can share information and communicate through a variety of network protocols.
	- **Router** - While a switch connects multiple devices to create a network, a router connects multiple switches, and their respective networks, to form an even larger network. Routers allow networked devices and multiple users to access the Internet. A router works as a dispatcher, directing traffic and choosing the most efficient route for information, in the form of data packets, to travel across a network.
	- **Firewall** - A firewall is a network security system that monitors and controls incoming and outgoing network traffic based on predetermined security rules. A firewall typically establishes a barrier between a trusted internal network and untrusted external network, such as the Internet.
	- **Wireless Controller** - A network appliance or software that provide centralized security across multiple WAPs (Wireless Access Points).
	- **Proxy** - Hardware or software systems that act as intermediaries between internal resources and internet resources. Procies cache content, provide address anonymity and can filter malicious activity and monitor activity in real time.
	- **Load Balancer** - Load Balancers distribute network requests and their associated traffic across a pool of servers or resources. Load balancers allow multiple servers to appear as one endpoint to their clients. Algorithyms used to distribute traffic include Round Robin, Least Connections, and Source IP Hash.

### Video Lesson 2
- Physical or Virtual network and security devices (Other Components)

	- **UTM** - (Unified Threat Management) : An approach to information security where a single hardware or software installation provides multiple security functions. This contrasts with the traditional method of having point solutions for each security function.
	- **IDS** - (Intrusion Detection System) : An intrusion detection system is a device or software application that monitors a network or systems for malicious activity or policy violations. Any intrusion activity or violation is typically reported either to an administrator or collected centrally using a security information and event management system.
	- **IPS** - (Intrusion Prevention System) : An intrusion prevention system (IPS) is a form of network security that works to detect and prevent identified threats. Intrusion prevention systems continuously monitor your network, looking for possible malicious incidents and capturing information about them.
	Supplemental Source: Good article on the difference between an IDS and IPS may be found at: https://www.varonis.com/blog/ids-vs-ips/

	- **NIDS** - (Network Intrusion Detection System) : Short for network intrusion detection system, NIDS is a system that attempts to detect hacking activities, denial of service attacks or port scans on a computer network or a computer itself. 
	- **NIPS** - (Network Intrusion Prevention System) : An NIPS strongly enforces network security by providing real-time network protection against network vulnerabilities, exploits, and exposures in operating systems, applications, and databases.
	- **INE** - (Inline Network Encryptors) : A device that encrpts network traffic on the fly. As opposed to encryption prior to delivery, INEs encrypt when transmitting across unsecured connections. Often employed by government agencies for classified information. See HAIPE (High Assurance Internet Protocol Encryptor) for related information.
	- **SIEM** - (Security Information Event Management) : SIEM software collects and aggregates log data generated throughout the organization’s technology infrastructure, from host systems and applications to network and security devices such as firewalls and antivirus filters. The software then identifies and categorizes incidents and events, as well as analyzes them.
	- **HSM** - (Hardware Security Module) : Devices that provide key generation and safeguarding services. Through encryption and strong authentication HSMs speed cryptographic functions and can serve in a variety of contexts from small USB (Universal Serial Buss) devices to CA (Cartificate Authority) and SSL/TLS (Secure Socket Layer/Transport Layer Security) Certificates.
	- **MicroSD HSM** - Small HSM cards that plug into the MicroSD ports of small devices. These devices can provide a variety of security functions to devices such as smart phones and tablets.

- Application and protocol-aware technologies
	- **WAF** - (Web Application Firewalls) : A web application firewall filters, monitors, and blocks HTTP traffic to and from a web application. A WAF is differentiated from a regular firewall in that a WAF is able to filter the content of specific web applications while regular firewalls serve as a safety gate between servers.
	- **Firewall** (See prior lesson)
	- **Passive Vulnerability Scanners** :  a Passive Vulnerability Scanner (PVS) is a hybrid tool that combines the sniffing capabilities of a packet sniffer and analyzer with the capabilities of an active vulnerability scanner and an IDS. A packet analyzer and sniffer captures packets from the network for analysis. An active vulnerability scanner probes systems and devices to detect known vulnerabilities. An IDS detects possible intrusion attempts as traffic moves over your network. A PVS can do all of these functions.
	- **DAM** - (Database Access Monitor) : A DAM monitors the transactions and activity of a given database. By focussing on the database layer specific baselines may be detected for normal usage, and when anomalies occur, a DAM can isolate the activity to the database system specifically.

### Video Lesson 4

- Advanced network design (wired/wireless)
	- **Remote access** : It is important to recognize that the physical location of workers affects the number of attack vectors or access points that may exist in a network. On-premise users, as opposed to remote access users, can be managed through physical infrastructure and security mechanisms such as controlled physical access to devices. Remote access calls for segmentation so that remote user traffic may be isolated and analyzed more deeply than perhaps onsite users. The following technologies assist the security practitioner in assuring proper network design and operation.
		- **VPN** : A virtual private network extends a private network across a public network and enables users to send and receive data across shared or public networks as if their computing devices were directly connected to the private network. VPNs may employ tunneling and encryption to provide protected transport. VPNs require authentication and authorization at the time a session is instantiated.
			- **IPSec** - (Internet Protocol Security) : IPSec is a means of securing network traffic. In IPv4 it is achieved through a set of extensions, while native to IPv6. IPSec may be used to encrypt just the data portion of the traffic (transport mode) or the entire transmission (tunnel mode). Authentication headers are used to protect encapsulated payloads.
			- **SSL/TLS** - (Secure Socket Layer/Transport Layer Security) : TLS is a successor to SSL. Both are a means to secure HTTP (HyperText Transfer Protocol) network sessions between clients and servers. SSL become common place and enabled web broweser and servers to establish secure encrypted sessions. It was common to communicate over port 80, and Secure HTTP or HTTPS was established over port 443. Both SSL and TLS utilize key exchange, hasing, and digital signatures to provide integrity, authnticity and confidentiality of data. TLS utilizes certificates to achive protected sessions. 
		- **SSH** - (Secure Shell) : Secure Shell is a means of establishing a client session to a server over port 22 using a terminal emulator. SSH utilizes cryptographic ciphers to establish a secure session with protected data transport. Version 2 of SSH implements key sharing and message authentication codes to ensure security. This means of connection provides a command line interface (CLI) that has proven useful for the administration of servers, routers, firewalls and other infrastructure components.
		- **RDP** - (Remote Desktop Protocol) : RDP is a protocol solution developed to allow desktop systems to establisg a GUI (Graphical User Interface) session on Windows servers and platforms. Typically run on port 3389 the software allows a user to perform commands from a client similar to SSH and Telnet, but in this case with the Windoes point-and-click interface. 
		- **VNC** - (Virtual Network Computing) : VNC is a platform independent graphical desktop-sharing protocol that uses the Remote Frame Buffer (RFB) protocol. VNC is a common solution for support organizations that need to support Windows and Mac OS desktop systems. It is a client/server model that connects the remote system to the server and then uses the frame buffering to recreate the experience on another client. It is not secure by default. Ultra-VNC is a version that supports cryptography.
		- **VDI** - (Virtual Desktop Infrastructure) : VDI provides a mneans to host a virtual instance of a desktop operating system as a guest instance on a server. VDI allows the entire desktop resource to be hosted on the server and is platform independent. The three models of deployment are Centralized virtual desktops, Hosted virtual desktops, and remote virtual desktops. These provide for server hosted, service-provider hosted, and a remote hosted downloaded instance that does not require constant network connections to the server.
		- **Reverse Proxy** : A Reverse Proxy server flips the script on a conventional proxy. Instead of acting as an internediary between the client and the server, a reverse proxy facilitates a user's connection to a server that is typically in a protected network zone and behind a firewall. The reverse proxy maintains the connection with the server, and utilizes authentication and authorization to grant remote access to that server.
	- **IPv4 & IPv6 transitional technologies** : Ultimately IPv6 will replace IPv4, however until then the security features of IPv6 sometimes need to be provided in IPv4 environments as extentions of IPv4 capabilities. The specific transitional capabilities are: 6 to 4, Teredo amd ISATAP Tunneling, Dual IP stack support, and GRE Tunneling. For more information see: https://www.ipv6.com/gateways/ipv6-transition-technologies/
	- Network Authentication Methods
	- 802.1x
	- Mesh Networks
	- Placement of fixed/mobile devices
	- Placement of hardware & applications
- Complex network security solutions for data flow
	- DLP
	- Deep Packet Inspection
	- Data Flow Enforcement
	- Network flow (S/Flow)
	- Data flow diagram
- Secure configuration and baselining of networking and security components
- Software defined networking
- Network management and monitoring tools
	- Alert definition and rule writing
	- Tuning alert threasholds
	- Alert fatigue
- Advanced configuration of routers, switches, and other network devices
	- Transport security
	- Trunking security
	- Port security
	- Route protection
	- DDoS protection
	- Remotely triggering black hole
- Security zones
	- DMZ
	- Separation of critical assets
	- Network segmentation
- Network access control
	- Quarantine/remediation
	- Persistent/volatile or non-existent agent
	- Agent vs. agentless
- Network enabled devices
	- System on a Chip (SoC)
	- Building/home automation systems
	- IP video
	- HVAC controllers
	- Sensors
	- Physical access control systems
	- A/V systems
	- Scientific/Industrial equipment
- Critical infrastructure
	- Supervisory control and data acquisition (SCADA)
	- Industrial control system (ICS)

##### 2. Analyze a scenario to integrate security controls for host devices 

- When to use trusted operating systems
	- SELinux
	- SEAndroid
	- Trusted Solaris
	- Least functionality
- Endpoint security software
	- Anti-malware
	- Anti-virus
	- Anti-spyware
	- SPAM filters
	- Patch management
	- HIPS/HIDS
	- Data loss prevention
	- Host-based firewalls
	- Log monitoring
	- Endpoint detection response
- Host hardening
	- Standard operating environment
	- Configuration baselining and management
		- Application white-listing and black-listing
	- Security group policy implementation
	- Command shell restrictions
	- Patch management
		- Manual
		- Automated
			- Scripting and replication
	- Configuring dedicated interfaces
		- Out of band management
		- ACLs
		- Management interface
		- Data interface
	- External I/O restrictions
		- USB
		- Wireless
			- Bluetooth
			- NFC
			- IrDA
			- RF
			- 802.11
			- RFID
		- Drive mounting
		- Drive mapping
		- Webcam
		- Recording mic
		- Audio output
		- SD port
		- HDMI port
	- File and disk encryption
	- Firmware updates
- Boot loader protections
	- Secure boot
	- Measured launch
	- Integrity measurement architecture
	- BIOS/UEFI
	- Attestation services
	- TPM
- Vulnerabilities associated with hardware
- Terminal services/application delivery services

##### 3. Analyze a scenario to integrate security controls for mobile and small form factir devices to meet security requirements

- Enterprise mobility management
	- Containerization
	- Configuration profiles and payloads
	- Personally owned corporate enabled
	- Application wrapping
	- Remote assistance access
		- VNC
		- Screen mirroring
	- Application content and data management
	- Over the air updates for software and firmware
	- Remote wiping
	- SCEP
	- BYOD
	- COPE
	- VPN
	- Application permissions
	- Side loading
	- Unsigned apps
	- Context aware management
		- Geolocation and Geofencing
		- User behavior
		- Security restrictions
		- Time-based restrictions
- Security implications and privacy concerns
	- Data storage
		- Non-removable storage
		- Removable storage
		- Cloud storage
		- Transfer backup data to uncontrolled storage
		- USB OTG
	- Device loss or theft
	- Hardware anti-tamper
		- eFuse
	- TPM
	- Rooting and jailbreaking
	- Push notification services
	- Geotagging
	- Encrypted instant messaging apps
	- Tokenization
	- OEM carrier Android fragmentation
	- Mobil payment
		- NFC enabled
		- Inductance enabled
		- Mobile wallet
		- Peripheral enabled payments
	- Tethering
		- USB
		- Spectrum management
		- Bluetooth 3.0 & 4.1
	- Authentication
		- Swipe pattern
		- Gesture
		- Pin code
		- Biometric
			- Facial
			- Fingerprint
			- Iris Scan
		- Malware
		- Unauthorized domain bridging
		- Baseband radio/SOC
		- Augmented reality
		- SMS, MMS messaging
- Wearable technology
	- Devices
		- Cameras
		- Watches
		- Fitness devices
		- Glasses
		- Medical sensors & devices
		- Headsets
	- Security implications
		- Unauthorized remote activation/deactivation of device features
		- Encrypted and unencrypted communication concerns
		- Physical reconnaissance
		- Personal data theft
		- Health privacy
		- Digital forensics

##### 4. Security Controls for Various Software Vulnerability Scenarios

- Application security design considerations
	- Secure: by design, default and deployment
- Specific application issues
 	- Unsecure direct object references
	- XSS
	- CSRF
	- Click-jacking
	- Session management
	- Input validation
	- SQL injection
	- Improper error and exception handling
	- Privilege escalation
	- Improper storage of sensitive data
	- Fuzzing and fault injection
	- Secure cookies
	- Buffer overflow
	- Memory leaks
	- Integer overflows
	- Race conditions
		- Time of check and time of use
	- Resource exhaustion
	- Geotagging
	- Data remnants
	- Use of third-party libraries
	- Code reuse
- Application sandboxing
- Secure encrypted enclaves
- Database activity monitor
- Web application firewalls
- Client/Server processing
	- JSON and REST
	- Browser extensions
		- ActiveX
		- Java Applets
	- HTML5
	- AJAX
	- SOAP
	- State management
	- Java script
- Operating system vulnerabilities
- Firmware vulnerabilities

  

