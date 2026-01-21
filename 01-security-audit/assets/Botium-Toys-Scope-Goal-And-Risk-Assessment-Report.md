## Audit Scope

The scope of this security audit covers the entire security program at Botium Toys. The audit evaluates how the organization manages, protects, and monitors its assets across technical, administrative, and physical domains.

Assets and environments reviewed include:

- Employee-owned and company-issued devices
- Internal network and internet connectivity
- On-premises systems and supporting infrastructure
- Business systems supporting accounting, e-commerce, inventory, and telecommunications
- Data storage, retention, and processing environments
- Legacy systems requiring ongoing monitoring
- Physical locations including offices, storfront, and warehouse

The audit focuses on identifying security gaps in asset management, access control, data protection, monitoring, and recovery capabilities.

## Audit Goals

The primary goals of this audit are to:

- Identify and document key organizational assets
- Evaluate exisiting security controls and compliance practices
- Assess risks related to confidentiality, integrity, and availability (CIA triad)
- Determine which security controls and best practices are missing or insufficient
- Support completion of a structured controls and compliance checklist
- Provide a foundation for actionable security recommendations

## Asset Overview

Assets managed by the IT department include:

- On-premises equipment supporting daily business operations
- Employees equipment such as desktops, laptops, smartphones, remote workstations, and peripherals
- Retail inventory stored on-site and in the adjoining warehouse
- Core business systems including accounting, database management, e-commerce, inventory, and security tools
- Internal network and internet access
- Data retention snd storage systems
- Legacy systems that are end-of-life and require manual monitoring and maintenance

## Risk Assessment 

Botium Toys currently lacks mature asset management and comprehensive security controls. As a result, the organization faces increased risk of data exposure, operational disruption, and potential non-compliance with applicable U.S. and international regulations.

## Control Best Practice Alignment

The audit identified in the Identify function of the NIST Cybersecurity Framework. Asset discovery, classification, and impact analysis are insufficient, limiting the organization's ability to prioritize risks and protect systems critical to business continuity.

## Risk Score

# Overall Risk Score: 8/10 (High)

This rating limited control implementation incomplete monitoring capabilities, and weak recovery planning.

## Key Risk Observations

- All employees have broad access to internally stored data, including potential access to cardholder data and customer PII/ SPII
- Customer credit card data is stored and processed wothout encryption
- Least privilage and separation of duties are not enforced
- Firewall controls are implemented and actively filtering network traffic
- Antivirus software is deployed and monitored
- No intrusion detection system (IDS) is in place
- No disaster recovery plan or backups for critical data exist
- Breach notification pprocedures for EU customers meet the 72-hour requirement
- Password policy exists but does not meet modern complexity standards
- No centralized password management system is enforced
- Legacy systems are monitored but lack defined maintenance schedules
- Physical security controls such locks, CCTV, and fire detection systems are present and operational

## Impact Assessment

The potential business impact of asset loss is assessed as medium due to limited visibility into asset criticality. However, the risk of regulatory fines, data breaches, and reputational damage is high, given the absence of strong access controls, encryption, monitoring, and recovery mechanisms.
