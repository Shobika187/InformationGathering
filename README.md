# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering
### Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.


## OUTPUT:
![image](https://github.com/Shobika187/InformationGathering/assets/94508142/89bb93fc-1412-43a9-8cc2-de4807a44a22)
### Finding IP address:
Ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
![image](https://github.com/Shobika187/InformationGathering/assets/94508142/e6730364-0022-4ad3-b50e-01a8300d5acf)
### Finding Hosting Company
Get further detail by using ip2location.com website.
![image](https://github.com/Shobika187/InformationGathering/assets/94508142/f8e52e5e-6470-4140-a19f-3b57e9494a8b)
### History of the website:
### Output:
![image](https://github.com/Shobika187/InformationGathering/assets/94508142/581914ad-e434-4918-9a2d-5c48a8bfa8bd)
### Webserver Fingerprinting:
#### Netcat:
```
nc 172.17.52.118 80
```
![image](https://github.com/Shobika187/InformationGathering/assets/94508142/2e1dd3ed-0d1b-4fed-8ee0-6e02e7010260)
### nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
![image](https://github.com/Shobika187/InformationGathering/assets/94508142/4340c85c-d8f8-4675-ab36-df945c8a2555)
### Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
### Output:
![image](https://github.com/Shobika187/InformationGathering/assets/94508142/e1f2de11-052c-407c-b4c2-4f8a86dade43)
### httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
![image](https://github.com/Shobika187/InformationGathering/assets/94508142/b83bbaaf-42b5-448e-b0af-fb13e4652683)
### Tracing the Location:
### TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
### UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
### Output:

![image](https://github.com/Shobika187/InformationGathering/assets/94508142/7ae34851-9f4d-4453-901f-8fe3cb2f98c9)
### ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
![image](https://github.com/Shobika187/InformationGathering/assets/94508142/e2ab97dc-38f3-41d5-b702-2a853911b903)





## RESULT:
The information gathering techniques tools/procedure were  identified successfully
