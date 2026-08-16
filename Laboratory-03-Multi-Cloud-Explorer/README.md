# Checkpoint 7 – Continue Your Linux Investigation

## Linux Server Investigation

A Linux Playground was launched using KillerCoda. The following commands were used to identify the server information.

| Information      | Linux Command         | Result                             |
| ---------------- | --------------------- | ---------------------------------- |
| Operating System | `cat /etc/os-release` | Ubuntu 24.04.4 LTS                 |
| CPU Information  | `lscpu`               | 1 CPU, Intel Xeon E312xx @ 2.0 GHz |
| Memory           | `free -h`             | 1.9 GiB RAM                        |
| Disk Space       | `df -h`               | 19 GB total, 13 GB available       |

## Terminal Screenshots

### Operating System

![Operating System](OS_screenshot.png)

### CPU Information

![CPU Information](cpu_Screenshot.png)

### Memory

![Memory Information](memory_Screenshot.png)

### Disk Space

![Disk Space](diskspace_Screenshot.png)

## Cloud Migration

If this Linux server were migrated to the cloud, it could be hosted using virtual machine services from AWS, Azure, or GCP.

| Cloud Provider | Service                | Description                                                 |
| -------------- | ---------------------- | ----------------------------------------------------------- |
| AWS            | Amazon EC2             | Hosts Linux servers as virtual machines in AWS.             |
| Azure          | Azure Virtual Machines | Hosts Linux servers as virtual machines in Microsoft Azure. |
| GCP            | Google Compute Engine  | Hosts Linux servers as virtual machines in Google Cloud.    |

### Conclusion

The Linux server can be migrated to AWS, Azure, or GCP. Amazon EC2, Azure Virtual Machines, and Google Compute Engine can all host Linux-based servers. The best platform would depend on cost, performance, scalability, and the organization's requirements.

