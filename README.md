# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 
```
Developed by:Praveen V
Register no:212222040121
```
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

## Google Hacking:

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

 
# DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion








## dnsenum
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


## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


# Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 
  
  

# nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:
## site:

![Screenshot 2024-09-19 140000](https://github.com/user-attachments/assets/8d4c007c-a98f-4669-9c09-de8d06965077)

## filetype:
![Screenshot 2024-09-19 140051](https://github.com/user-attachments/assets/a3d8285c-cb6d-4064-8b77-317585a44eca)



## intext:
![Screenshot 2024-09-19 140229](https://github.com/user-attachments/assets/6aceb2cd-3ec4-4c64-9cba-6521fbeddaed)



## inurl:

![Screenshot 2024-09-19 140253](https://github.com/user-attachments/assets/a03cdb05-4d37-4698-a5d3-6f19ba30bd6e)

## intitle:
![image](https://github.com/user-attachments/assets/c3da5262-ea2b-4f79-94e3-e60d6fa75353)



## link:
![image](https://github.com/user-attachments/assets/2241e38e-0bca-4ced-8e05-83420dcf795e)



## cache:

![image](https://github.com/user-attachments/assets/1fddaae4-6429-4317-a33d-ad89d02610b9)

## DNS Enumeration:
## DNS Recon:
![image](https://github.com/user-attachments/assets/3a6d46ca-e1c6-4600-8b6b-091334dd87e6)

## dnsenum:

![image](https://github.com/user-attachments/assets/9379db3f-0dd6-4b90-b0a0-2b90158d7dc4)

![image](https://github.com/user-attachments/assets/094f0955-8090-4932-8df4-3def1849810e)



## smtp-user-enum:

![image](https://github.com/user-attachments/assets/46bd614b-e82d-4844-a598-3b01a0f6fabf)


## nmap –script smtp-enum-users.nse :

![image](https://github.com/user-attachments/assets/1216ed62-fd95-4aa9-a6aa-14e1a779a549)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

