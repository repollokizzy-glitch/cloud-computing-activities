# Cloud Infrastructure Components

## 1. Compute Resources

### Purpose

Compute resources provide the processing power needed to run applications and perform tasks. CPU and memory are examples of compute resources.

### Importance in Cloud Computing

Compute resources are important because applications need processing power to operate. Cloud providers allow organizations to choose the amount of CPU and memory based on their workload.

### KillerCoda Environment

The KillerCoda server has an Intel Xeon E312xx processor with 1 CPU core and 1.9 GiB of RAM. These resources allow the Linux server to perform basic computing and administrative tasks.

---

## 2. Storage Resources

### Purpose

Storage resources provide space for operating system files, applications, configurations, and data.

### Importance in Cloud Computing

Cloud applications need storage to save and retrieve information. Reliable storage is important for maintaining data and allowing applications to continue operating.

### KillerCoda Environment

The server has a 20 GB virtual disk called `/dev/vda`. Its main partition `/dev/vda1` provides approximately 19 GB and uses the ext4 filesystem.

---

## 3. Networking Resources

### Purpose

Networking resources allow computers, servers, applications, and users to communicate with each other.

### Importance in Cloud Computing

Networking is necessary because cloud resources need to communicate with users and other services. It allows applications to be accessed and resources to exchange information.

### KillerCoda Environment

The Linux environment reported the following IP addresses:

- 172.30.1.2
- 172.17.0.1

These addresses show that the virtual server has network connectivity within its environment.

---

## 4. Operating System

### Purpose

The operating system manages the computer's hardware and provides an environment where applications and commands can run.

### Importance in Cloud Computing

The operating system provides the foundation for cloud applications and server workloads. Linux is widely used in cloud environments because it is flexible and supports many server applications.

### KillerCoda Environment

The server is running Ubuntu 24.04.4 LTS with Linux kernel version `6.8.0-136-generic`.

---

## Relationship Between the Components

The cloud infrastructure components work together. The operating system manages the CPU, memory, storage, and networking resources. Compute resources process tasks, storage keeps data, and networking allows the server to communicate with other systems.
