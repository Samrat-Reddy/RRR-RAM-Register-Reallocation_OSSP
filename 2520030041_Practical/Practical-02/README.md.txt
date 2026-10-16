# Practical 02 - File Copy Using System Calls

## Aim

To copy the contents of one file into another file using Linux system calls in C.

## Description

This practical demonstrates how files can be opened, read, and written using system calls. The program opens an existing file in read-only mode and creates another file for writing. The contents of the original file are then read into a buffer and written into the new file.

## System Calls Used

* `open()` - Opens or creates a file.
* `read()` - Reads data from a file.
* `write()` - Writes data to a file.
* `close()` - Closes an opened file.

## Concepts Used

* File descriptors
* Reading and writing files
* Input and output system calls
* Buffers
* File permissions
* Error handling

## Working

1. The original file is opened using `O_RDONLY`.
2. A new file is opened using `O_WRONLY | O_CREAT`.
3. Data is read from the original file into a buffer.
4. The data stored in the buffer is written to the new file.
5. Both files are closed after the operation.
6. The program prints `done` when the copying is completed successfully.

## Expected Result

The contents of the original file are copied into the newly created file. The program displays `done` after the operation is completed successfully. The practical document also demonstrates the copied file and its output.

## Conclusion

This practical helped me understand how Linux handles files using system calls. I learned how to use file descriptors and the `open()`, `read()`, `write()`, and `close()` functions to perform basic file operations.
