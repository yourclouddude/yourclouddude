<p align="center">
  <img src="./assets/cloud-workshop.svg" width="100%" alt="YourCloudDude's cloud workshop: a pixel-art robot, a laptop, a message queue and connected server islands. Build it. Understand it. Explain it." />
</p>

<p align="center">
  <b>Practical cloud projects for developers who learn by building.</b><br />
  AWS architecture, Python automation, and infrastructure as code.
</p>

<p align="center">
  <a href="https://yourclouddude.com/">Website &amp; guides</a> &nbsp; / &nbsp;
  <a href="#on-the-workbench">Explore the projects</a> &nbsp; / &nbsp;
  <a href="https://x.com/yourclouddude">Find me on X</a>
</p>

## Welcome to my workshop

I'm **YourCloudDude**. I build and share projects that make cloud engineering easier to understand, from a small Python tool to an AWS system with queues, private networks, and infrastructure you can read.

Getting something to run is the starting point. I care about the questions that come next: **why this design, what can fail, and how do you find out?** My repositories explore those decisions through code, architecture notes, tests, and experiments you can try yourself.

## On the workbench

Pick a system you'd like to understand. Each project gives you a different design decision to investigate.

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/yourclouddude/aws-serverless-url-shortener"><img src="./assets/project-serverless.svg" width="100%" alt="Serverless URL shortener: HTTP to Lambda to DynamoDB. Explore collisions, expiration, and IAM." /></a>

**[AWS Serverless URL Shortener](https://github.com/yourclouddude/aws-serverless-url-shortener)**

Build a small API, then follow the decisions behind collision-safe writes, expiring links, and separate read/write permissions.

`API Gateway` · `Lambda` · `DynamoDB` · `Python`

</td>
<td width="50%" valign="top">

<a href="https://github.com/yourclouddude/aws-event-driven-image-pipeline"><img src="./assets/project-pipeline.svg" width="100%" alt="Event-driven image pipeline: S3 uploads pass through a queue to a worker. Explore buffering, retries, and failure isolation." /></a>

**[AWS Event-Driven Image Pipeline](https://github.com/yourclouddude/aws-event-driven-image-pipeline)**

Follow an upload through S3, SQS, and Lambda. See how buffering, duplicate events, partial failures, and a dead-letter queue change the design.

`S3` · `SQS` · `Lambda` · `CloudWatch`

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/yourclouddude/terraform-aws-three-tier-web-stack"><img src="./assets/project-terraform.svg" width="100%" alt="Terraform three-tier AWS stack: a public load balancer leads to private application and database tiers." /></a>

**[Terraform AWS Three-Tier Web Stack](https://github.com/yourclouddude/terraform-aws-three-tier-web-stack)**

Trace a request from a public ALB to private EC2 and RDS. Explore security groups, network boundaries, and the choice to leave NAT out of the base stack.

`Terraform` · `VPC` · `EC2` · `RDS PostgreSQL`

</td>
<td width="50%" valign="top">

<a href="https://github.com/yourclouddude/python-safe-file-organizer"><img src="./assets/project-python.svg" width="100%" alt="Python safe file organizer: preview a move plan before applying it, keep a manifest, and support undo." /></a>

**[Python Safe File Organizer](https://github.com/yourclouddude/python-safe-file-organizer)**

Automate a messy folder with a read-only plan, collision-safe names, a move manifest, and rollback. Learn what an undo command can and cannot promise.

`Python` · `CLI` · `pytest` · `GitHub Actions`

</td>
</tr>
</table>

### Start small with Python

The **[Python Project Showcase](https://github.com/yourclouddude/python-project-showcase)** has four local builds: an expense tracker, a bookstore API, an invoice generator, and a portfolio generator. Start with sample input, inspect the output, then work through the practice exercises.

## Tools on my workbench

<img src="./assets/toolbelt.svg" width="100%" alt="AWS: Lambda, S3, SQS. Python: CLI, APIs, pytest. Terraform: VPC, EC2, RDS. Delivery: SAM, Git, GitHub Actions." />

My focus is **serverless and event-driven AWS**, **Python tools and APIs**, and **infrastructure as code**. The projects make room for failure handling, IAM boundaries, testing, cleanup, and cost trade-offs alongside the working implementation.

## Open the experiment notebook

<details>
<summary><b>Break an assumption. Follow the evidence.</b></summary>
<br />

<img src="./assets/experiment.svg" width="100%" alt="The best test of a project? Change one assumption. Explain what happens." />

These are experiments to try, with the question each one should help you answer:

| Project | Try this | Explain what you observe |
| --- | --- | --- |
| URL shortener | Request a link whose expiration has passed, before TTL cleanup removes it. | Why must the redirect handler check expiration itself? |
| Image pipeline | Send a corrupt image alongside valid images. | How does partial batch failure keep good work from retrying? |
| Three-tier stack | Block the application's path to the database. | Why can the load balancer still see a healthy web process? |
| File organizer | Create a file with a name that already exists at the destination. | How does the plan protect the existing file? |

Use the repository instructions to run an experiment and clean up afterward. Write down your prediction first, then compare it with the result.

</details>

<details>
<summary><b>Where should I start?</b></summary>
<br />

- **New to Python projects?** Start with the [expense tracker](https://github.com/yourclouddude/python-project-showcase/tree/main/projects/06) and follow the sample data.
- **Want a first serverless system?** Try the [URL shortener](https://github.com/yourclouddude/aws-serverless-url-shortener) and trace one request.
- **Curious about async systems?** Open the [image pipeline](https://github.com/yourclouddude/aws-event-driven-image-pipeline) and ask why the queue is there.
- **Want to understand AWS networking?** Read the [three-tier stack](https://github.com/yourclouddude/terraform-aws-three-tier-web-stack) and follow the security group rules.

</details>

## Keep building with me

Find guides and more projects at **[yourclouddude.com](https://yourclouddude.com/)**, follow **[@yourclouddude on X](https://x.com/yourclouddude)**, or browse **[all my repositories](https://github.com/yourclouddude?tab=repositories)**.

<a href="https://yourclouddude.com/"><img src="./assets/footer.svg" width="100%" alt="See you in the next build. Visit yourclouddude.com." /></a>
