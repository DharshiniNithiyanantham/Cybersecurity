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
wireshark is mostly used in the checking process
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

  testing types
  *functional testing
  *non-functional testing
  
  security testing
  
  *production environment - live websites/web app
  *staging environment p- actual copy of production
  *QA environment - test build

  brup suite:
  Client --->Burp Proxy ----> Server
    good for web developers and testers

  user agent -> browser
    
    foxyproxy -extension for proxy browser

    Dark web:
client ---> Proxy1 ----> Proxy2 ----> proxy3 -----> proxy4 -----> proxy5 -----> proxy6 ----> Server

command for kali

sudo nmcli networking on
asks password : kali
sudo service NetworkManager start
both commands are used to check the internet connection
sudo - super user

ctrl + Shift + C --> for copy
ctrl + Shift + v --> for paste

sudo nano /etc/apt/sources.list
cat /etc/apt/sources.list
 add s to the http -->https
ctrl + O and enter to save the file
ctrl + X to Exit

URL and URI :
web protocol  --> http/https
TLD
Domain --> example.com
sub domain -->maps.example.com , mail.example.com

ls -l /var/www/html/  --> for finding the rrot element
linux basic path --> /var/www/html
windows --> C:\inetpub\wwwroot

WAP --> web application firewall + rate limiting

the testing has 3 types of environment :
Production Environment-live website or web application--->(website down problem is there)(risk,highly costly)
Staging Environment-Changes checks or tested -->Actual copy of production environment
QA environment -test enviornment

Burpsuite-act b/w client and server -->**proxy**---act as a middle server --proxy can be both good and bad

Tor-Bitcoin 1b-$67000
Darkweb--act b\w clent and server--=>   (Client-->Proxy1-->proxy 2-->Proxy3-->proxy 4-->Proxy5-->proxy 6-->SERVER) **located in 6 diff ways**

**burp suite**
open burp suite->proxy_->open browser(user agent)

Foxyproxy--open link-right side up corner--puzzle Symbol--poxies--enter name--enter ip--save--

brupsuite--port 8080

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
Cyber Security Terms(most important terms)
1. Policy(Set of rules)
2. Procedure(Step to follow the rules)
3. Standard(a Set of procedure)
4. Regulation(it is only given by Government)
   

Vulnerability Assessment(VA)**--process of identifying--find out potential weakness actually affect CIA--PRIORTIZE(if u find bug)--
it invovles a systematic review of potential weakness

VA process
Asset discovery---------->Vulnerability scanning----------->Vulnerability assessment ------------->Vulnerability remediation
Vulnerability Metrics (Vulnerability scores)
   National vulnerability databases - this websiter will tell us how to gives the rating or score(CVSS score)
   CVSS-Common Vulnerability Scoring System

Vulnerability Scanner(VS)
Types
1. Automated VS types
  1. Database VS
  2. Network VS
  3. Web Application VS
  4. Host-based VS
  5. API VS
  6. Cloud based VS
2. Manual VS


Vulnerability Assessment methods
1.VS
2.Penetration Testing
3.Risk Assessment 
4.Code reviews
5.Configuration Management
6.Patch management
7.Security assessment


Five phases of Hacking
1.Information gathering
2.Scanning(scan the information we gathered)
3.Gaining Access
4.Maintaining Access(persistence)
5.Clearing Tracks
6.Reporting

Penetration Testing(an authorized attack on a device to identify security vulnerabilities that could be hacked)
process
Information Gathering------>Threat modeling------>Vulnerability analysis------->Exploitation ------>Post exploitation ----->Reporting
Types
1.Internal PT(there are some scope and rules to be followed)
2.External PT(they only give us the information and said to identify the vulnerability)


SAST- without deploying a code(
DAST- we use code (burpsuite)

OWASP Vulnerability
1.Sql Injection
2.Authentication vulnerability
3.Path Traversal/Directory Traversal
4.OS Command Injection

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

To convert the url to base 64 ---> cyber chef (website) use base 64 option
never use cyber chef to kali linux (uses more memory)

book.hacktricks.xyz ----> bible for hackers
hacking tricks for hackers

penetration testing > vulnerability testing

cat /etc/passwd | grep /bin/bash ---> checking the users in system

mkdir MKCE && cd  MKCE && touch test -----> to create directory in kali
ll ---> to check the directory

concepts to remember (shells) :
web shell ----> browser
bind shell ----> process/service/port combine
reverse shell ----> user interaction

revshell.com ---->access the system by clicking the link provided in the website

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

angry ip scanner ----> scans the ip address

pimeyes ----> upload photos to find the person social accounts.

google advanced search -----> to search about the particular things

inurl: --->shows results about the login page

site:mkce.ac.in  ----> shows the particular websites

pip
sudo apt install example

To install vpn
download tyhackme file
run command:

cd Desktop
sudo openvpn tryhackme.ovpn
takes some time
 -----------
or
download academy.zip file
download and install splunk enterprise free version
ip link set dev ens33 up
dhclient -v ens33
ip a

SIEM(security inforamtion and event management) tool  ----> for defense
splunk forwarder --->to connent with the servers (complex task)
not able to copy,paste

service ssh status ----> to check the active status of ssh(in academy linux)
ssh root@192.168.181.129 ---> in commmand prompt
then -->enter passord --> tcm
uname -a
whoami
useradd -m splunkfwd
groupadd splunk
then go to splunk forwarder install for linux:

export SPLUNK_HOME="/opt/splunkforwarder"
mkdir $SPLUNK_HOME

go to ---> splunk forwarder download(website) :
to  check the version of the splunk in academy linux using ---> uname -a
to download ---> copy the 64-bit version and paste it in command prompt(academy)

dpkg -i splunkforwarder-9.2.1-78803f08aabb-linux-2.6-amd64.deb --->change based on given address
chown -R splunkfwd:splunkfwd $SPLUNK_HOME
$SPLUNK_HOME/bin/splunk start --accept-license
cd /opt/splunkforwarder/bin/
it shows --->/opt/splunkforwarder/bin# ---> ./splunk status
./splunk add forward-server 172.1.42.46(:9997) --->default port
./splunk add forward-server 172.1.42.46:9997
enter previous asked username and password
ping ip address(172.1.42.46) ---> for academy running
if not installed properly:
./splunk add forward-server 172.1.42.46:9997
./splunk list forward-server
if inactive :
./splunk remove forward-server
./splunk restart
for installing splunk
check the splunk enterprise --->academy with data graphs---> enterprise is running
go to windows defender firewall ---> inbound --> new rule --->port --->tcp ---> 9997 ---> finish
go to windows defender firewall ---> inbound --> new rule --->port --->udp ---> 9997 ---> finish

go to kali ---> terminal ---> sudo netdiscover (with ip address and subnet mask ex--> 192.168.181.254/16)
  create or go to any directory --->cd mkce
  create file within it ----> nano ipaddress.txt
  save the ip address in the file
  to open the file ----> cat ipadddress.txt
  it shows the resources within the file
  to filter the ip address:
cat ipadddress.txt | cut -d ' ' -f 2
nmap &ip -p -v -min-rate=3000
alternate for netdiscover:
nmap -sn 192.168.181.128/24 ---> use this command
nmap 192.168.181.128 -p1-65535 -min-rate=3000 -v -pn
to check the port connected to the server :
[
sudo netdiscover -r 192.168.243.0/2
export target=192.168.243.0
nmap $target  -p1-65535 -min-rate=3000
nmap $target  -p1-65535 -v -min-rate=3000 -oN open_ports.txt
]

CIA
SQL injection
authentication authorzation-theory
access control/authorization

**pwd/home/kali
cat /etc/passwd---all linux  have this file 
burpsuite
/usr/bin/burpsuite
/bin/burpsuite
win.ini---all window have this file
path traversal
OS command injection

path traversal 

cybercef-use full web site--should not use in kali
path traversal-file inclusion

cat /etc/passwd | grap/bin/bash(or) /bin/zsh
temC

mkdlr MKCE && cd MKCE 

web shell-browser
Bind shell - process/service/port combine 
Reverse shell- user intraction


siem tool-security inform and event management tool

Risk accpectance -outdated system ah updated panna mudiyathu so atha acccept pannikanum (for eg:linux,windows..) 
risk aviodance-varathuku munnadi eh prevent pandrathu..eliminate or mitigate ohh pannama varathuku munnadi eh prevent pandrathu... fixing a aviod...completing removeing the risk.before doing a one thing there is a risk so we aviod completely
risk mitigation--reducing a risk,antivirus protection,unused application removing,
risk transfer--process of transfering risk to threed party,insurance,

improtance of cloud security
threat proctetion-unauthorized person la iruthu namba data va threat la iruthu protect pandrathu

business continuty---system backup ah 

encryption--normal plain txt converted into cipertxt(
access management--
cloud scalability--oranganization 
network segmentation--oru n/w ah sub -net ah piruchutu athuku etha mari security control and sources ah provide pannum
stack validation and re---intrutation attack nadaka pothu bac

cloud artitecture
on premisis -host server(within the organization)

i/q
cloud security models
-public cloud sercurity
-private cloud security
-hybrid cloud security
-community cloud security

cloud security changes

Regulatory Compliance in CS
GRC-government risk and complaints
GDPR--General Data Protection Regulation(EU)
HIPAA--Health Insurance Portability and Accountability Act(US)
PCIDSS-Payment Card Industry Data Security Standard
ISO27001-ISMS policy
ISO27002-
CMM level--
Capability Maturity Model 
-initial,managed,defined,qualitively management ,optimizing

future trends
DAC-Discretionary access contriool
RBAC-Role based access control
MAC-Mandatory access control

