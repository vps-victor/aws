# AWS ARCHITECTURE 

## Abstraction  
![AWS Infrastructure Architecture](https://github.com/vps-victor/aws/assets/105178616/b2d22240-d572-44e2-8183-2e60f24635cd)

**`NETWORK`**
- Types of Cloud `Private` (own), `Public` (services), `Hybrid` (mix)
- `Autos-caling` manage EC2 based on user-defined policies
- `Elastic Load Balancing` distributes incoming traffic
- `Virtual Private Cloud` Virtual Network to isolates own services
- `Direct Connect` host to aws without going through the internet
- `Rout 53` scalable & highly available DNS (and registration) (run at port 53). 

**`COMPUTING SERVICES`**
- `EC2` virtual server with resizable compute capacity
- `Elastic Beanstak` deploy and managing containers for working w/ web applications
- `Lambda` stateless serverless event-driven system
- `S3` secure, scalable, and durable storage of data objects (flat file)
  - standart, Intelligent-Tiering, Standard-IA, One Zone-IA, Glacier, Glacier DA 

- STARTING STEPS
  - (0) CREAT & ADD Credit Card
  - (1) ROOT ACC > Config MFA to the root acc
  - (2) CONFIG ADM IAM + CREATE ADM ACC + MFA
  - (3) CREATE > Group + Polices + Groups + Roles
  - (4) ADD + BIND users to 3st Step  

- [Well-Architected PDF](https://docs.aws.amazon.com/wellarchitected/latest/userguide/intro.html)
- [AWS Total Cost Calculator](https://calculator.aws/)
- AWS drive of cost
  - Storage (always) + instance running=yes (instance stoped=no) + Instance type + pricing model +
  - Load balancing + Detailed monitoring + Elastic IP (max. 1/enabled EC2) + Paid OS & Software Package
- AWS Budget (before) vs AWS Cost Explorer (After)

# CHEAT SHEETS

## Abbreviation & Acronyms

### AWS Certifications Abbreviations and Current Exam Codes

**FOUNDATIONAL**
- [AWS Certified Cloud Practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/) (CCP) - CLF-C02

**ASSOCIATE**
- [AWS Certified SysOps Administrator - Associate](https://aws.amazon.com/certification/certified-sysops-admin-associate/) (SOA) - SOA-C02
- [AWS Certified Developer - Associate](https://aws.amazon.com/certification/certified-developer-associate/) (CDA) - DVA-C01
- [AWS Certified Solutions Architect - Associate](https://aws.amazon.com/certification/certified-solutions-architect-associate/) (SAA) - SAA-C03
- [AWS Certified Data Engineer - Associate](https://aws.amazon.com/certification/certified-data-engineer-associate/) (DEA) - DEA-C01

**PROFESSIONAL**
- [AWS Certified DevOps Engineer - Professional](https://aws.amazon.com/certification/certified-devops-engineer-professional/) (DOP) - DOP-C01
- [AWS Certified Solutions Architect - Professional](https://aws.amazon.com/certification/certified-solutions-architect-professional/) (SA Pro / SAP) - SAP-C02

**SPECIALTY**
- [AWS Certified Advanced Networking - Specialty](https://aws.amazon.com/certification/certified-advanced-networking-specialty/) (AN-S) - ANS-C01
- [AWS Certified Security - Specialty](https://aws.amazon.com/certification/certified-security-specialty/) (SCS) - SCS-C02 
- [AWS Certified Machine Learning - Specialty](https://aws.amazon.com/certification/certified-machine-learning-specialty/) (MLS) - MLS-C01
</details>

# COMPARISON
[Latance/Ping Test - Cloud Providers per Regions](https://cloudpingtest.com/)

<details><summary></summary><br>
<details>
