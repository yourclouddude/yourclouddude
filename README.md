<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:2563EB,50:7C3AED,100:06B6D4&text=YourCloudDude&fontColor=ffffff&fontSize=56&fontAlignY=36&desc=Cloud%20%7C%20AWS%20%7C%20Python%20%7C%20Terraform&descAlignY=57&descSize=18&animation=fadeIn" alt="YourCloudDude banner" />

### Build it. Understand it. Explain it.

Practical **AWS, Cloud, Terraform, and Python** projects for developers who learn by building.

[![Website](https://img.shields.io/badge/Website-yourclouddude.com-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white)](https://yourclouddude.com/)
[![X](https://img.shields.io/badge/X-@yourclouddude-111827?style=for-the-badge&logo=x&logoColor=white)](https://x.com/yourclouddude)
[![GitHub](https://img.shields.io/badge/GitHub-yourclouddude-7C3AED?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourclouddude)

</div>

---

## About YourCloudDude

Most tutorial repositories stop when the happy path works. These projects spend more time on the parts that make a design worth discussing: **why a boundary exists, what can fail, what should never be public, and what changes when the system grows.**

The goal is simple: build projects you can not only run, but **understand, debug, defend, and explain.**

---

## Tech I Work With

<div align="center">

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=111827)

![Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![S3](https://img.shields.io/badge/Amazon_S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

</div>

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔗 AWS Serverless URL Shortener

A serverless API where the useful lessons are bigger than shortening a URL: conditional DynamoDB writes, short-code collisions, application-level expiration, IAM boundaries, and public endpoint controls.

**Stack**

![API Gateway](https://img.shields.io/badge/API_Gateway-FF4F8B?style=flat-square&logo=amazonapigateway&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

[**View project →**](https://github.com/yourclouddude/aws-serverless-url-shortener)

</td>
<td width="50%" valign="top">

### 🖼️ AWS Event-Driven Image Pipeline

An asynchronous image-processing pipeline built around a deliberate `S3 → SQS → Lambda` boundary. It explores buffering, partial batch failures, poison messages, DLQs, and safer image processing.

**Stack**

![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![SQS](https://img.shields.io/badge/SQS-FF4F8B?style=flat-square&logo=amazonsqs&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-759C3E?style=flat-square&logo=amazoncloudwatch&logoColor=white)

[**View project →**](https://github.com/yourclouddude/aws-event-driven-image-pipeline)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🏗️ Terraform AWS Three-Tier Web Stack

A Terraform project focused on real network boundaries: public ALB, private EC2 Auto Scaling, and private RDS PostgreSQL across two Availability Zones—with no SSH, public EC2 IPs, or unnecessary NAT gateway in the base design.

**Stack**

![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

[**View project →**](https://github.com/yourclouddude/terraform-aws-three-tier-web-stack)

</td>
<td width="50%" valign="top">

### 🐍 Python Safe File Organizer

A file organizer that treats automation as something that can damage data if designed carelessly. It plans before mutation, prevents silent overwrites, records completed moves, and supports rollback.

**Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI-2088FF?style=flat-square&logo=githubactions&logoColor=white)

[**View project →**](https://github.com/yourclouddude/python-safe-file-organizer)

</td>
</tr>
</table>

---

## Explore by Area

| Area | Projects | Focus |
|---|---|---|
| ☁️ **AWS & Serverless** | [URL Shortener](https://github.com/yourclouddude/aws-serverless-url-shortener) · [Image Pipeline](https://github.com/yourclouddude/aws-event-driven-image-pipeline) | Lambda, APIs, queues, storage, IAM |
| 🏗️ **Infrastructure as Code** | [Three-Tier AWS Stack](https://github.com/yourclouddude/terraform-aws-three-tier-web-stack) | Terraform, networking, ALB, EC2, RDS |
| 🐍 **Python Engineering** | [Safe File Organizer](https://github.com/yourclouddude/python-safe-file-organizer) | automation, CLI design, testing, safe operations |

---

## What These Repositories Focus On

```text
Architecture decisions   → Why is the system shaped this way?
Failure handling         → What breaks, and how does it recover?
Security boundaries      → What should never be public?
Testing & CI             → How do we know changes are safe?
Cost awareness           → What does this design cost as it grows?
Trade-offs               → What would we change at the next scale?
```

When a project needs it, you will find **tests, CI, architecture notes, failure handling, security boundaries, cost discussion, troubleshooting, and explicit limitations**. The important part is that those things come from the actual implementation rather than being added as portfolio decoration.

A useful way to work through a repo is to get it running, change one assumption, break a boundary on purpose, and then explain why the resulting failure happened.

---

## Current Technical Focus

<table>
<tr>
<td>☁️ <b>AWS</b></td>
<td>Serverless systems, event-driven architecture, IAM, S3, SQS, Lambda, API Gateway, DynamoDB, VPC, ALB, EC2, RDS</td>
</tr>
<tr>
<td>🐍 <b>Python</b></td>
<td>Automation, CLI tools, backend logic, testing, safe file operations</td>
</tr>
<tr>
<td>🏗️ <b>Infrastructure</b></td>
<td>Terraform, AWS SAM, GitHub Actions, CI/CD, security boundaries, cost-aware design</td>
</tr>
</table>

---

<div align="center">

### Learn by building systems you can explain.

[![Explore Projects](https://img.shields.io/badge/Explore_My_Projects-2563EB?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourclouddude?tab=repositories)
[![Visit YourCloudDude](https://img.shields.io/badge/Visit_YourCloudDude-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white)](https://yourclouddude.com/)

**Build the project. Break an assumption. Explain what happened.**

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:06B6D4,50:7C3AED,100:2563EB" alt="footer" />

</div>
