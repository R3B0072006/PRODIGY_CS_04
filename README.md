# PRODIGY_CS_04
Simple Keylogger
## Description
In this task, we will create a simple Python program that logs keystrokes, recording each key pressed by the user and saving the data to a text file. The program will focus on capturing the keys that are pressed and storing them securely for later use. It is important to note that the use of keyloggers must be done ethically and with proper consent, as this type of software can have significant privacy implications.

## Ethical Considerations
1. Permissions: You must have explicit permission from the user to log keystrokes on their system.
2. Privacy: Ensure that any data logged is used solely for the intended purpose and is securely stored to avoid misuse.
3. Transparency: Always inform the user about what data is being collected and how it will be used.
   
## Features
1. Key Logging: Logs each key pressed by the user, including alphabetic characters, numbers, and special keys.
2. File Saving: Captures the keystrokes and saves them to a text file for later analysis.
3. Key Press Detection: Handles key press events and writes the logged keys to a file in real-time.
4. Stop Logging: Provides a way to stop the logging process (for example, by pressing a designated "stop" key).
   
## How to Run
1. Set Up the Environment: Install the necessary Python libraries (e.g., pynput for detecting keystrokes).
2. Run the Program: Launch the Python script to start logging keystrokes.
3. Stop Logging: The program will log the keys until a predefined "stop" key (e.g., Esc) is pressed.

## Example Output in keystrokes.txt
If you type "Hello World!" during the logging session, the keystrokes will appear in the file like this:

1. 2024-11-12 14:32:01,123 - H
2. 2024-11-12 14:32:01,126 - e
3. 2024-11-12 14:32:01,129 - l
4. 2024-11-12 14:32:01,132 - l
5. 2024-11-12 14:32:01,135 - o
6. 2024-11-12 14:32:01,138 -  
7. 2024-11-12 14:32:01,141 - W
8. 2024-11-12 14:32:01,144 - o
9. 2024-11-12 14:32:01,147 - r
10. 2024-11-12 14:32:01,150 - l
11. 2024-11-12 14:32:01,153 - d
12. 2024-11-12 14:32:01,156 - !

Each key press is logged with the exact key and the timestamp of when it was pressed.
