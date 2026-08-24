# Practical 01 - Process Creation and Linux System Information

## Aim

To understand process creation in Linux using `fork()`, process execution using `execl()`, and basic Linux system information commands.

## Description

This practical demonstrates how a parent process creates a child process using the `fork()` system call. The child process executes a command using the `execl()` function, while the parent process waits for the child to complete using `wait()`.

The practical also includes basic Linux commands used to understand the system and running processes.

## System Commands Used

* `lscpu` - Displays CPU and processor information.
* `lsblk` - Displays information about available storage devices.
* `ps` - Displays currently running processes.
* `top` - Displays real-time information about system resources and processes.

## Concepts Used

* Process creation using `fork()`
* Parent and child processes
* Process IDs (PID)
* Program execution using `execl()`
* Process synchronization using `wait()`
* Linux system information commands

## Expected Result

The program creates a child process. The child process executes the given command, while the parent process waits for the child to finish. The system commands provide information about the CPU, storage, and currently running processes.

## Conclusion

This practical helped me understand the basic relationship between parent and child processes and how Linux allows one process to create and execute another program. It also provided basic knowledge of Linux commands used to inspect system and process information.
