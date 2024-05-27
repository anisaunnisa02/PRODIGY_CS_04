# Simple Keylogger

This is a basic keylogger program written in Python that records and logs keystrokes. 
The logged keys are saved to a file named `keylog.txt`.

## Ethical and Legal Considerations

**Important**: Ensure that you have explicit permission from any users on whose devices you intend to run this software. 
Unauthorized use of a keylogger is illegal and unethical.

## Requirements

- Python 3.x
- `pynput` library
## Running the Keylogger
Open the Project in VS Code:

Open Visual Studio Code.
Open the directory containing keylogger.py.

## Run the Script:

Open a terminal in VS Code by going to View > Terminal or pressing 'Ctrl+'.
Run the script by executing :
python keylogger.py

## Stop the Keylogger:

Press the Esc key to stop the keylogger. 
This will terminate the listener and stop logging keystrokes.

## Script Details
Logging Keystrokes:
The script logs every key press to keylog.txt. It distinguishes between regular keys, special keys (e.g., space, enter), and handles errors gracefully.

## Stopping the Keylogger:
The keylogger can be stopped by pressing the Esc key, which triggers the on_release function to return False, stopping the listener.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
