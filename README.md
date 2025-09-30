# Python Keylogger
This Python script uses the pynput library's Listener to capture keyboard press events and log them into a file named log.txt. It performs several transformations to make the log more readable: it removes quotes from single characters, converts Key.space into a real space, ignores right-shift presses, converts Key.enter into a newline, and records a readable message when the Backspace key is pressed.

## Features / Capabilities

List what your code does in a professional way:

Captures all keyboard presses in real-time.

Converts Key.space into a proper space character for readability.

Converts Key.enter into a newline to separate typed lines.

Ignores right-shift presses to simplify the log.

Records a readable token for Backspace ( Backspace pressed).

Appends all logged data into log.txt.

## Sample Output

If the user types:
Hello

The log.txt file will contain:
Hello

If Backspace is pressed, it will record:
Backspace pressed

Ethical Disclaimer

This project is for educational purposes only. Never use this script on other people’s devices without permission. Misuse is illegal and unethical.
