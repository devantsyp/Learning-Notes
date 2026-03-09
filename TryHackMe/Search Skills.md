# Search Skills @ [TryHackMe](https://tryhackme.com/room/searchskills)

# Key Takeaways

When evaluating information on the Internet, the user must consider the reputability of the source, credible evidence, objective evaluation of information, and consistency from multiple sources.

There are several search operators that can be used to search for information. Google, for example, has several search operators: **"exact phrase"**, **site:**, **-**, **filetype:**, and more.

Google is not the only search engine. There is a myriad of specialized search engines designed to search for very specific information which may not be optimized for by other engines. For example, Shodan allows the user to search for specialized networking-related information.

Consider **Common Vulnerabilities and Exposures** (CVE) and **the Exploit Database** for searching for identified and standardized vulnerabilities.

# Notes

## Evaluation of Search Results

Few things to consider when evaluating information:

> - **Source**: Identify the author or organization publishing the information. Consider if the source is reputable.
> - **Evidence**: Check whether the claims are backed by credible evidence and logical reasoning.
> - **Objectivity**: Evaluate whether the information is presented impartially and rationally.
> - **Consistency**: Validate information from multiple independent sources.

**ss** (socket statistics) is the name of the command replacing **netstat** in Linux.

## Advanced searches

### search operators supported by Google:

> **"exact phrase"** - match the exact phrase inside quotes.

> **site:** - this operator lets the user specify domain name to which the search is limited,

> **-** - the minus sign allows to omit search results that contain a particular word or phrase.
>
> > **pyramids -tourism** or **-tourism pyramids**

> **filetype:** - this operator is used to find files instead of web pages. Some files the user can search for are **PDF**, **DOC**, **XLS**, **PPT**.
>
> > **filetype: ppt cyber security**

## Specialized Search Engines

### Shodan

Shodan us a specialized search engine which allows users to search for specific types and versions of servers, networking equipment, industrial control systems, IoT devices.

> For example, the user may want to see how many servers are running Apache 2.4.1. This can be searched for using **apache 2.4.1** keyword, which will return the list of servers with the string "apache 2.4.1" in their headers.

### Censys

Censys is a specialized search engine focusing on Internet-connected hosts, websites, certificates, and other Internet assets. Some of its use cases include enumerating domains in use, auditing open ports and services, and discovering rogue assets within a network.

### VirusTotal

VirusTotal is an online website that provides a virus-scanning services for files using multiple antivirus engines. It allows users to upload files or provide URLs to scan them against numerous antivirus engines and website scanners in a single operation.

### Have I Been Pwned

Have I Been Pwned is an online website which tells the user if an email address has appeared in a leaked data breach.

## Vulnerabilities and Exploits

### CVE

**Common Vulnerabilities and Exposures** (CVE) is a program providing a standardized identifier for vulnerabilities and security issues in software and hardware products. Each vulnerability is assigned a CVE ID with a standardized format like **CVE-2024-29988**.

The CVE system is maintained by the MITRE Corporation.

### Exploit Database

**The Exploit Database** lists exploit codes from various authors; some of these exploit codes are tested and marked as verified.

### Linux Manual Pages

Linux offers a manual containing help on using Linux and Unix-like system commands.

> For example: if the users wants to check the manual page for the command **ip**, the user should issue a command **man ip**. This command will output the the name of the command, synopsis, options, and more.
