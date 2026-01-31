
# eza-cmd

[Korean README](README.ko.md)

A collection of Windows batch command scripts designed to make using the eza program more convenient on Windows. These scripts help users easily utilize eza and related features from the command line. Provided by JayTwoLab.

## Overview
This repository contains several command-line utility scripts for Windows, each with a specific purpose. These scripts are designed to enhance productivity and provide useful command-line tools for everyday tasks.

## eza Installation

To use these scripts, you need to have the [eza](https://github.com/eza-community/eza) program installed.

### Download eza
- Official GitHub releases: [https://github.com/eza-community/eza/releases](https://github.com/eza-community/eza/releases)

### Install via Package Manager
- **Scoop**:
   ```
   scoop install eza
   ```
- **winget**:
   ```
   winget install --id eza-community.eza
   ```
- **Chocolatey**:
   ```
   choco install eza
   ```

After installing eza, ensure it is available in your system PATH.

## Included Scripts
- **ela.cmd**
- **elh.cmd**
- **ell.cmd**
- **els.cmd**
- **elt.cmd**

Each script serves a different function. Please refer to the comments within each script for detailed usage instructions.

## Usage
1. Clone or download this repository.
2. Place the desired `.cmd` files in a directory included in your system's `PATH` environment variable, or run them directly from the repository folder.
3. Open a Command Prompt or PowerShell window and execute the scripts by typing their names, e.g.:
   ```
   ela
   elh
   ell
   els
   elt
   ```

## License
This project is licensed under the terms of the LICENSE file provided in this repository.

## Author
JayTwoLab
