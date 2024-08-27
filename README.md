# Simple Python Calendar

A simple Python program to manage and organize calendar events for personal use. This application allows users to add, view, and delete events, and saves the meetings to a file (`events.json`) for persistence across multiple sessions.

## Features

- **Add Events**: Schedule new meetings with a date, time, title, and description.
- **View Events**: Display all scheduled meetings in a user-friendly format.
- **Delete Events**: Remove meetings that are no longer needed.
- **Data Persistence**: All meetings are saved to a `events.json` file, ensuring they are available even after the program is closed and reopened.

## Requirements

- Python 3.x

## How to Run

1. **Clone the repository** (or download the `main.py` script):

    ```bash
    git clone https://github.com/i-suck-at-most-stuff/simple-python-calendar.git
    cd simple-python-calendar
    ```

2. **Run the program**:

    ```bash
    python main.py
    ```

3. **Follow the on-screen instructions** to add, view, or delete events.

## Usage

When you run the program, you will be presented with a menu:


- **Add an Event**: Enter the date (YYYY-MM-DD), time (HH:MM), title, and description.
- **View Events**: Lists all scheduled events.
- **Delete an Events**: Enter the number corresponding to the meeting you wish to delete.
- **Exit**: Closes the application.

## Data Storage

All events are stored in a `events.json` file in the same directory as the script. The file is automatically updated whenever you add or delete a meeting.

If the `events.json` file is not found when the program starts, a new one will be created.
