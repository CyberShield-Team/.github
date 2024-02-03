<center>
  <img src="https://github.com/CyberShield-Team/About_Our_Team/blob/main/CyberShield.png">
</center>

# Project Scenario: Improving Cybersecurity for NotOurJob Solution

## Executive Summary:
* NotOurJob Solution, a growing tech company, seeks to enhance its cybersecurity posture, particularly in cloud infrastructure. The company has contracted our team to implement robust cybersecurity measures that align with AWS best practices and compliance standards. This project focuses on establishing secure IAM configurations, server hardening, data protection, and implementing effective SIEM systems for real-time monitoring and response to adversarial activities.

## Current Challenges:

* Inadequate IAM Practices: NotOurJob Solution currently lacks stringent IAM policies for its root and user accounts, leading to potential security vulnerabilities.

* Server Vulnerability: Their Windows Server DC and Linux data servers, especially those handling PII and PCI data, are not fully compliant with CIS benchmarks, posing risks to data integrity and security.

* Insufficient Data Encryption: Sensitive data stored in their cloud infrastructure is not adequately encrypted, both at rest and in transit, leading to potential data breaches.

* Lack of Effective Monitoring: The absence of a robust SIEM system hinders the real-time detection of malicious activities and delays response to potential threats.

* Inefficient Cloud Monitoring Systems: Current cloud monitoring practices are insufficient to capture and analyze traffic effectively, limiting the ability to detect and respond to attack TTPs.

## Proposed Solutions:

* IAM Configuration: Implement robust IAM policies, including multi-factor authentication and regular audits, to secure root and user accounts.

* Server Hardening and Data Protection: Harden the Windows Server DC and Linux data servers following CIS benchmarks. Implement comprehensive encryption for data at rest and in transit.

* SIEM/Log Aggregation System Implementation: Deploy and configure Splunk, CloudWatch, or Elastic Stack to ingest and analyze event logs from key AWS assets in real time.

* Cloud Monitoring Enhancement: Utilize VPC Flow Logs and AWS Lambda functions for capturing traffic and automating responses to detected threats. Implement monitoring for failed SSH attempts and unusual patterns.

* Novel Tool Integration: Explore and implement a novel cybersecurity tool or technique to enhance the existing security framework.

* Compliance and Documentation: Develop thorough compliance documentation and security incident plans to align with industry standards like PCI or GDPR.

## Project Goals:

* Ensure robust cybersecurity defenses in the cloud environment.
* Achieve compliance with relevant cybersecurity standards.
* Enhance real-time monitoring and rapid response capabilities.
* Educate and empower NotOurJob Solution's team on best cybersecurity practices.
* Outcome Expectation:
* Upon project completion, NotOurJob Solution will have a fortified cloud infrastructure, significantly reduced cybersecurity risks, and a competent team capable of maintaining and improving their cybersecurity posture.
