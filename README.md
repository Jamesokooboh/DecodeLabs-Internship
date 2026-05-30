# DecodeLabs-Internship

Welcome to the **DecodeLabs-Internship** repository. This repository contains projects, assignments, and practical implementations completed during the DecodeLabs Internship program, with a focus on Cloud Engineering, DevOps, and Infrastructure Automation.

## Overview

The goal of this repository is to document hands-on experience gained through real-world tasks and projects involving modern cloud and DevOps technologies.

Project 1: Linux & Command Line Basics

​Objective: Shift from a passive graphical interface (GUI) user to an active terminal operator, establishing low-level system configuration capabilities.
​Key Requirements Executed
​Filesystem Navigation & Orientation: Leveraged pwd for contextual safety before execution. Utilized cd alongside navigational shortcuts (~, .., -) and evaluated deep folder maps using advanced ls flags (-l, -a, -R).
​File & Directory Engineering: Constructed a production-grade nested file tree natively using mkdir -p /app/src/main to bypass iterative folder setup. Populated code infrastructure using touch, cp, mv, and managed resource purging securely with rm.
​FHS Architecture Mapping: Studied and verified the system blueprints of critical core directories:
​/ (The Root Zero-Point), /bin & /sbin (Essential Binaries), /etc (System Blueprints), /var (Variable Logs/Data), /tmp (The System Scratchpad), /home (Standard User Home), and /root (Protected Administrator Space).
​Deliverables Inside Portfolio
​Project-1-Linux/logs/terminal_execution.txt: Live shell logs demonstrating clean terminal navigation and successful nested directory structure expansion.
​
Project 2: Version Control with Git
​Objective: Transition from static storage to full lifecycle collaboration, auditability, tracking changes, and establishing a remote Source of Truth.
​Key Requirements Executed
​Cryptographic Ledger Initialization: Formulated a localized tracking mechanism running git init within the directory sandbox.
​Managing the Three Trees: Internalized and manipulated code variations across the distinct structural zones:
​The Working Tree: Experimental and unsafe scratchpad area.
​The Staging Area (Index): The curated loading dock for proposing snapshot states using git add.
​The HEAD (Repository): The permanent, immutable ship's ledger using git commit.
​Diagnostic Integrity Tracking: Used git status as a continuous system dashboard and executed git diff to analyze state differentials between tree layers before sealing history.
​Commit Engineering: Applied proper architectural guidelines to commits, utilizing precise 40-character SHA-1 hash tracking combined with strictly imperative verb messages (e.g., 'Fix login bug', 'Add linting step').
​Centralized Hub Syncing: Interlinked localized nodes to a remote master grid on GitHub using code isolation branches, pull requests, and resolving incoming merge conflicts manually.
​Deliverables Inside Portfolio
​This active, multi-commit GitHub Repository containing structured tracking history with clear, semantic execution records.
​
Project 3: CI/CD Pipeline Basics
​Objective: Engineer an automated software factory by building a digital conveyor belt that builds, tests, and validates code integrity via pure automation logic.
​Key Requirements Executed
​Pipeline Architecture Design: Visualized and mapped out a structural factory assembly line blueprint processing code through strict checkpoints: Code ➔ Build ➔ Test ➔ Deploy.
​Orchestration Logic Configuration: Mastered and structured workflow components inside YAML schemas:
​Workflows: The top-level master conveyor configurations.
​Events/Triggers: Automated catalysts mapping tasks directly to repository actions (push, pull_request).
​Jobs: Parallel assembly lines designed to maximize system deployment speed.
​Steps: Granular individual instruction tasks interacting with localized run environment layers.
​Advanced Continuous Integration Guardrails: Scaled automated logic past elementary code saves by building out automated code quality enforcement tasks (e.g., Code Linting Steps to monitor layout bugs) and automated system notifications tracking failure events.
​Deliverables Inside Portfolio
​.github/workflows/ci-cd-pipeline.yml: Complete functional pipeline orchestration configuration script running targeted automation rules.


## Contributions

This repository is primarily for internship learning and project tracking. Suggestions and improvements are welcome.

## Author

James Okooboh
Cloud & DevOps Engineer Enthusiast
