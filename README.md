### Description
**Keka Log Duration by Jp** is a Tampermonkey script designed to enhance the user experience for tracking and calculating attendance log durations on the Keka platform. The script automatically calculates the time duration between log-in and log-out times, displays total duration for the day, and adds a visually appealing morphing text effect for better clarity and engagement.

---

### README.md

# Keka Log Duration by Jp

**Keka Log Duration by Jp** is a Tampermonkey user script that improves the usability of the Keka platform by automating log duration calculations and displaying total log-in time. This script is perfect for users who want to quickly track their attendance log durations without manual calculations.

## Features

- **Automatic Duration Calculation**:
  - Calculates and displays the duration between log-in and log-out times.
  - Displays the total duration for multiple log entries.
  
- **Dynamic Updates**:
  - Handles changes in log data in real-time as you interact with the platform.
  - Updates durations dynamically when modal elements are opened.

- **Visual Enhancements**:
  - Adds styled text for displaying durations.
  - Includes a morphing text effect for a more engaging experience.

- **Failsafe Mechanism**:
  - Handles edge cases like missing log-out times by considering the current time as the end time.

## Requirements

- **Tampermonkey Extension**:
  Install the Tampermonkey extension for your browser:
  - [Tampermonkey for Chrome](https://www.tampermonkey.net/)
  - [Tampermonkey for Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)

- **Keka Platform Access**:
  This script works on the Keka platform (`https://*********.keka.com/`).

## Installation

1. Install the Tampermonkey extension for your browser.

2. Add the script:
   - Open Tampermonkey in your browser.
   - Click on "Create a new script."
   - Paste the code into the editor and save.

3. Alternatively, use the direct download link:
   - Install from [GreasyFork](https://update.greasyfork.org/scripts/488533/Keka%20Log%20Duration%20by%20Jp.user.js).

4. Reload the Keka platform page to activate the script.

## Usage

1. Navigate to the Keka platform: `https://*********.keka.com/`.

2. Open the attendance log modal by clicking on the relevant row.

3. The script will:
   - Calculate and display durations next to each log entry.
   - Show the total duration for the day at the bottom of the modal.

4. Enjoy the added **morphing text effect** at the top for a visually enhanced experience!

## How It Works

### Key Functionalities:

1. **Calculate Duration**:
   - Automatically computes the difference between start and end times.
   - Displays durations for each log entry.

2. **Calculate Total Duration**:
   - Aggregates durations of all log entries for the day.
   - Displays the total duration at the bottom of the log modal.

3. **Real-Time Updates**:
   - Listens to user interactions and updates the durations dynamically.

4. **Visual Effects**:
   - Adds a morphing text effect to display engaging messages at the top of the page.

## Example

### Before:
- Manually calculate durations between log-in and log-out times.
- No visibility of total duration for the day.

### After:
- **Log Durations**: `2 Hr 15 Min` displayed dynamically next to each log.
- **Total Duration**: `7 Hr 45 Min` displayed clearly at the bottom.
- **Enhanced UI**: Morphing text adds an engaging element to the page.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! If you have ideas for improvements, feel free to fork the repository and submit a pull request.

---

This script transforms the mundane task of tracking attendance into an efficient and enjoyable experience. Install it today and make the most of your time! 🚀
