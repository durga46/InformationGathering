# EX.NO : 02
# DATE : 24.8.2023
# <p align="center"> To perform information gathering techniques</p>


## AIM:
To perform information gathering techniques using kali linux

## STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode

### Step 2:
Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:

![238300689-505c1008-6602-4c30-a18f-a19831193609](https://github.com/durga46/InformationGathering/assets/75235704/f4fc5309-b9c2-41cf-9d17-3c14db69dc7f)

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```ping saveetha.ac.in```

## Output:
![238300810-18c141eb-f997-4e6a-970b-1278bf0f085f](https://github.com/durga46/InformationGathering/assets/75235704/5a558f4c-9789-4609-8fe7-d0cdbfc9d53a)


### Finding Hosting Company
get further detail by using ip2location.com website.

## Output:


## History of the website:
## Output:
![238300893-192a1d85-246e-45ad-bcd0-0a70e209c601](https://github.com/durga46/InformationGathering/assets/75235704/34f85b0d-cc13-4011-8b19-6c20768be490)



## Webserver Fingerprinting:
### Netcat:
```nc 172.17.52.118 80```

## Output:
![238301333-7c38b307-51d1-45b5-85ec-751ed930ba9b](https://github.com/durga46/InformationGathering/assets/75235704/03420b23-87a6-4b6c-9c0b-1adebfc08afd)


### nmap:
```nmap -p 21 -sV --script=banner ftp.vim.org```
### Output:

![238301531-4631c0fd-1296-4c74-82fa-8950c48c5a61](https://github.com/durga46/InformationGathering/assets/75235704/acaaf27c-71f6-4e4b-92d6-ce91d41fc20e)

### Whatweb:
```whatweb infosys.com```

```whatweb zoho.com```
```whatweb -v -a 3 172.17.52.201```
### Output:
![238301746-ab6e52ed-b1c2-4c7c-b4cb-edc75d6de5e6](https://github.com/durga46/InformationGathering/assets/75235704/7882fcfd-12b3-4b87-9453-36b461237ccb)
![238302016-3daa0d6f-df5d-4571-bf8b-c2fe63bbc3cc](https://github.com/durga46/InformationGathering/assets/75235704/90bc2a3d-20eb-4a4c-84da-890ff611e62e)


### httprint:
```httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more```

### Output:
![238301937-a70e6db5-d324-4bee-80f9-9dfdf9b37338](https://github.com/durga46/InformationGathering/assets/75235704/2ed06091-2b80-4b78-8c01-55bb1a00368b)


## Tracing the Location
## TCP Traceroute:
```sudo traceroute -T www.saveetha.ac.in```

### Output:

![238302079-a4c85efc-4084-4513-895e-325f5f53f5f7](https://github.com/durga46/InformationGathering/assets/75235704/38d8273d-8f49-4cc1-8a45-a1631500f07c)

## UDP Traceroute:

```sudo traceroute -U www.saveetha.ac.in```

### Output:
![238302091-8c7b84b9-8045-45c3-ba6a-f2af47f40e5e](https://github.com/durga46/InformationGathering/assets/75235704/4dd62409-9f05-477b-b6ba-7f83b0828c4f)

## ICMP Traceroute:
```sudo traceroute  www.saveetha.ac.in```
### Output:

![238302109-00a45edd-a2df-4cc6-858c-87d5b4a6b659](https://github.com/durga46/InformationGathering/assets/75235704/e8403fee-1392-4f27-b64e-417ba33fbb3e)

## RESULT:
The information gathering techniques tools/procedure were identified successfully
