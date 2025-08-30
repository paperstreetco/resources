---
title: DevOps Learning Resources
date: 2025-08-29
draft: false
author: Alex Kraker github.com/kraker
---

# DevOps Learning Resources

**Author:** Alex Kraker [@kraker](https://github.com/kraker)\
**Updated:** 2025-08-29

This is a curated collection of the DevOps learning resources that I've found
to be the most useful or that my friends in the industry have recommended to me.
Those with a ✅ are what I consider to be _best in class_ for the topic they
cover and are most often my go-to recommendations.

## Table of Contents

- [Getting Started](#getting-started)
  - [Points of Entry](#points-of-entry)
  - [DevOps Books](#devops-books)
- [Infrastructure](#infrastructure)
  - [Cloud Platforms](#cloud-platforms)
  - [Virtualization](#virtualization)
- [Containerization & Orchestration](#containerization--orchestration)
  - [Containerization](#containerization)
  - [Container Orchestration](#container-orchestration)
- [Automation & Configuration Management](#automation--configuration-management)
  - [CI/CD Platforms & Pipelines](#cicd-platforms--pipelines)
  - [Configuration Management (CaC)](#configuration-management-cac)
  - [Infrastructure as Code (IaC)](#infrastructure-as-code-iac)
  - [Image Building & Provisioning](#image-building--provisioning)
  - [Orchestration & Workflow](#orchestration--workflow)
- [Development & Version Control](#development--version-control)
  - [Programming Languages](#programming-languages)
  - [Source Code Management](#source-code-management)
  - [Regular Expressions](#regular-expressions)
- [Networking](#networking)
  - [TCP/IP & Protocols](#tcpip--protocols)
  - [Routing & NAT](#routing--nat)
  - [IP Addressing & Subnetting](#ip-addressing--subnetting)
  - [DNS](#dns)
- [Systems Administration](#systems-administration)
  - [Unix & Linux](#unix--linux)
    - [General Linux Resources](#general-linux-resources)
    - [Enterprise Linux](#enterprise-linux)
    - [Bash & Linux CLI](#bash--linux-cli)
  - [Windows](#windows)
- [Security & Compliance](#security--compliance)
  - [Security Fundamentals](#security-fundamentals)
  - [Linux Security Hardening](#linux-security-hardening)
  - [Cloud Security](#cloud-security)
  - [Container Security](#container-security)
  - [DevSecOps Practices](#devsecops-practices)
  - [Compliance & Auditing](#compliance--auditing)
  - [Security Information & Event Management (SIEM)](#security-information--event-management-siem)
- [Site Reliability Engineering](#site-reliability-engineering)
- [Monitoring & Observability](#monitoring--observability)
  - [Metrics & Visualization](#metrics--visualization)
  - [Log Management & Analysis](#log-management--analysis)
- [Knowledge Management](#knowledge-management)
  - [Documentation](#documentation)
  - [Note Taking](#note-taking)
- [Meta Resources](#meta-resources)

# Getting Started

## Points of Entry

DevOps points of entry - not sure where to start? Start here:

* [roadmap.sh \| DevOps Roadmap](https://roadmap.sh/devops)
* [Reddit \| Getting into DevOps](https://www.reddit.com/r/devops/comments/yjdscp/getting_into_devops/?utm_source=share&utm_medium=web2x&context=3)

## DevOps Books

General books on DevOps as a whole. What exactly is DevOps anyways? Nobody is really sure, but these resources may elucidate.

* ✅ [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](https://itrevolution.com/product/the-phoenix-project/) by Gene Kim
* [The Unicorn Project: A Novel about Digital Disruption, Developers, and Overthrowing the Ancient Powerful Order](https://itrevolution.com/product/the-unicorn-project/) by Gene Kim
* [The DevOps Handbook: How to Create World-Class Agility, Reliability, & Security in Technology Organizations](https://itrevolution.com/product/the-devops-handbook-second-edition/) by Gene Kim, et al.

# Infrastructure

## Cloud Platforms

### AWS

*Resources coming soon*

### Azure

*Resources coming soon*

### GCP

*Resources coming soon*

## Virtualization

### VMware

*Resources coming soon*

### VirtualBox

*Resources coming soon*

### Proxmox VE

*Resources coming soon*

# Containerization & Orchestration

## Containerization

### Docker

* [CLI Cheat Sheet](https://docs.docker.com/get-started/docker_cheatsheet.pdf) – Docker
* [Docker Mastery](https://www.udemy.com/course/docker-mastery/) – Udemy
* [Docker Deep Dive](https://nigelpoulton.com/books/) by Nigel Poulton

### Podman

Podman is basically Docker but it's FOSS, and has batteries included.

## Container Orchestration

Beware, here be dragons. Container orchestration is not for the faint of heart.
These resources may help make the complexity deamons manageable at least.

### Kubernetes

Kubernetes (k8s) is the de facto standard for container orchestration. Developed
by the Trekie's at Google and born out something they called Borg. Resistence
is futile! You will be assimilated!

* ✅ [The Kubernetes Book](https://nigelpoulton.com/books/) by Nigel Poulton
* [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way) – Free Tutorial
* [KodeKloud.com](https://kodekloud.com/) – Learn-by-doing Platform
* [Kubectl cheat sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/) – Kubernetes

### OKD/OpenShift

*Resources coming soon*

# Automation & Configuration Management

## CI/CD Platforms & Pipelines

### General CI/CD Resources

_Resources coming soon_

### Jenkins

_Resources coming soon_

### GitLab CI/CD

_Resources coming soon_

### GitHub Actions

_Resources coming soon_

### Azure DevOps

_Resources coming soon_

## Configuration Management (CaC)

### Ansible

#### Documentation & Tutorials

- Official [Ansible Documentation](https://docs.ansible.com/ansible/latest/index.html)
- [Getting started with Ansible](https://docs.ansible.com/ansible/latest/getting_started/index.html) – Ansible

#### Books & Courses

- ✅ [Ansible for DevOps](https://www.ansiblefordevops.com/) by Jeff Geerling\
  _This is the single best resource for learning Ansible that I've found._
- [Ansible Up & Running](https://www.oreilly.com/library/view/ansible-up-and/9781098109141/) by Bas Meijer, Lorin Hochstein, and René Moser
- [Ansible for the Absolute Beginner](https://www.udemy.com/course/learn-ansible/) – Udemy

#### Videos & Interactive

- [Getting Started with Ansible](https://www.youtube.com/playlist?list=PLT98CRl2KxKEUHie1m24-wkyHpEsa4Y70) – LearnLinuxTV
- [Ansible 101](https://youtube.com/playlist?list=PL2_OBreMn7FqZkvMYt6ATmgC0KAGGJNAN) by Jeff Geerling

### Salt

_Resources coming soon_

### Puppet

_Resources coming soon_

### Chef

_Resources coming soon_

## Infrastructure as Code (IaC)

### Terraform

_Resources coming soon_

### OpenTofu

_Resources coming soon_

### Pulumi

_Resources coming soon_

### AWS CloudFormation

_Resources coming soon_

### Azure Resource Manager

_Resources coming soon_

## Image Building & Provisioning

### Packer

- [Official Packer Documentation](https://developer.hashicorp.com/packer/docs)
- [Packer Tutorial](https://developer.hashicorp.com/packer/tutorials) – HashiCorp Learn

### Vagrant

_Resources coming soon_

## Orchestration & Workflow

### Apache Airflow

_Resources coming soon_

### Argo Workflows

_Resources coming soon_

# Development & Version Control

## General Development

* ✅ [The Grug Brained Developer](https://grugbrain.dev/)
* [Unix as IDE](https://blog.sanctum.geek.nz/series/unix-as-ide/)

## Programming Languages

### Python

#### Documentation & Tutorials

- [Python Cheat Sheet](https://www.pythoncheatsheet.org/)
- [Official Tutorial](https://docs.python.org/3/tutorial/index.html)
- [Python Challenge](http://www.pythonchallenge.com/)
- [Python Tutor](https://pythontutor.com/)

#### Books & Courses

- ✅ [Automate the Boring Stuff](https://automatetheboringstuff.com/) by Al Sweigart
- [Learn Python the Hard Way](https://learncodethehardway.org/python/) by Zed Shaw
- [Think Python](https://open.umn.edu/opentextbooks/textbooks/43) by Allen B. Downey

#### Videos & Interactive

- [Learn Python with Socratica](https://youtu.be/bY6m6_IIN94) – YouTube
- [Python Object Oriented Programming (OOP) - For Beginners](https://youtu.be/JeznW_7DlB0) – YouTube

## Source Code Management

Version control and release management practices.

* [Semantic Versioning](https://semver.org/)

### Git

#### Documentation & Tutorials

- Official [Git Documentation](https://git-scm.com/docs)
- ✅ [Git Cheat Sheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet) – Atlassian
- ✅ [git - the simple guide](https://rogerdudler.github.io/git-guide/) by Roger Dudler
- [How to Write a Git Commit Message](https://cbea.ms/git-commit/)
- [gittutorial](https://git-scm.com/docs/gittutorial) – Git
- [giteveryday](https://git-scm.com/docs/giteveryday) – Git

#### Books & Courses

- [Pro Git](https://git-scm.com/book/en/v2) by Scott Chacon and Ben Straub

#### Videos & Interactive

- [Version Control (Git)](https://missing.csail.mit.edu/2020/version-control/) – MIT: _Missing Semester_

## Regular Expressions

* ✅ [RegexOne](https://regexone.com/) – Online tutorial\
  _This is a great intro to RegEx that you can probably get through in a couple
  of hours._

# Networking

## General Networking Resources

* ✅ [Computer Networking: A Top-Down Approach](https://www.pearson.com/en-us/subject-catalog/p/computer-networking/P200000003334/9780136681557) by James F. Kurose\
  _If you only consume one resource on computer networking, read this._
* [Professor Messer's CompTIA N10-008 Network+ Course](https://www.professormesser.com/network-plus/n10-008/n10-008-video/n10-008-training-course/) – Video Course
* [Networking for System Administrators](https://mwl.io/nonfiction/networking) by Michael W Lucas

## TCP/IP & Protocols

_The [Internet Protocol suite](https://en.wikipedia.org/wiki/Internet_protocol_suite)._

_Resources coming soon_

## Routing & NAT

### NAT

* [What is NAT?](https://www.comptia.org/content/guides/what-is-network-address-translation "https://www.comptia.org/content/guides/what-is-network-address-translation") – CompTIA

## IP Addressing & Subnetting

Network segmentation and IP addressing fundamentals.

### Subnetting

* [What is a subnet? | How subnetting works | Cloudflare](https://www.cloudflare.com/learning/network-layer/what-is-a-subnet/) – Cloudflare
* [Seven-Second Subnetting](https://youtu.be/SWy0MRfkXpQ "https://youtu.be/SWy0MRfkXpQ") by Professor Messer – YouTube
* [What is a DMZ Network?](https://www.fortinet.com/resources/cyberglossary/what-is-dmz "https://www.fortinet.com/resources/cyberglossary/what-is-dmz") – Fortinet

### CIDR & IP Address Classes

_Classless Inter-Domain Routing_

* [What is CIDR?](https://aws.amazon.com/what-is/cidr/) – AWS
* [Classful addressing](https://en.wikipedia.org/wiki/Classful_network#Classful_addressing_definition) – Wikipedia
* [Reserved IP addresses](https://en.wikipedia.org/wiki/Reserved_IP_addresses) – Wikipedia

## DNS

Cloudflare has published some quality articles on DNS from a conceptual overview standpoint.

Start with these:

* [What is DNS? | How DNS works | Cloudflare](https://www.cloudflare.com/learning/dns/what-is-dns/)
* [What is a domain name? | Domain name vs. URL | Cloudflare](https://www.cloudflare.com/learning/dns/glossary/what-is-a-domain-name/)
* [DNS server types | Cloudflare](https://www.cloudflare.com/learning/dns/dns-server-types/)
* [What is a DNS zone? | Cloudflare](https://www.cloudflare.com/learning/dns/glossary/dns-zone/)
* [What are DNS records? | Cloudflare](https://www.cloudflare.com/learning/dns/dns-records/)

# Systems Administration

## General Systems Administration

* [The Practice of System and Network Administration: DevOps and other Best Practices for Enterprise IT, Volume 1](https://the-sysadmin-book.com/) By Thomas A. Limoncelli, et al.

## Unix & Linux

### General Linux Resources

#### Tutorials

* [Linux Upskill Challenge](https://linuxupskillchallenge.org/)\
  Level up your Linux skills to Jr. Linux Administrator in month's worth of
  daily challenges. I'm a contributor on this
  [project](https://github.com/livialima/linuxupskillchallenge) and am active
  on the
  [Discord](https://discord.gg/linux-upskill-challenge-682046666928685068).

#### Books

* [Unix and Linux System Administration Handbook](https://www.admin.com/) by Evi Nemeth, et al.
* [Systems Performance: Enterprise and the Cloud, 2nd Edition](https://www.brendangregg.com/systems-performance-2nd-edition-book.html) by Brendan Gregg
* [Sudo Mastery](https://mwl.io/nonfiction/tools) by Michael W. Lucas

### Enterprise Linux

#### Red Hat Enterprise Linux (RHEL)

##### RHCSA Certification

Red Hat Certified System Administrator - fundamental Linux system administration skills.

###### Documentation & Tutorials

- [RHCSA Exam Objectives](https://www.redhat.com/en/services/training/ex200-red-hat-certified-system-administrator-rhcsa-exam) – Red Hat
- [Red Hat Certified System Administrator overview](https://www.reddit.com/r/linux/comments/s845x2/red_hat_certified_system_administrator_overview/) – Reddit
- [RHCSA study materials](https://www.reddit.com/r/redhat/comments/8arqd9/rhcsa_study_materials/) – Reddit
- [Best courses with hands-on labs for RHCSA](https://www.reddit.com/r/linuxadmin/comments/14zazsx/what_are_the_best_courses_with_hands_on_labs_to/) – Reddit

###### Books & Courses

- [RHCSA Red Hat Enterprise Linux 9: Training and Exam Preparation Guide (EX200), Third Edition](https://www.amazon.com/RHCSA-Enterprise-Linux-Training-Preparation/dp/1803243074) by Asghar Ghori\
  _Good source. This source is more linux admin flavored, CLI-centric which I think more accurately reflects sysadmin day-to-day. The user is encouraged to "learn-by-doing" while following along... this is a solid approach to building muscle memory for the CLI I've found._

- [Red Hat RHCSA 9 Cert Guide EX200](https://www.ciscopress.com/store/red-hat-rhcsa-9-cert-guide-ex200-9780138096335) by Sander van Vugt\
  _Good source. Sander Van Vugt's courses are considered the defacto standard for prep, but I'm not sure if the book is as good as the courses... this source does seem to have better practical tips. For example, recommending using dnf provides to find what package needs to be installed to provide a command, and what man pages to refer to rather than memorizing complex or arcane syntax, such as semanage fcontext -a -t .... Some topics are not as complete and the coverage focuses on just what's needed for the exam. But exercises seem to be more relevant to what you're likely to actually encounter on the exam._

###### Videos & Interactive

- [RHCSA RHEL 9 Complete Video Course](https://www.pearsonitcertification.com/store/red-hat-rhcsa-rhel-9-complete-video-course-9780138097714) by Sander van Vugt\
  _I didn't buy the course since I tend to prefer books over video lecture style courses. But this is considered by many to be the defacto standard when it comes to studying for the RHCSA exams. The book above comes with a pretty significant discount, so I recommend buying the book for the coupon._

- [RHCSA Guru](https://www.rhcsaguru.com/)\
  _I haven't tried this yet, but hands-on labs may be worth the price of admission..._

##### RHCE Certification

Red Hat Certified Engineer - focuses on Ansible automation (90% Ansible-based since RHEL 8).

###### Documentation & Tutorials

_Resources coming soon_

###### Books & Courses

- [Red Hat RHCE 8 (EX294) Cert Guide](https://www.ciscopress.com/store/red-hat-rhce-8-ex294-cert-guide-9780135656495) by Sander van Vugt\
  _A bit outdated. Refers to Ansible Tower instead of AAP. Based on RHEL 8 but current exam is RHEL 9. But Sander van Vugt's courses and books are still considered the defacto standard for preparing for both RHCSA and RHCE. His courses may be better, but I'm not 100% sold on how the content is structured in his books... it doesn't resonate as well with me compared to other written learning materials I've used._

- [Red Hat Certified Engineer (RHCE) Ansible Automation Study Guide](https://developers.redhat.com/e-books/red-hat-certified-engineer-rhce-ansible-automation-study-guide) – Red Hat Developer\
  _Free with developer subscription. A good overview of the objectives, but it's breadth vs depth. Probably best as a supplementary study source. Seems like Red Hat is trying to sell you courses, AAP, etc. by giving away this ebook for free._

- ✅ [Ansible for DevOps](https://www.ansiblefordevops.com/) by Jeff Geerling\
  _Still one of the best sources out there on learning Ansible IMO. But not directed at RHCE specifically._

###### Videos & Interactive

_Resources coming soon_

### Bash & Linux CLI

#### Documentation & Tutorials

- [Bash Reference Manual](https://www.gnu.org/software/bash/manual/bash.html)
- [Greg's Wiki](https://mywiki.wooledge.org/)
- ✅ [Command Line Crash Course](https://learnpythonthehardway.org/book/appendixa.html) – Learn Python the Hard Way
- [Learning the Shell](https://linuxcommand.org/lc3_learning_the_shell.php) by William Shotts
- [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)
- [explainshell.com](https://explainshell.com/)

#### Books & Courses

- ✅ [The Linux Command Line](https://linuxcommand.org/tlcl.php) by William Shotts
- [Linux Command Line and Shell Scripting Bible](https://www.wiley.com/en-us/Linux+Command+Line+and+Shell+Scripting+Bible,+4th+Edition-p-9781119700937) by Richard Blum & Christine Bresnahan

#### Videos & Interactive

- [The Shell](https://missing.csail.mit.edu/2020/course-shell/) – MIT: _Missing Semester_
- [Linux Commands for Beginners](https://youtube.com/playlist?list=PLT98CRl2KxKHaKA9-4_I38sLzK134p4GJ) – LearnLinuxTV
- [Linux Crash Course - Public Key Authentication (SSH)](https://youtu.be/bfwfRCCFTVI) – LearnLinuxTV

#### Bash Scripting

- [Bash scripting cheatsheet](https://devhints.io/bash) – Devhints
- [Shell Style Guide](https://google.github.io/styleguide/shellguide.html) – Google

## Windows

* [Learn Windows PowerShell in a Month of Lunches](https://www.manning.com/books/learn-powershell-in-a-month-of-lunches) by Travis Plunk, et al.

# Security & Compliance

## Security Fundamentals

### Security Frameworks & Standards

_Resources coming soon_

### Risk Management & Threat Modeling

_Resources coming soon_

## Linux Security Hardening

### RHEL/Enterprise Linux Hardening

_Resources coming soon_

### General Linux Security

_Resources coming soon_

## Cloud Security

### Cloud Security Fundamentals

_Resources coming soon_

### AWS Security

_Resources coming soon_

### Azure Security

_Resources coming soon_

### GCP Security

_Resources coming soon_

## Container Security

### Docker Security

_Resources coming soon_

### Kubernetes Security

_Resources coming soon_

### Image Scanning & Vulnerability Management

_Resources coming soon_

## DevSecOps Practices

### Security in CI/CD

_Resources coming soon_

### Infrastructure as Code Security

_Resources coming soon_

### Secrets Management

_Resources coming soon_

### Supply Chain Security

_Resources coming soon_

## Compliance & Auditing

### Compliance Frameworks

_Resources coming soon_

### Security Scanning & Auditing Tools

_Resources coming soon_

### Policy as Code

_Resources coming soon_

## Security Information & Event Management (SIEM)

_Resources coming soon_

# Site Reliability Engineering

## SRE Fundamentals

- ✅ [Google | SRE Books](https://sre.google/books/) – The definitive SRE resources
  - Site Reliability Engineering (The original "SRE Book")
  - The Site Reliability Workbook (Practical implementation)
  - Building Secure and Reliable Systems

# Monitoring & Observability

## Metrics & Visualization

### Grafana

_Resources coming soon_

### Prometheus

_Resources coming soon_

## Log Management & Analysis

### Splunk

_Resources coming soon_

### Graylog

_Resources coming soon_

# Knowledge Management

## Documentation

### Docs as Code

- ✅ [Docs as Code at Linode](https://www.linode.com/blog/linode/docs-as-code-at-linode/#:~:text=Docs%20as%20code%20is%20a,Writing%20plain%2Dtext%20documentation%20files)
- [Write the Docs: Docs as Code](https://www.writethedocs.org/guide/docs-as-code/)

### Markdown

- ✅ [The Markdown Guide](https://www.markdownguide.org/)
- [Official Markdown Specification](https://daringfireball.net/projects/markdown/)
- [MermaidJS](https://mermaid.js.org/) - Extended support for flow-charts, diagrams, etc. in Markdown files

## Note Taking

_Taking notes is akin to managing a personal "knowledge base"._

Making a habit out of taking notes is one of the single greatest force-multipliers for the IT professional. Every exceptional developer, sysadmin, engineer, etc that I've worked with was a note-taker. The methodologies used doesn't seem to matter so much, but taking notes does.

- [How to Take Smart Notes](https://www.soenkeahrens.de/en/takesmartnotes) by Sönke Ahrens
- [The Zettelkasten Method](https://zettelkasten.de/posts/overview/)\
  _This is the method that I (mostly) use. See my [second brain](https://notes.kraker.dev/) as an example._
- [Obsidian](https://obsidian.md/)\
  Markdown note-taking tool. Supports Zettelkasten methodologies. This is what
  I'm currently using, although I've also used Vim, Emacs, and explored various
  other tools and text-editors in the past.

# Meta Resources

- ✅ [Teach Yourself Computer Science](https://teachyourselfcs.com/)\
  Best in-class books and courses for learning Computer Science (CS).
- [Open Source Society University (OSSU)](https://github.com/ossu)
- [Code](https://www.charlespetzold.com/books/) by Charles Petzold
