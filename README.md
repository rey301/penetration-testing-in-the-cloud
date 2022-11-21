# Penetration Testing in the Cloud 
## Description
Penetration testing is an important aspect of computer security and is one of the main reasons why so many applications have frequent security updates; to patch vulnerabilities to prevent exploitation. Normally, such acts are conducted using local machines and networks.

In this repository, penetration testing in the cloud is investigated using AWS as a service to host a vulnerable web application that is attacked using a Kali Linux machine. Kali Linux has preinstalled various tools such as Nmap which is useful for the information gathering stage in retrieving data about a targeted network.

It is not so common that papers investigate how penetration testing is affected within the cloud as opposed to traditional penetration testing. This paper aims to gain an understanding on what restrictions one may have when performing tests within such systems.

Gaining a reverse shell using Netcat on the vulnerable cloud machine is achievable by exploiting vulnerabilities discussed in literature. One of the vulnerabilities includes file uploading which allows one to upload a malicious file to the web server. Many security restrictions prevent you from doing so such as specifying the file type to a non-malicious extension such as JPEG or PNG.

An assessment of the penetration test is provided towards the end of the final report regarding how well it performed.

## Disclaimer
This project was produced in association with the University Of Sussex as a final year dissertation.
