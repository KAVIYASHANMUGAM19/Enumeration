# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

 
#DNS Enumeration


##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion

##dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.


##smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:

## site:

<img width="1596" height="908" alt="site" src="https://github.com/user-attachments/assets/802bd645-704b-4816-8ce9-4b29a57429b6" />

 
## filetype:

<img width="1655" height="905" alt="filetype" src="https://github.com/user-attachments/assets/e8776cbc-e289-4aa7-9605-aee18fadee6d" />


## intext:

<img width="1728" height="917" alt="intext" src="https://github.com/user-attachments/assets/8ab1d9eb-3b00-4635-abdc-7cf3add672eb" />



## inurl:

<img width="1686" height="904" alt="inurl" src="https://github.com/user-attachments/assets/84aa4223-8f2b-4ac8-8d8f-f207f70d2a4e" />



## intitle:

<img width="1691" height="907" alt="intitle" src="https://github.com/user-attachments/assets/bc3c3a1b-19ba-403d-95ea-17c5f9321405" />


## link:

<img width="1874" height="970" alt="link" src="https://github.com/user-attachments/assets/231f0ecf-f42b-4342-bc1f-ad6294e0b787" />


## cache:

<img width="1640" height="909" alt="cache" src="https://github.com/user-attachments/assets/676bf48b-4f05-4aa8-b857-a98d8353dced" />



## DNS Enumeration:

## DNS Recon:

<img width="940" height="708" alt="DNS Recon" src="https://github.com/user-attachments/assets/f259e507-42a1-4830-bb2e-bf59f7ddfe7d" />


## dnsenum:

<img width="949" height="692" alt="dnsenum" src="https://github.com/user-attachments/assets/3c0d4bbb-9899-4fa0-8e07-e7efb63094c4" />


<img width="952" height="779" alt="dnsenum " src="https://github.com/user-attachments/assets/80dfbc8b-8269-4d55-b994-6fb38f55d5fd" />



## smtp-user-enum:

<img width="956" height="439" alt="smtp-user-enum" src="https://github.com/user-attachments/assets/675d6d7e-93d4-4bc6-8046-7918290946fa" />


<img width="942" height="436" alt="smtp" src="https://github.com/user-attachments/assets/01c1d6c3-776a-43ab-b3f4-599a3856f823" />



## telnet:

<img width="955" height="598" alt="telnet" src="https://github.com/user-attachments/assets/012b1201-08f5-4d01-a1ef-f3fe83895c17" />


## nmap –script smtp-enum-users.nse :

<img width="951" height="280" alt="nmap script" src="https://github.com/user-attachments/assets/25b69cb0-57e3-45e4-805c-133a9040781e" />




## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

