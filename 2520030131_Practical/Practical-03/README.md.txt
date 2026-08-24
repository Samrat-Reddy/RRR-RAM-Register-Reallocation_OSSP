# Practical 03 - Parent and Child Process States

## Aim

To understand parent-child process relationships and process states using `fork()`, `getpid()`, `getppid()`, `sleep()`, and `wait()`.

## Description

This practical creates a child process using the `fork()` system call. Both the parent and child processes display their process information, including their PID and PPID. The program also displays the running and completed states of the processes.

## System Calls and Functions Used

* `fork()` - Creates a new child process.
* `getpid()` - Returns the PID of the current process.
* `getppid()` - Returns the PID of the parent process.
* `sleep()` - Temporarily pauses the process.
* `wait()` - Makes the parent wait for the child process.

## Working

1. The program calls `fork()` to create a child process.
2. The child displays its PID and the PID of its parent.
3. The child displays its running state and waits for 2 seconds using `sleep()`.
4. The child then displays that its execution is completed.
5. The parent displays its own PID and PPID.
6. The parent waits for the child using `wait()`.
7. After the child finishes, the parent displays its completed state.

The program follows the parent-child process structure shown in the Practical-03 source code.

## Expected Result

The output shows the parent and child processes with their respective PIDs and PPIDs. Both processes initially show a running state, followed by a completed state. The parent completes after the child process has finished.

## Conclusion

This practical helped me understand how Linux creates and manages parent and child processes. I also learned how PIDs, PPIDs, process states, `sleep()`, and `wait()` are used to control and observe process execution.
