# Alarm Clock Application

This is a simple alarm clock application built using Python and the Tkinter library for the GUI, with additional libraries like PIL for image handling and pygame for sound. This application allows users to set an alarm for a specific time (hour, minute, and second) and plays a sound when the alarm time is reached.

## Features

- **Set Alarm**: Users can set an alarm by specifying the hour, minute, and second.
- **Activate/Deactivate Alarm**: Users can activate the alarm to start the countdown and deactivate it to stop the alarm sound.
- **Sound Notification**: Plays a sound when the alarm time is reached.

## Requirements

- Python 3.x
- Libraries:
  - `tkinter`
  - `PIL` (Pillow)
  - `pygame`

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/alarm-clock-app.git
   cd alarm-clock-app
   ```

2. **Install the required libraries**:
   ```bash
   pip install pillow pygame
   ```

3. **Install `tkinter` on Windows**:
   ```bash
   pip install tk
   ```

4. **Ensure you have the `alarm main.mp3` file in the same directory as your script**.

## Usage

Run the `alarm_clock.py` script:

```bash
python alarm_clock.py
```

## Description

This application provides a graphical user interface (GUI) where users can set an alarm by selecting the hour, minute, and second from dropdown menus. The application runs a background thread to constantly check the current time against the set alarm time. When the alarm time is reached, a sound is played using the `pygame` mixer.

### Alarm Functions

- **Activate Alarm**: Starts a background thread to monitor the time and trigger the alarm sound.
- **Deactivate Alarm**: Stops the alarm sound when activated.

### GUI Elements

- **Comboboxes**: Allow users to select the hour, minute, and second for the alarm.
- **Radiobuttons**: Provide options to activate and deactivate the alarm.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
