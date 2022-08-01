---
title: Deploy a high available web server in Azure,Terrafrom & packer
summary: Azure Infrastructure Operations Project Deploying a scalable IaaS web server in Azure.

tags:
- DevOps
date: "2022-07-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
- icon: linkdin
  icon_pack: fab
  name: Follow
  url: https://www.linkedin.com/in/dawit-anelay/
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

---

Infrastructure as code is one of the five practices that we consider the heart of DevOps. Infrastructure as code provides a significant benefit in terms of creating, deploying, upgrading, and deleting infrastructure. Infrastructure as code make the deployment procedure as simple as pressing a button.

Packer a server templating software written in JSON, will be used to create virtual machine images containing our application for repeatable deployments. Terraform is a provisioning tool that creates infrastructure according to a configuration file that you create. This file can be saved and reused which enables you to safely and predictably create, change, and improve infrastructure.

For this project, you will write a Packer template and a Terraform template to deploy a customizable, scalable web server in Azure.
