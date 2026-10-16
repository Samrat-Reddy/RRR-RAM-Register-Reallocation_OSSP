# Skill-02: Interactive Command-Line Shell

## Introduction

This skill focuses on understanding the basic working of an interactive command-line shell. A shell allows the user to enter commands, processes the input, and continues accepting commands until the user chooses to exit.

## Concepts Covered

### 1. Main Loop

The shell uses a main loop to continuously interact with the user. It displays a prompt, waits for input, processes the command, and then displays the prompt again.

### 2. Command Prompt

The shell displays a prompt to indicate that it is ready to accept a command from the user.

### 3. Keyboard Input

The shell receives input from the keyboard. Characters are collected one by one and stored in an input buffer.

### 4. Input Buffer

The input buffer temporarily stores the characters entered by the user. When the Enter key is pressed, the stored characters are treated as a complete command.

### 5. Backspace Handling

Backspace allows the user to correct typing mistakes. When Backspace is pressed, the last character is removed from the input buffer and the display is updated.

### 6. Enter Key Handling

The Enter key indicates that the user has finished entering a command. The shell then processes the command stored in the input buffer.

### 7. Multi-Character Commands

Commands such as `hello` and `ls` are entered character by character and stored in the correct order before being processed.

### 8. Exit Condition

The shell continues running until the user enters the required exit condition. This allows the user to terminate the shell when required.

## Conclusion

This skill helped me understand the basic structure of an interactive shell and how it communicates with the user. I learned about the main loop, command prompt, keyboard input, input buffering, Backspace handling, Enter-key handling, and command processing. These concepts provide a foundation for developing more advanced shell features.
