# Silverline Financial Solutions

**Industry:** Finance / Fintech
**Employees:** 150
**Description:** Provides online banking, payment processing, and financial analytics. Systems are hybrid (on-premises servers + cloud).

## Assets with Specific Versions

| Asset Category               | Asset / Software / Hardware | Version   |
| ---------------------------- | --------------------------- | --------- |
| **Application Server**       | Ubuntu Server               | 20.04 LTS |
| **Database Server**          | MySQL                       | 5.7       |
| **Web Server**               | Apache HTTP Server          | 2.4.38    |
| **Firewall**                 | Cisco ASA 5506-X            | 9.12(4)   |
| **Switch**                   | HP ProCurve 2920            | 07.5.69   |
| **Load Balancer**            | F5 BIG-IP                   | 15.1.2    |
| **Employee Workstations**    | Windows 10 Pro              | 20H2      |
| **SOC Analyst Workstations** | Kali Linux                  | 2020.4    |
| **Cloud Storage**            | AWS S3 buckets              | N/A       |
| **Cloud Directory**          | Azure AD                    | N/A       |

## Network Devices and Cloud Storage

The organization has recently deployed several network devices and a cloud storage bucket. Some of these devices and storage configurations were left with default settings or overly permissive access.

## Passwords and MFA

Currently, no formal password policy is enforced, and multi-factor authentication (MFA) is optional for all accounts.

## Segmentation Between Servers and Workstations

For simplicity, the network allows full communication between servers and workstations, which share the same network segment or VLAN. Security relies primarily on host-based firewalls.

## Employee Awareness for Phishing Attacks

Employees receive security awareness training and phishing simulations only once per year. If an employee fails the training, they are required to complete an additional phishing awareness course.
