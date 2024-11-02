# System Health Monitoring and Automated Backup Scripts

This repository contains two Python scripts:
1. **Automated Backup Script**: A script to automate the backup of a specified directory to a remote server or cloud storage solution.
2. **System Health Monitoring Script**: A script that monitors the health of a Linux system by checking CPU usage, memory usage, disk space, and running processes.

## Table of Contents
- [Requirements](#requirements)
- [Automated Backup Script](#automated-backup-script)
  - [Configuration](#configuration)
  - [Usage](#usage)
  - [Scheduling with Cron](#scheduling-with-cron)
- [System Health Monitoring Script](#system-health-monitoring-script)
  - [Configuration](#configuration-1)
  - [Usage](#usage-1)
  - [Scheduling with Cron](#scheduling-with-cron-1)
- [License](#license)

## Requirements
- Python 3.x
- `psutil` library (for the System Health Monitoring Script)
- `rsync` (for the Automated Backup Script)
- SSH access to the remote server (for the Automated Backup Script)

### Install psutil
You can install the required library using pip:
```bash
pip install psutil
