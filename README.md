# 02-LPI-Linux-Essentials

## Overview

This repository documents my preparation for the **LPI Linux Essentials** certification. It includes study notes, command practice, hands-on Linux labs, weak-area review, troubleshooting notes, and certification preparation evidence.

The goal of this repository is to build a strong Linux foundation for IT Support, Systems Administration, Networking, Cloud Engineering, and DevSecOps.

---

## Purpose

Linux is a core skill across IT infrastructure, cloud platforms, cybersecurity, networking, and DevOps. This repository is used to document my progress as I strengthen my Linux fundamentals through hands-on practice and structured certification review.

This repository supports my current roadmap phase:

* LPI Linux Essentials
* IT Support Specialist Foundation
* Future LPIC-1 preparation
* Future cloud and infrastructure labs

---

## Certification Goal

**Certification:** LPI Linux Essentials
**Exam:** 010-160
**Status:** In Progress
**Goal:** Pass Linux Essentials and build a strong foundation before moving deeper into Linux administration and LPIC-1.

---

## Current Focus Areas

This repository focuses on the following Linux Essentials domains:

1. Linux Evolution and Popular Operating Systems
2. Major Open Source Applications
3. Open Source Software and Licensing
4. ICT Skills and Working in Linux
5. Command Line Basics
6. Getting Help
7. Using Directories and Listing Files
8. Creating, Moving, and Deleting Files
9. Archiving and Compression
10. Searching and Extracting Data
11. Turning Commands into Scripts
12. Understanding Computer Hardware
13. Where Data is Stored
14. Network Configuration
15. System Security
16. Users and Groups
17. File Permissions and Ownership

---

## Hands-On Lab Environment

Current Linux practice environment:

* Ubuntu Desktop
* Linux terminal
* Virtualized lab environment
* Proxmox homelab environment
* Windows + Linux infrastructure practice

---

## Repository Structure

```text
02-LPI-Linux-Essentials
│
├── README.md
├── docs/
├── notes/
├── commands/
├── labs/
├── screenshots/
├── troubleshooting/
└── review-quizzes/
```

---

## Folder Purpose

| Folder             | Purpose                                           |
| ------------------ | ------------------------------------------------- |
| `docs/`            | Written study documentation and explanations      |
| `notes/`           | Topic notes and weak-area review                  |
| `commands/`        | Linux command examples and explanations           |
| `labs/`            | Hands-on Linux practice labs                      |
| `screenshots/`     | Screenshots proving completed labs                |
| `troubleshooting/` | Linux troubleshooting examples                    |
| `review-quizzes/`  | Quiz notes, missed questions, and review evidence |

---

## Key Commands Practiced

This repository will document practice with commands such as:

```bash
pwd
ls
cd
mkdir
touch
cp
mv
rm
cat
less
head
tail
grep
find
tar
zip
unzip
chmod
chown
ps
top
kill
ip
ping
man
history
```

---

## Important Linux Skills Being Built

* Navigating the Linux filesystem
* Understanding absolute and relative paths
* Managing files and directories
* Viewing and editing text files
* Searching files and command output
* Understanding users and groups
* Managing permissions
* Understanding ownership
* Using compression and archiving tools
* Understanding basic networking commands
* Reading system information
* Practicing command-line troubleshooting

---

## Weak Areas to Strengthen

Current focus areas for improvement:

* File permissions
* User and group management
* Archiving and compression
* Process management
* UID and GID concepts
* Command-line options
* Linux directory structure
* Security basics
* Network commands
* Package management concepts

---

## Troubleshooting Documentation Format

Each Linux troubleshooting note should follow this structure:

```text
Issue:
Symptoms:
Command Used:
Expected Result:
Actual Result:
Root Cause:
Resolution:
What I Learned:
```

---

## Example Troubleshooting Scenario

```text
Issue:
A user cannot execute a script.

Symptoms:
The script exists, but running ./script.sh returns "Permission denied."

Command Used:
ls -l script.sh

Root Cause:
The script does not have execute permission.

Resolution:
chmod +x script.sh

What I Learned:
Linux files require execute permission before they can be run as scripts.
```

---

## Resume Impact

This repository supports resume bullets such as:

```text
Built Linux command-line skills through hands-on Ubuntu labs covering file management, permissions, users/groups, process management, networking commands, archiving, compression, and troubleshooting.
```

---

## Current Status

Status: Active

This repository will be updated as I continue Linux Essentials preparation, complete labs, document commands, and prepare for the certification exam.
