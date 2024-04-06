# Cybersecurity
Network vulnerability
Tool-hascat(brute force)(password cracking tool)
attack,RAT-Remote Access Trogent(either hardware or software)
Data,resource,securing,safe guard
Physical control,administative control,logical control-safe guard by self 
Port Scanning,OSI layer
Protocol-set of rules
TCP & UDP-65535 TCP ports+65535 UDP Ports(Entry port) 
(https-port 443,http-port 80)
http VS https
Blockchain,Blockchain security
Exploit
SQL injection
Session hyjacking 
phishing 
DNS poisoning 
IP address 
Cloud 
Krpytograph
ARP Poisoning 
hascat cracking 
Metasploit
Backdoor
Ethical hacking-gainig unauthorized data with written permission 
web application-web application security testing
web application-user intraction ,web page-document will be displayed in web browser,web server-host of web site,web site-collection of web pages
opp-=Affensive,deffensive-sos analyist
red team,blue team,purple team(both)
3 types of hackers-white hat,black hat,gray hat
white hat-software architecture
black hat-just a hacker(zero knowledge about a web site)
gray hat-combine of both white hat and black hat
script kiddies
hackthysm-social calls
wikileads
state hackers
BYOD-bring your own device(demand)
CIA-confidentiality . integrity(orginality) . availibility
Aurthentication-3 factors(1.some thing you know,2.some thing you have,3.some thing you are)
Access control(with permission)-UAC 
SSL-secure software layer(integrity)
Encryption-convertion of normal text into cyber text
firewall


format executable in window
.exp,.batch,.sh(windows)
...(edit the envirnomental variable)..
zand server
----(open edit the envirnomental variable--click environmental variable-----click path--click edit--click new--C:\Window\System32\)
same subnet +same ip address=LAN.
jumping into another subnet and ip or more than one subne=WAN
*(ping 172.1.44.44-c 4)     (-c=counts) for linux 
*(ping --help)  
-c=switch 
-n=no.of count 
same n/w devices-cross over 
diff n/w devices-straight over 
two device connected by router
PT-Packet tracer
MAC address-permanent address for device (media access control address) (trace)
ping users ICMP protocol


DHCP--Dynamic Host Configuration Protocol
power shell                         command prompt
linux-ls (listing)                           window-dir
linux-cd(change directory)(cd.\desktop\)back-cd..    front-cd...

et0-ethernet 0
VPN-encrypt B/W CLIENT and SERVER 

Encryption-clear text ->ciper text
Decryption-ciper text->clear text

Tpyes of encryption
-symmetric encrp-single key
-Asymmentric encrp-public key\private key

wireshark is a packet analyiser
3 way handshake***--syn,syn-ack,ack

http-
https-TLS way handshake,asy,

click any one-right click-follow-tcl
diff b/w 


Signature=hash 
virustotal.com----checking the file intergity

Client Request ---> server response --> DB
HTTP methods                    RESPONSE (code) methods
GET                                 1xx- Informational(Protocol changes in inside(informations))
POST                                2xx- OK(Success)
PUT                                  3xx- Redirect 
OPTIONS                              4xx - Client side Error
DELETE                               5xx-Server side Error 

the testing has 3 types of environment :
Production Environment-live website or web application--->(website down problem is there)(risk,highly costly)
Staging Environment-Changes checks or tested -->Actual copy of production environment
QA environment -test enviornment

Burpsuite-b/w client and server -->**proxy**---act as a middle server --proxy can be both good and bad

Tor-Bitcoin 1b-$67000
Darkweb--b\w clent and server--=>   (Client-->Proxy1-->proxy 2-->Proxy3-->proxy 4-->Proxy5-->proxy 6-->SERVER) **located in 6 diff ways**

**burp suite**
open burp suite->proxy_->open browser(user agent)

Foxyproxy--open link-right side up corner--puzzle Symbol--poxies--enter name--enter ip--save--

brupsuite--8080

kali command
*sudo nmcli networking on
sudo service NetworkManager start(sto,restart)*

install after 
file--cat /etc/apt/sources.list---to open file 
nano - to read the file

burpsuite ku traffic ah send pannanum ah  on or we can off

**COMMAND
**sudo service NetworkManager start
sudo service apache2 start
sudo service apache2 status
q
**


Vulnerability Assessment(VA)**--process of identifying--find out potential weakness actually affect CIA--PRIORTIZE(if u find bug)--
it invovles a systematic review of potential weakness


RISK ANAYLSIS:
**VULNERABILITY ASSESSMENT PROCESSS
Assest discovery(we can sacn computer)---Vulnerability scanning  (scanning ALL OS/HOST EG:IOT devices)---Vulnerability Assessment(undering the impact of theards)-----Vulnerability remediation(

**NATIONAL Vulnerability DATABASE-NVD
**CVSS -common Vulnerability Scoring system 
***CVSS SOCORE 
LOW-0.1-3.9
Medium-4.0-6.9
High-7.0-8.9
Critical-9.0-10.0

WINDOW USER-Admin

**Vulnerability Scanner
TYPES:
DATABASE vul.scanner
Network vul.scanner
Web Application vul.scanner
Host-Based vul.scanner
API-based vul.scanner---Api(Application programming interface)(general transfering front end to backend)
Cloud based vul.scanner(AWS,GOOGLE CLOUD,IBM)


**very important cyber security tearms:
POLICY -- rules
PRODUCDURE--step by step following for policy 
STANDARD -- regualtions are given by government (hippa)(GDPR-general data production regulations)(segregate by a department)(
REGULATIONS--

BENIFITS
--Identify security
--priorities remediation
--supports
--improve over all security recommadation
--povides actionable  recommadation

Drawbacks
--resource intensive
--false positive(there is no vulnerability bt it shown as vul)
--false negative(there is no vulnerability bt it shown as  no vul)
--limited scopes 

SAST tool-Static application security testing**Res(python)

developing vulerability tool(there should be no true vul)

**Vulnerability Assessment method
--vulerability scanning

**PENETRATION TESTING(imp interview question)
5 phases of hacking
--INFORMATION gathering(eg:host,router,servers,protocols,technologies(python,html,cms-conent management system(coding illa ma --web site-- create pannalam)
--scanning(indetail info eg:version-apache,)
--gaining access(find vul and exploit it)
--Maintaining access or persistance(using backdoor)
--clearing tracks

NDA(MENTIONS THE ATTACKS-SHOULD NOT ATTACK DOS ATTACKS)(PENETRAION TECHNIQUES)

types of peneration test
--application
--network
--physical
--IOTMedic

**Internal and external penetration testing 
internal -- there will be limitations in vul
external-- they give only give domain to find vul

