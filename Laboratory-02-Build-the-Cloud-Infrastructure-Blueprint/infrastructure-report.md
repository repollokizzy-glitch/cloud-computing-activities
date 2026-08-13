# Cloud Infrastructure Investigation

## Operating System

The Linux server is running Ubuntu 24.04.4 LTS, also known as Noble Numbat.

- Operating System: Ubuntu
- Version: 24.04.4 LTS
- Version ID: 24.04
- Codename: noble

## Kernel Version

The Linux kernel version is:

6.8.0-136-generic

The kernel manages the system resources and provides communication between the operating system and the hardware.

## CPU Model

The CPU detected in the KillerCoda environment is:

Intel Xeon E312xx (Sandy Bridge, IBRS update)

The system has 1 CPU core.

## RAM

The server has a total of 1.9 GiB of RAM.

At the time of the investigation:

- Used: 409 MiB
- Free: 850 MiB
- Available: 1.5 GiB

The amount of used memory can change while the server is running.

## Disk Capacity

The server has a 20 GB virtual disk named `/dev/vda`.

The main partition is `/dev/vda1`, which has approximately 19 GB and is mounted as the root filesystem.

## Mounted File Systems

| Filesystem | Type | Size | Used | Available | Mounted On |
|---|---|---:|---:|---:|---|
| tmpfs | tmpfs | 191M | 996K | 190M | /run |
| /dev/vda1 | ext4 | 19G | 5.4G | 13G | / |
| tmpfs | tmpfs | 952M | 84K | 952M | /dev/shm |
| tmpfs | tmpfs | 5.0M | 0 | 5.0M | /run/lock |
| /dev/vda16 | ext4 | 881M | 117M | 703M | /boot |
| /dev/vda15 | vfat | 105M | 6.2M | 99M | /boot/efi |

## Hostname

The hostname of the server is:

ubuntu

## IP Address

The server reported the following IP addresses:

- 172.30.1.2
- 172.17.0.1

## Summary

The KillerCoda environment provides a virtual Linux server with one CPU core, 1.9 GiB of RAM, and a 20 GB virtual disk. The server runs Ubuntu 24.04.4 LTS and has network addresses that allow it to communicate within its environment.
