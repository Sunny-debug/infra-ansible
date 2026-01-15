Ansible EC2 & Route53 Automation (Tag-Driven)

**Overview**
This project demonstrates infrastructure lifecycle management using Ansible tags.
With a single playbook, you can create EC2 instances, provision Route53 DNS records, and tear everything down cleanly—all by selectively running tags.

This is intentionally simple, practical, and production-oriented.

**Key Concepts Demonstrated**

- Infrastructure as Code (IaC) with Ansible
- Tag-based execution (create, destroy_ec2, destroy_r53)
- Dynamic DNS record creation from EC2 facts
- Separation of configuration via vars_files
- Idempotent, repeatable automation
