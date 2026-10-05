# Hi, I'm Ahmad Raza

**Aspiring DevOps Engineer** focused on cloud infrastructure, Linux systems, and observability.

I learn by building complete systems end to end: provisioning infrastructure as code, setting up databases for high availability, and monitoring everything with metrics, logs, and alerts. Each project below is documented so it can be reproduced from scratch.

---

## Featured Projects

### [AWS MySQL High Availability with GTID Replication and Monitoring](https://github.com/Ahmadraza9091/AWS-MySQL-High-Availability-GTID-Replication-Monitoring)
A production-style, two-node MySQL Source/Replica setup on AWS EC2 behind a bastion host. It uses GTID-based replication and custom Bash scripts for health checks, failover, and replica rejoin. Monitoring is covered by Prometheus, Grafana, Loki, and Nagios/NRPE, and the setup was validated with failure tests.
`AWS` `MySQL 8` `GTID` `Bash` `systemd` `Prometheus` `Grafana` `Loki` `Nagios`

### [Proxmox Observability Stack](https://github.com/Ahmadraza9091/proxmox-observability-stack)
A self-hosted monitoring and incident-response stack for Proxmox servers. Grafana Alloy agents, deployed with Ansible, ship metrics and logs to Prometheus and Loki. Alertmanager routes alerts into a self-hosted OpsKnight instance for incident tracking, on-call, and escalation, with no cloud dependency.
`Prometheus` `Grafana` `Loki` `Alertmanager` `Grafana Alloy` `Ansible` `Docker`

### [Three-Tier AWS Infrastructure with Terraform](https://github.com/Ahmadraza9091/aws-terraform-three-tier)
A modular Terraform deployment of a three-tier architecture: a VPC with public and private subnets across two Availability Zones, an Application Load Balancer, an EC2 Auto Scaling group, and a private multi-AZ RDS MySQL database. Terraform state is stored remotely in S3, and the project documents the security-group design and its known limitations.
`Terraform` `AWS` `VPC` `ALB` `Auto Scaling` `RDS` `S3`

### [Linux Server Toolkit](https://github.com/Ahmadraza9091/linux_toolKit-script)
A Bash toolkit that automates common server administration tasks: user and folder management, backups, disk and memory checks, service control, and system information.
`Bash` `Linux` `Automation`

---

## Tech Stack

| Area | Tools |
|---|---|
| **Cloud** | AWS (EC2, VPC, ALB, Auto Scaling, RDS, S3) |
| **Infrastructure as Code** | Terraform, Ansible |
| **Containers** | Docker, Docker Compose |
| **Observability** | Prometheus, Grafana, Loki, Alertmanager, Grafana Alloy, Nagios/NRPE |
| **Databases** | MySQL (GTID replication, failover) |
| **Systems and Scripting** | Linux (Ubuntu), Bash, systemd |
| **Version Control** | Git, GitHub |

---

## Currently Learning

- CI/CD pipelines with GitHub Actions
- Kubernetes fundamentals
- Deeper cloud security and cost optimization

---

## How I Work

- I build full systems rather than isolated exercises, and I test failure scenarios, not just the happy path.
- I document projects so someone else can rebuild them from zero.
- I state the limitations of my work honestly, because knowing what a design does not cover is part of engineering.

---

## Connect

- LinkedIn: [your-linkedin-link]
- Email: [your-email-address]
