# Operating System Assessment – Saadiqbal

## Overview

This repository contains the completed assessment tasks for my Operating Systems course. 
The assessment covers:

- Part 1: Tasks using a GUI-based OS (Ubuntu Desktop)
- Part 2: Tasks using a CLI-based OS (Ubuntu Server)
- Part 3: A Python script for directory management

Screenshots and evidence are provided in the respective folders.

---

## Part 1 – GUI Tasks

**OS:** Ubuntu Desktop

**Tasks completed:**

- Installed a second hard drive
- Formatted and mounted the new drive
- Created a folder hierarchy
- Zipped a folder with password protection
- Set a static IP address
- Restarted a service
- Applied a firewall rule to block a browser
- Ran an antivirus scan

**Evidence:**

- Screenshots folder: `Part1_GUI_Screenshots/`
- Each screenshot shows task completion

---

## Part 2 – CLI Tasks

**OS:** Ubuntu Server (CLI only)

**Tasks completed:**

- Installed a second hard drive
- Formatted and mounted it via CLI
- Created a folder hierarchy using terminal commands
- Zipped a folder with a password using CLI
- Set a static IP address and DNS via terminal
- Restarted a service using `systemctl`
- Applied a firewall rule using `ufw` to block a browser
- Ran an antivirus scan using ClamAV

**Evidence:**

- Screenshots folder: `Part2_CLI_Screenshots/`
- Terminal outputs included

---

## Part 3 – Directory Management Script

**Language:** Python 3  
**Purpose:** Allows non-technical users to safely create, rename, and delete directories in predefined paths.

**Features:**

- Menu-driven interface:
  - Create a New Directory
  - Rename a Directory
  - Delete a Directory
  - Exit
- Restricted to a limited set of directories for safety
- Fully documented and tested

**Files:**

- `dir_manager.py` – the Python script
- `dir_manager_demo.html` – HTML export showing script execution (Colab or Jupyter Notebook)

**How to run:**

1. **Locally**:
   ```bash
   python3 dir_manager.py

Author

Saadiqbal
