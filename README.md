# Content Countdown Timer

This project is a simple, elegant countdown timer that locks a link until a specified time. Once the timer reaches zero, the link is revealed. It's built with HTML, and Tailwind CSS for styling, and includes a clear configuration section in the JavaScript.

## Live Demo

You can see a live demo of the project here: [https://websites0.github.io/Mahir-Exam-Time/](https://websites0.github.io/Mahir-Exam-Time/)

## Configuration

All configuration is done directly in the `index.html` file within the `<script>` tag.

1.  **Google Drive Link**:
    To change the link that unlocks, modify the `GOOGLE_DRIVE_LINK` constant:
    ```javascript
    const GOOGLE_DRIVE_LINK = 'YOUR_NEW_GOOGLE_DRIVE_LINK_HERE';
    ```

2.  **Unlock Time**:
    To set the unlock date and time, modify the `UNLOCK_TIME_STRING` constant. The format is `YYYY-MM-DDTHH:MM:SS` (ISO 8601), based on the user's local timezone.
    ```javascript
    // Example: November 8, 2025, at 6:15:00 PM
    const UNLOCK_TIME_STRING = '2025-11-08T18:15:00';
    ```

## Features

*   **Real-time Countdown**: Displays the remaining days, hours, minutes, and seconds.
*   **Dynamic Content Unlock**: Automatically hides the locked state and shows the unlocked link when the timer finishes.
*   **Easy Configuration**: All settings are in one place and clearly commented.
*   **Clean & Modern UI**: Styled with Tailwind CSS for a professional look.
*   **Responsive Design**: Works on all screen sizes.

## Files

*   `index.html`: The main file containing the HTML structure, styling, and JavaScript logic.
*   `README.md`: This file, providing information about the project.
