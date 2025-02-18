:octicons-terminal-24:

## General Cloud Pentesting notes

## Attacking SaaS
* Exploits could be out of scope 
* Generally focused on data and the access to that data
* Backdooring and abusing tokens abuse like OAuth
* MFA bypass

## Attacking PaaS
* Focuses on Applications

## Attacking IaaS
* Compute, Storage, Network all in scope

## Cloud Recon & Discovery
Domains and hosts
* Passive techniques such as Google Cache, Certificate Transparency Reports
* Active techniques such as brute forcing with wordlists and DNS scanning

Some Tools for Domain and Host recon
* gau
* OTX
* crtsh
* hunters.io
* shodan
* securitytrails
* intelX
* dehashed
* DNSdb

Subdomain Hijacking
* CNAME record that was created for something and never cleaned up (dangling dns record)

Wordlist Patterns
* Can utilize to discover services 

Figure out cloud providers - Leverage DNS info, tools like builtwith, public websites, any other OSINT data.

Azure Recon - AADInternals

Domain Enum tools:
* subfinder
* dnsx
* puredns
* OWASP amass
* MassDNS


## Cloud Scanning



Identify IP ranges for provider and scan for target discovery.
Azure, AWS, and GCP all publish their IP addresses. Can use jq to parse.


## Azure Attacks

## AWS Attacks

## GCP Attacks

Data Exfiltration no tools - gcloud and gsutil
!!! tip "How to detect"
    
    Check the GCP audit logs

## Kubernetes Attacks

## Linux Attacks

### Rootkits

===  ""
!!! tip "How to detect"
    
    Content TBD
    
### Container Attacks


## Resources
* https://github.com/RoseSecurity/Red-Teaming-TTPs
* https://github.com/dafthack/CloudPentestCheatsheets/?tab=readme-ov-file
* https://github.com/RhinoSecurityLabs/pacu
* https://www.daehee.com/blog/scan-aws-ip-ssl-certificates/
* 