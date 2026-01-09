# 📂 Automatic File Organizer

A simple and efficient Python script that automatically organizes files in a specific directory by moving them into categorized folders based on their file extensions.

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Status](https://img.shields.io/badge/Status-Working-brightgreen)

## 📝 Description

This script scans a target directory (e.g., your Downloads or specific project folder) and sorts the files into the following sub-folders automatically:

- **jpg files** (for `.jpg` images)
- **image files** (for `.png` images)
- **pdf files** (for `.pdf` documents)
- **docx files** (for Word documents)

If the folders do not exist, the script creates them automatically. If a file does not match these extensions, it is left untouched.

## 🚀 Features

- **Automatic Folder Creation**: Checks if destination folders exist; if not, creates them.
- **Duplicate Protection**: Checks if a file already exists in the destination to prevent overwriting errors.
- **Extension Sorting**: Handles `.jpg`, `.png`, `.pdf`, and `.docx`.
- **Feedback**: Prints the path of created folders and notifies if files were not moved.

## 🛠️ Prerequisites

You need to have **Python** installed on your system. This script uses standard libraries, so no external installation (`pip install`) is required.

- **Libraries used:** `os`, `shutil`

## ⚙️ How to Use

1. **Clone or Download** this repository.
2. **Open the script** in a code editor.
3. **⚠️ IMPORTANT:** Update the `path` variable.
   Line 2 of the code contains a specific path:
