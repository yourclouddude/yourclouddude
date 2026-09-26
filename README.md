<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=205&color=0:2563EB,50:7C3AED,100:06B6D4&text=YourCloudDude&fontColor=ffffff&fontSize=54&fontAlignY=36&desc=AWS%20%E2%80%A2%20Cloud%20%E2%80%A2%20Python%20%E2%80%A2%20Terraform&descAlignY=57&descSize=18&animation=fadeIn" alt="YourCloudDude" />

### Build systems you can understand, break, debug, and explain.

Practical cloud and Python projects built around real engineering decisions — not just the happy path.

[![Website](https://img.shields.io/badge/yourclouddude.com-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white)](https://yourclouddude.com/)
[![X](https://img.shields.io/badge/@yourclouddude-111827?style=for-the-badge&logo=x&logoColor=white)](https://x.com/yourclouddude)

</div>

---

## Start here

Each featured repository focuses on a different engineering problem. Pick the one closest to what you want to learn.

<table>
<tr>
<td width="50%" valign="top">

### ☁️ [Serverless URL Shortener](https://github.com/yourclouddude/aws-serverless-url-shortener)

**AWS serverless fundamentals through a small API.**

API Gateway → Lambda → DynamoDB, with the interesting parts left visible: conditional writes, short-code collisions, application-level expiration, IAM boundaries, and public endpoint limitations.

`AWS` · `Python` · `Lambda` · `DynamoDB`

</td>
<td width="50%" valign="top">

### 🖼️ [Event-Driven Image Pipeline](https://github.com/yourclouddude/aws-event-driven-image-pipeline)

**Learn why asynchronous boundaries matter.**

S3 → SQS → Lambda image processing with buffering, retries, partial-batch failures, DLQ behavior, image-safety limits, and explicit failure handling.

`AWS` · `S3` · `SQS` · `Lambda` · `Python`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏗️ [Terraform Three-Tier AWS Stack](https://github.com/yourclouddude/terraform-aws-three-tier-web-stack)

**Treat the network boundary as part of the application.**

A public ALB fronts private EC2 Auto Scaling and private RDS PostgreSQL across two Availability Zones. The base design intentionally avoids public EC2 IPs, SSH ingress, and an unnecessary NAT gateway.

`Terraform` · `AWS` · `VPC` · `ALB` · `EC2` · `RDS`

</td>
<td width="50%" valign="top">

### 🐍 [Safe File Organizer](https://github.com/yourclouddude/python-safe-file-organizer)

**Automation should be reversible when it touches your files.**

A Python CLI that plans before mutation, requires confirmation, avoids silent overwrites, records completed moves, and supports manifest-based rollback.

`Python` · `CLI` · `pytest` · `GitHub Actions`

</td>
</tr>
</table>

---

## The engineering thread

These repositories are intentionally different, but they share one standard:

| Question | What the projects make visible |
|---|---|
| **Why this architecture?** | The boundary or design decision the project is actually teaching |
| **What can fail?** | Collisions, retries, unsafe input, network assumptions, or filesystem mistakes |
| **What should stay private?** | IAM, security-group, credential, and data-safety boundaries |
| **How is it checked?** | Tests, CI, validation, or project-specific guardrails where appropriate |
| **What was left out?** | Scope and limitations instead of unsupported “production-ready” claims |
| **What changes next?** | Trade-offs a learner can reason about as requirements grow |

A useful way to explore any repo is:

```text
1. Run or validate the project
2. Find the boundary it is protecting
3. Change one assumption
4. Observe what fails
5. Explain the trade-off
```

That is the difference between copying an architecture and learning how to reason about one.

---

## Toolbox

<div align="center">

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

The portfolio currently centers on **AWS architecture, Python engineering, infrastructure as code, CI, security boundaries, failure handling, and cost-aware design**. Tools appear here because they are used by the projects, not as a keyword wall.

---

<div align="center">

### Learn by building systems you can explain.

[![Browse repositories](https://img.shields.io/badge/Browse_repositories-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourclouddude?tab=repositories)
[![Visit YourCloudDude](https://img.shields.io/badge/Visit_YourCloudDude-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white)](https://yourclouddude.com/)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=105&section=footer&color=0:06B6D4,50:7C3AED,100:2563EB" alt="" />

</div>
