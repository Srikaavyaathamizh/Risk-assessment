# EXP : 5 - ASSET ORIENTED RISK ASSESSMENT OF STORAGE ASSETS IN AWS AND AZURE
# Name: SRIKAAVYAA T
# Reg no: 212223230214

# Aim
<p>
To perform an asset-oriented risk assessment of cloud storage assets including:

1.AWS Elastic Block Store (EBS)
2.AWS Elastic File System (EFS)
3.Azure Files (File Storage)
</p>

# 1. Background
<p>
Cloud storage services offer flexible, scalable options for storing data. However, each storage type brings distinct security risks and configurations. This experiment focuses on identifying assets and performing a detailed risk assessment based on:

Confidentiality, Integrity, and Availability (CIA)
Access control
Encryption
Auditing capabilities

# 2. Tools Required
AWS Console with EC2, EBS, and EFS access
Azure Portal with Storage Account access
IAM credentials with sufficient permissions
Risk Assessment Template (provided)
Internet browser
Microsoft Excel or Google Sheets for tabulating findings


# Procedure
Part A: Identifying AWS Storage Assets
Step 1: Login to AWS Console
Go to: https://aws.amazon.com/console

Log in using IAM or root credentials

Step 2: Identify EBS Volumes
Navigate to: EC2 > Volumes (under Elastic Block Store)

# Record the following:
Volume ID
Size and Type (e.g., gp2, io1)
Availability Zone
Attached instance (if any)
Encryption status

# Tags

Step 3: Identify EFS File Systems
Go to: EFS > File systems
Record:
File system ID and name
Mount targets (AZs)
Throughput mode (bursting/provisioned)
Performance mode
Lifecycle policy
Encryption at rest status
Part B: Identifying Azure File Storage Assets
Step 4: Login to Azure Portal
Go to: https://portal.azure.com

Log in using credentials with access to storage accounts

Step 5: View File Shares
Navigate to: Storage Accounts > Choose Account > File Shares
Record:
Name
Quota (in GB)
Used space
Protocol (SMB/NFS)
Authentication method (SAS Tokens, Azure AD, Shared Keys)
Snapshot policies
Risk Assessment Methodology
Use the following CIA-based asset-oriented checklist for each asset:

<img width="862" height="471" alt="image" src="https://github.com/user-attachments/assets/dd91be5b-d0b9-46a9-8db8-7d90fc8a1944" />
# Sample Output Table

<img width="1026" height="198" alt="image" src="https://github.com/user-attachments/assets/c5290bd1-951f-4527-a279-93d4f0e64916" />

# Result
All active cloud storage assets across AWS and Azure have been identified and assessed for security posture based on CIA principles, access control, encryption, and risk level.
</p>



