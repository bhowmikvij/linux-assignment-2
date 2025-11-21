# Linux Assignment 2

## Overview

This project demonstrates practical Linux setup, basic command usage, and automation using shell scripts in an Ubuntu virtual environment. The assignment guides users from OS installation on VirtualBox to running essential Linux commands and automating tasks with bash scripts.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation Steps](#installation-steps)
- [Linux Commands Covered](#linux-commands-covered)
- [Shell Scripts](#shell-scripts)
- [Challenges Faced](#challenges-faced)
- [Learning Outcomes](#learning-outcomes)
- [Author](#author)

## Introduction

The purpose of this assignment is to help users:

- Install and configure Ubuntu in VirtualBox
- Allocate system resources safely
- Learn basic Linux commands
- Automate tasks using shell scripting

## Requirements

- **VirtualBox** (latest version)
- **Ubuntu ISO** (latest desktop version)
- Basic knowledge of command line interface

## Installation Steps

1. Download and install [VirtualBox](https://www.virtualbox.org)
2. Download the latest [Ubuntu Desktop ISO](https://ubuntu.com/download/desktop)
3. Create a new VM in VirtualBox and configure settings (RAM, storage)
4. Attach the Ubuntu ISO and follow the installation steps
5. After installation, boot into Ubuntu and open the terminal

## Linux Commands Covered

| Command    | Purpose                                  |
|------------|------------------------------------------|
| ls         | List files and directories               |
| cd         | Change working directory                 |
| pwd        | Print current directory path             |
| tree       | Show directory structure                 |
| mkdir      | Create new directory                     |
| touch      | Create a new/empty file                  |
| cp         | Copy files or directories                |
| mv         | Move or rename files/directories         |
| rm         | Remove files/directories                 |
| chmod      | Change file permissions                  |
| chown      | Change file ownership                    |
| ps, top    | Process monitoring                       |
| kill       | Terminate a process                      |
| ping       | Test network connectivity                |
| ifconfig   | Display network interfaces               |
| ip, netstat| Get IP info, show open ports             |

## Shell Scripts

- **backup.sh**: Copies a directory to a backup folder with a timestamp
- **monitor.sh**: Logs CPU and memory usage every 10 seconds
- **download.sh**: Downloads a file using `wget` to a specified directory

### Example Usage

Make scripts executable
chmod +x backup.sh monitor.sh download.sh

Run backup script
./backup.sh

Run monitor script
./monitor.sh

Run download script (edit script with your desired URL/path)
./download.sh

## Challenges Faced

- Configuring VirtualBox settings for optimal performance
- Handling Linux file permissions when executing scripts
- Debugging syntax errors in bash scripts
- Understanding and using a variety of shell commands efficiently

## Learning Outcomes

- Hands-on experience with Linux installation and navigation
- Practical skills in bash scripting and process automation
- Understanding permission management and process monitoring
- Exposure to open-source tools and collaboration via GitHub

## Author

**Bhowmik Vij**  
Roll No: 2501010195  
Section D  
Course: Computer Science Fundamentals  
Instructor: Dr. Ravinder Beniwal

---

**GitHub Repository**: [linux-assignment-2](https://github.com/bhowmikvij/linux-assignment-2.git)
