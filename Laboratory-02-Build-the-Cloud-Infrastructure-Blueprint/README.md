# Mission 2: Build the Cloud Infrastructure Blueprint

## Mission Overview

This laboratory activity focused on investigating the infrastructure behind a cloud-based Linux server. The KillerCoda environment was examined using Linux commands to identify its computing, memory, storage, filesystem, and networking resources. The activity also included comparing AWS, Microsoft Azure, and Google Cloud Platform and designing a basic cloud infrastructure.

## Objectives

- Investigate a Linux server.
- Identify compute, storage, networking, and operating system resources.
- Understand how cloud infrastructure components work together.
- Compare services from major cloud providers.
- Create a simple cloud infrastructure diagram.
- Practice technical documentation using Markdown.
- Organize laboratory work using GitHub.

## Cloud Infrastructure Components

The major infrastructure components investigated were compute, storage, networking, and the operating system.

The KillerCoda server has one CPU core and 1.9 GiB of RAM. It also has a 20 GB virtual disk and runs Ubuntu 24.04.4 LTS. The environment also provides IP addresses for network communication.

## Tools Used

- KillerCoda Playground
- Ubuntu Linux
- Linux Terminal
- GitHub
- Markdown
- diagrams.net

## Linux Commands Executed

| Command | Purpose |
|---|---|
| `cat /etc/os-release` | Check operating system information |
| `uname -r` | Check kernel version |
| `lscpu` | Display CPU information |
| `nproc` | Display CPU core count |
| `free -h` | Display RAM information |
| `lsblk` | Display storage devices |
| `df -hT` | Display mounted filesystems |
| `hostname` | Display hostname |
| `hostname -I` | Display IP addresses |

## Skills Learned

I learned how to investigate a Linux server using terminal commands and identify basic cloud infrastructure resources. I also learned how different cloud providers offer equivalent services and practiced creating technical documentation and an infrastructure diagram.

## Challenges Encountered

One challenge was understanding the information displayed by the Linux commands. Some commands showed technical details that were unfamiliar at first. I also needed to organize the results properly so that the information could be easily understood by another person.
