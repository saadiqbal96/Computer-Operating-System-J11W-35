# Directory Management Script – Part 3 of OS Assessment

## Overview

This Python script provides a simple, safe, and user-friendly way for non-technical users to manage directories. 
Users can create, rename, or delete directories in a restricted set of predefined paths.

The script is part of the Operating Systems assessment (Part 3).

---

## Features

- Menu-driven interface:
  - Create a New Directory
  - Rename a Directory
  - Delete a Directory
  - Exit
- Restricted to a **safe set of directories** to prevent system-level changes
- Fully documented and tested
- Works both in **local Python environments** and **Google Colab / Jupyter Notebook**

---

## Allowed Directories

By default, the script uses Colab-friendly paths:



/content/Projects
/content/Backups
/content/Shared


> These paths can be adjusted for local systems.

---

## Files in this Repository

- `dir_manager.py` – the Python script  
- `dir_manager_demo.html` – HTML export from Colab/Jupyter showing code and menu execution

---

## How to Run

### Local Python Environment:

1. Make sure Python 3 is installed
2. Run the script:

```bash
python3 dir_manager.py


Follow the menu prompts to create, rename, or delete directories.

Google Colab / Jupyter Notebook:

Open the notebook or HTML file

Run all cells

Follow on-screen menu prompts to demonstrate functionality

Example Usage

Create a directory → Projects/TestFolder

Rename a directory → TestFolder → RenamedFolder

Delete a directory → RenamedFolder

Exit script

Author: Saad Iqbal
