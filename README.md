# DevOps Internship Portfolio

## Overview

This repository contains the practical projects completed during my DevOps Industrial Training program with DecodeLabs. The projects demonstrate foundational competencies in Linux system administration, Git version control, and CI/CD automation.

The objective of this portfolio is to showcase hands-on experience with core DevOps practices, industry-standard tools, and automation workflows used throughout the Software Development Lifecycle (SDLC).

---

## Projects Completed

### Project 1: Linux & Command Line Basics

#### Objective

Transition from graphical user interface (GUI) usage to effective command-line operations and system navigation.

#### Skills Demonstrated

* Linux filesystem navigation
* Directory and file management
* Understanding the Linux Filesystem Hierarchy Standard (FHS)
* Terminal-based system operations

#### Key Commands Used

* `pwd`
* `cd`
* `ls`
* `mkdir`
* `touch`
* `cp`
* `mv`
* `rm`

#### Deliverables

* Terminal execution logs
* Nested directory structure creation
* Linux filesystem exploration

---

### Project 2: Version Control with Git

#### Objective

Implement source code version control, change tracking, collaboration workflows, and repository management using Git and GitHub.

#### Skills Demonstrated

* Repository initialization
* Staging and committing changes
* Branch management
* Merge operations
* Pull Request workflow
* Conflict resolution
* Remote repository synchronization

#### Git Concepts Applied

* Working Tree
* Staging Area (Index)
* Repository (HEAD)

#### Commands Used

* `git init`
* `git add`
* `git commit`
* `git status`
* `git diff`
* `git branch`
* `git checkout`
* `git merge`
* `git push`
* `git pull`

---

### Project 3: CI/CD Pipeline Basics

#### Objective

Design and implement an automated workflow that validates code changes through Continuous Integration and Continuous Deployment principles.

#### Skills Demonstrated

* GitHub Actions
* Workflow automation
* YAML configuration
* Event-driven pipelines
* Build and test automation
* Pipeline orchestration

#### Pipeline Flow

Code → Build → Test → Deploy

#### Workflow Features

* Automated execution on push events
* Automated execution on pull requests
* Build stage
* Test stage
* Deployment simulation
* Workflow monitoring through GitHub Actions

#### Deliverable

* `.github/workflows/cicd-pipeline.yml`

---

# Project 4: Containerization with Docker

## Objective

Containerize an application using Docker to ensure consistent execution across different environments.

## Project Components

### Dockerfile

Defines the container blueprint using:

* FROM
* WORKDIR
* COPY
* CMD

### .dockerignore

Optimizes build performance by excluding unnecessary files from the build context.

## Build Process

Build the image:

```bash
docker build -t my-app:1.0 .
```

## Run Process

Launch the container:

```bash
docker run -d -p 8080:80 --name my-container my-app:1.0
```

## Verification

Access the application:

```text
http://localhost:8080
```

## Concepts Demonstrated

* Docker Images
* Docker Containers
* Layer Caching
* Port Mapping
* Detached Mode
* Container Networking
* Container Lifecycle Management

## Technologies Used

* Docker
* Nginx
* Alpine Linux


---
## Tools & Technologies

* Linux
* Git
* GitHub
* GitHub Actions
* YAML
* Bash Shell

---

## Repository Structure

```text
.
├── Project-1-Linux
├── Project-2-Version-Control
├── .github
│   └── workflows
│       └── ci-cd-pipeline.yml
└── README.md
```

---

## Learning Outcomes

Through these projects, I have gained practical experience in:

* Linux command-line operations
* Source code management
* Branching and collaboration workflows
* Continuous Integration concepts
* Continuous Deployment fundamentals
* Automation best practices
* DevOps workflow fundamentals

---

## Author

**James Okooboh**

DevOps Intern – DecodeLabs

2026
