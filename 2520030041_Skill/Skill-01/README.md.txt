# Skill-01: Linux Environment and GCC Setup

## Introduction

This skill focuses on setting up a Linux development environment on Windows and preparing it for C programming. The setup includes installing Ubuntu, creating a Linux user account, updating the system, and installing the GCC compiler.

## Steps Covered

### 1. Open PowerShell as Administrator

PowerShell is opened with administrator privileges to perform the required Linux installation and configuration commands.

### 2. Restart the Computer

After the installation process, the computer is restarted to complete the setup.

### 3. Complete Ubuntu Setup

Ubuntu is opened after restarting the system. A Linux username is created to access the Ubuntu environment.

### 4. Create a Password

A password is created for the Linux user account. The password is entered and confirmed during the setup process.

### 5. Update Ubuntu

The Ubuntu package list is updated using:

```bash
sudo apt update
```

This ensures that the system has the latest available package information.

### 6. Install GCC

The required C development tools are installed using:

```bash
sudo apt install build-essential
```

This provides the GCC compiler and other tools required for C programming.

### 7. Verify the Installation

The GCC installation is checked using:

```bash
gcc --version
```

The installed GCC version is displayed if the installation was successful.

## Conclusion

This skill helped me set up a Linux development environment and understand the basic steps required to compile C programs. I learned how to configure Ubuntu, update the system, install GCC, and verify that the compiler is working correctly.
