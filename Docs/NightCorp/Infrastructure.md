# NightCorp Technical Documentation: Critical Asset Overview

## **1. Network Infrastructure**

**Description:**  
NightCorp's network infrastructure is the backbone of its digital operations, supporting internal communication, data transfer, and access control mechanisms across the organization.

**Components:**
- **Routers:** Cisco ASR 1001-X and Cisco ISR 4000 series routers, providing high-performance routing, VPN services, and secure WAN connectivity.
- **Switches:** Cisco Catalyst 9000 series switches, enabling secure, high-speed connectivity within NightCorp's internal network infrastructure.
- **Firewalls:** Cisco Firepower 2100 series firewalls, offering advanced threat protection, intrusion prevention systems (IPS), and deep packet inspection.


## **2. Web Servers**

**Description:**  
These servers host NightCorp’s public-facing applications and client services, ensuring customers can access services such as cybersecurity dashboards, analytics platforms, and monitoring tools.

**Components:**
- **HTTP/HTTPS Servers:** Apache HTTP Server and NGINX for robust, secure web hosting and load distribution.
- **API Gateways:** Managed via AWS API Gateway and Kong for secure, scalable API access, rate limiting, and monitoring.
- **Load Balancers:** AWS Elastic Load Balancers (ELB) and HAProxy are used to distribute incoming client requests across multiple servers, ensuring high availability and performance.

## **3. Database Servers**

**Description:**  
NightCorp uses high-availability database clusters for securely storing sensitive corporate, client, and operational data.

**Components:**
- **Relational Databases:** PostgreSQL and MySQL for structured data storage and transaction processing.
- **NoSQL Databases:** MongoDB for flexible, scalable storage of unstructured and semi-structured data.
- **Encrypted Storage:** Advanced encryption mechanisms using AES-256 for encrypting data at rest, with secure key management through AWS KMS and HashiCorp Vault for safeguarding encryption keys.

## **4. Employee Devices**

**Description:**  
Endpoints used by NightCorp employees for daily operations, including accessing internal systems, client databases, and communication tools.

**Components:**
- Laptops and desktops running Windows 11 Pro and macOS Ventura for development, administrative tasks, and communications.
- Company-owned mobile devices, including Apple iPhone 13 Pro and Samsung Galaxy S21 devices, managed through Mobile Device Management (MDM) solutions.
- Virtual Private Network (VPN) connections provided via Cisco AnyConnect for secure remote access.

## **5. Internal Applications**

**Description:**  
NightCorp’s internal applications streamline operations and communication across departments, including HR, finance, and technical support.

**Components:**
- **HR Management Systems:** Workday for HR operations, payroll management, and employee benefits tracking.
- **Internal Communication Tools:** Microsoft Teams and Slack for internal messaging and collaboration.
- **Project Management Tools:** Jira and Asana for project tracking and task management.
- **Financial Management:** SAP S/4HANA for financial reporting and planning.
- **Technical Support Systems:** ServiceNow for IT service management (ITSM) and issue tracking.

## **6. Cloud Services**

**Description:**  
NightCorp leverages cloud solutions for scalable data storage, software-as-a-service (SaaS) applications, and secure backups.

**Components:**
- **Cloud Storage Services:** AWS S3, Azure Blob Storage, and Google Cloud Storage for secure data hosting.
- **SaaS Platforms:** Microsoft 365 for productivity tools, Atlassian Suite for development collaboration, and Salesforce for customer relationship management (CRM).
- **Cloud Compute Services:** AWS EC2 instances for scalable application hosting and Google Kubernetes Engine (GKE) for container orchestration.
- **Cloud Security Tools:** AWS GuardDuty for threat detection and Azure Security Center for compliance monitoring.

## **7. Email Servers**

**Description:**  
Handles internal and external communications, ensuring secure message exchange within the organization.

**Components:**
- **Secure Email Gateways:** NightCorp uses Cisco Umbrella and Proofpoint for secure email filtering, ensuring that emails sent and received are free from threats such as phishing, spoofing, and malware.
- **Spam and Malware Filters:** These are configured to filter out malicious content, detect patterns of suspicious activity, and block inbound malware payloads. Proofpoint's cloud-based spam filtering and Palo Alto Networks' WildFire are used for real-time malware scanning.
- **Data Loss Prevention (DLP) Tools:** DLP policies are configured to ensure that sensitive information (e.g., client data, internal reports) is not accidentally or maliciously leaked via email. The solution used is Symantec DLP.


## **8. Backup Systems**

**Description:**  
NightCorp maintains backup systems for business continuity and disaster recovery.

**Components:**
- **On-premises Backup Servers:** Dell PowerEdge R740 servers equipped with Veeam Backup & Replication software, providing high-availability backup solutions for critical internal systems. These on-prem backup servers are configured with RAID 6 for fault tolerance.
- **Cloud-Based Backup Solutions:** AWS Backup is used for scheduled, automated backups of NightCorp's cloud resources, including EC2 instances, EBS volumes, and S3 buckets. AWS Glacier is used for long-term, cost-effective data archiving.
- **Automated Backup Scheduling:** NightCorp uses Veeam's automated backup scheduling for on-prem servers, performing full backups once a week with incremental backups every night. Cloud backups via AWS Backup are scheduled daily, with monthly backups retained for compliance.

## **9. Physical Security Systems**

**Description:**  
Physical systems designed to protect NightCorp’s infrastructure from unauthorized physical access or tampering.

**Components:**
- **CCTV Surveillance:** High-definition surveillance cameras are installed throughout the corporate campus, using Hikvision cameras with 24/7 remote monitoring.
- **Biometric Access Control Systems:** NightCorp uses Fingerprint and Retina scan biometric security to control access to sensitive areas. Systems from HID Global are employed for employee authentication.
- **Intrusion Detection Alarms:** Honeywell Pro-Watch and Bosch Security Systems’ intrusion detection are integrated with motion sensors, door/window contacts, and glass break detectors to monitor unauthorized access to critical facilities.

## **10. Third-Party Integrations**

**Description:**  
Critical external services used by NightCorp to facilitate payment processing, specialized API functionalities, and external data sources.

**Components:**
- **Payment Gateways:** NightCorp integrates with Stripe and PayPal for secure online payment processing.
- **External Data Feeds:** NightCorp uses Bloomberg for real-time financial market data and weather data feeds from AccuWeather to enhance their cybersecurity analytics platform.
- **Partner SaaS Integrations:** Integration with partner SaaS providers such as Okta for identity management, Splunk for security information and event management (SIEM), and Trello for project collaboration.

---
