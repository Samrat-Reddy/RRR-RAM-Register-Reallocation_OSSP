# Practical 06 - Named Pipes and POSIX Signal Handling

## Aim

To understand inter-process communication using Named Pipes (FIFOs) and asynchronous event handling using POSIX signals.

## Description

This practical demonstrates communication between a client and server using a Named Pipe (FIFO). The client sends a message through the FIFO, and the server reads and displays the message.

The practical also demonstrates POSIX signal handling using `SIGINT`, `SIGTERM`, and `SIGUSR1`. Signal handlers are used to respond to asynchronous events while the program is running.

## Programs Used

* `client.c` - Sends messages through the FIFO.
* `server.c` - Reads and displays messages from the FIFO.
* `posix.c` - Handles POSIX signals.

## Concepts Used

* Inter-process communication using FIFO
* Named Pipes
* Client-server communication
* Multiple clients using a FIFO
* POSIX signals
* Signal handlers
* Asynchronous event handling
* `SIGINT`, `SIGTERM`, and `SIGUSR1`

## Expected Result

The client sends a message through the Named Pipe and the server receives and displays it.

The signal handling program responds to `SIGINT`, `SIGTERM`, and `SIGUSR1` using the registered signal handler while continuing its execution.

## Conclusion

This practical helped me understand inter-process communication using Named Pipes and how a client and server can exchange messages. It also provided an understanding of POSIX signals, signal handlers, and asynchronous event handling in Linux.