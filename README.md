# YourCloudDude

**Practical AWS, cloud, Terraform, and Python projects for developers who learn by building.**

> Build it. Understand it. Explain it.

Most tutorial repositories stop when the happy path works. These projects spend more time on the parts that make the design worth discussing: **why a boundary exists, what can fail, what should never be public, and what changes when the system grows.**

## Start with a project

### [AWS Serverless URL Shortener](https://github.com/yourclouddude/aws-serverless-url-shortener)

A small API where the useful lessons are bigger than shortening a URL: conditional DynamoDB writes, short-code collisions, application-level expiration, IAM boundaries, and the controls a public creation endpoint would still need.

**Stack:** API Gateway · Lambda · DynamoDB · IAM · Python · AWS SAM

### [AWS Event-Driven Image Pipeline](https://github.com/yourclouddude/aws-event-driven-image-pipeline)

An asynchronous image-processing pipeline built around a deliberate `S3 → SQS → Lambda` boundary. It shows why buffering matters, how partial batch failures work, what happens to poison messages, and why compressed file size alone is not enough protection for an image worker.

**Stack:** S3 · SQS · Lambda · DLQ · CloudWatch · IAM · Python · AWS SAM

### [Terraform AWS Three-Tier Web Stack](https://github.com/yourclouddude/terraform-aws-three-tier-web-stack)

A Terraform project about network boundaries rather than architecture-diagram decoration: a public ALB, private EC2 Auto Scaling tier, and private RDS PostgreSQL tier across two Availability Zones. The base design deliberately has no SSH, no public EC2 IPs, and no NAT gateway.

**Stack:** Terraform · VPC · ALB · EC2 Auto Scaling · RDS · Security Groups · CloudWatch

### [Python Safe File Organizer](https://github.com/yourclouddude/python-safe-file-organizer)

A file organizer that treats automation as something that can damage data if it is designed carelessly. It plans before mutation, refuses silent overwrites, records completed moves, and supports rollback without pretending the filesystem is transactional.

**Stack:** Python · `pathlib` · CLI · pytest · Ruff · GitHub Actions

## Explore by area

**AWS & serverless**  
[URL Shortener](https://github.com/yourclouddude/aws-serverless-url-shortener) · [Event-Driven Image Pipeline](https://github.com/yourclouddude/aws-event-driven-image-pipeline)

**Infrastructure as Code & networking**  
[Terraform AWS Three-Tier Web Stack](https://github.com/yourclouddude/terraform-aws-three-tier-web-stack)

**Python engineering**  
[Safe File Organizer](https://github.com/yourclouddude/python-safe-file-organizer)

## What to look for in these repositories

The goal is not to collect hundreds of shallow projects or make every repository follow the same template.

When a project needs it, you will find tests, CI, architecture notes, failure handling, security boundaries, cost discussion, troubleshooting, and explicit limitations. The important part is that those things come from the actual implementation rather than being added as portfolio decoration.

A useful way to work through a repo is to get it running, change one assumption, break a boundary on purpose, and then explain why the resulting failure happened.

If you can explain **why the system is shaped this way and what you would change next**, the project has done its job.

## Current technical focus

**AWS:** serverless systems, event-driven architecture, IAM, S3, SQS, Lambda, API Gateway, DynamoDB, VPC networking, ALB, EC2, RDS  
**Python:** automation, CLI tools, backend logic, testing, safe file operations  
**Infrastructure:** Terraform, AWS SAM, GitHub Actions, CI/CD, security boundaries, cost-aware design

## YourCloudDude

YourCloudDude creates practical technical learning resources around AWS, cloud architecture, Python, and building real projects.

**Website:** https://yourclouddude.com/  
**X:** https://x.com/yourclouddude

---

**Build the project. Break an assumption. Explain what happened.**
