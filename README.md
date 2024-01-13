# Create C Project

**A simple program for starting a new C project.**

## Overview

The provided C code serves as a project initiation script named "Crun." Its primary functionality is to automate the setup process for a new C project by cloning a template from the Create_C_Project GitHub repository. The project structure includes essential directories such as src, bin (with subdirectories for different build configurations), and res (for resources). The main function prints project information, determines the installation path, clones the template project, opens the installation directory, and displays a completion message. The script is tailored for Windows environments, utilizing Windows API functions.

## Project Structure

```plaintext
Crun Project
|-- bin
|   |-- debug
|   |-- release
|   |   |-- Crun.exe
|   |-- test
|-- doc
|   |-- notes.txt
|-- res
|-- |-- img
|   |   |-- Crun.ico
|-- src
|   |-- main.c
|   |-- Makefile
|-- Create_C_Project.code-workspace
|-- LICENSE
|-- README.md
```
## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ZouariOmar/Crun.git