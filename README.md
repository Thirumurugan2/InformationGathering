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

###Pen Test Tools Categories:

Following Categories of pen test tools are identified for information gathering: Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network. http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
![267845057-93be2e15-6d5f-4a08-b388-603929d20367](https://github.com/sanjeevraj0987/InformationGathering/assets/120698946/3e33dc24-829b-4a30-9d00-12a3c8785026)

### Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```

## OUTPUT:
![267846800-fcfa6599-0910-44f9-9f80-8675ae08893c](https://github.com/sanjeevraj0987/InformationGathering/assets/120698946/86da5172-01c8-4fa1-b574-a29f909f9a77)

###History of the website:
## OUTPUT:
https://web.archive.org/
![267847359-db356479-b506-4b5c-97e2-8781af87c5de](https://github.com/sanjeevraj0987/InformationGathering/assets/120698946/c9d10330-af20-47b3-898b-8d9c421b7ef8)
##Web server Fingerprint:
Netcat:
```
nc 172.17.52.118 80
```
## OUTPUT:
![267847643-af9060d2-7fea-4c18-a92b-60e77bbb6ac4](https://github.com/sanjeevraj0987/InformationGathering/assets/120698946/dde0900f-bce6-4d4e-91f7-da8672b3e315)

## namp
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## OUTPUT:
![267848628-2498d78f-e535-4f8b-96e0-052bd431325a](https://github.com/sanjeevraj0987/InformationGathering/assets/120698946/99602ff8-d553-4c2b-993c-0c79403fc77a)
## Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## OUTPUT:
![267848835-465ba57f-78d4-429f-862d-059d1f56a472](https://github.com/sanjeevraj0987/InformationGathering/assets/120698946/d804bd53-aa31-4bf0-a52f-bc77cc48319f)
## httprint
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## OUTPUT
![267849132-f59f0b7e-bea2-4642-99b9-a9767847d184](https://github.com/sanjeevraj0987/InformationGathering/assets/120698946/e8428f83-b733-44b7-93d4-66bcd130d61a)

## Tracing the Location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## OUTPUT
![267849281-de4f1456-1773-40f8-b1d3-388bae6aabb0](https://github.com/sanjeevraj0987/InformationGathering/assets/120698946/e73e090a-0dca-4eb3-9e91-680da4556582)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![267849405-a297fa4a-e19f-4b5f-aba3-0b35819890aa](https://github.com/sanjeevraj0987/InformationGathering/assets/120698946/f3b4f1c6-99b5-4415-8c61-fdc0aa241e9c)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![267849490-e8d554f5-0b5a-4c6f-ae34-17326ad87c0a](https://github.com/sanjeevraj0987/InformationGathering/assets/120698946/1adf5e4a-dd3b-4051-98b3-5586f3b4d4b7)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
