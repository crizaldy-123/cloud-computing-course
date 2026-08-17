# Laboratory 3 – Multi-Cloud Explorer

This laboratory activity explores and compares Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP). It includes cloud platform research, service comparisons, client recommendations, a multi-cloud decision matrix, and a Linux investigation using KillerCoda.

## Checkpoint 7 – Linux Investigation

I launched an Ubuntu Linux playground using KillerCoda and used Linux commands to inspect the server's system information.

### Linux Server Information

| Category             | Information                                       |
| -------------------- | ------------------------------------------------- |
| **Operating System** | Ubuntu 24.04.4 LTS                                |
| **Architecture**     | x86_64                                            |
| **CPU**              | Intel Xeon E312xx (Sandy Bridge), 1 CPU @ 2.0 GHz |
| **Memory**           | 1.9 GiB                                           |
| **Disk Space**       | 19 GiB total, approximately 13 GiB available      |

### Linux Commands Used

The following commands were used to collect the system information:

```bash
cat /etc/os-release
lscpu
free -h
df -h
```

The `cat /etc/os-release` command was used to identify the operating system. The `lscpu` command provided information about the CPU and system architecture. The `free -h` command displayed the available memory, while `df -h` showed the disk space and usage.

### Possible Cloud Services

If this Linux server were migrated to the cloud, it could be hosted using virtual machine services from the three major cloud providers:

| Cloud Provider            | Possible Service       |
| ------------------------- | ---------------------- |
| **AWS**                   | Amazon EC2             |
| **Microsoft Azure**       | Azure Virtual Machines |
| **Google Cloud Platform** | Google Compute Engine  |

These services can provide Linux virtual machines in the cloud. The appropriate virtual machine size would depend on the application's CPU, memory, storage, and performance requirements.

### Evidence

The KillerCoda terminal screenshots show the commands used and the actual Linux server information collected during the investigation.
