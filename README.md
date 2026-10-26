# python-lanscanner
Scans LAN wifi range(IP, Hostname, MAC)

This is a lightweight python Local Area Network(LAN) scanner that discovers devices on a LAN. It uses ARP.
And details of those devices such as MAC address, IP address, Hostname Lookup.

#Requirements:
-Scapy
-Python 3.8 or newer
-network interface connected to a LAN
-Appropriate privileges to send and receive network packets

#Installation:

1.Clone repository:
```
git clone https://github.com/NoboBanana/python-lanscanner.git
```
2.Install dependencies:
```
pip install scapy
```
#Run it

Linux:
```
sudo lanscanner.py
```
Windows(Run as Administrator in pwrshell or cmd):
```
python lanscanner.py
```
