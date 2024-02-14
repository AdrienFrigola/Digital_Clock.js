Digital Clock Program
Description
This JavaScript code creates a simple digital clock that displays the current time in hours, minutes, seconds, and meridiem (AM or PM). The clock updates automatically every second.

(https://github.com/AdrienFrigola/Digital_Clock.js.git)

Usage
To use the clock program, follow these steps:

Include the JavaScript code in your HTML file or link it externally.
Ensure that you have an HTML element with the id "clock" where the time will be displayed.
Call the updateClock function to initialize the clock and display the current time.
The clock will update automatically every second using setInterval(updateClock).
Functionality
The updateClock function retrieves the current time using the Date object.
It formats the hours, minutes, and seconds to ensure they are displayed with leading zeros if necessary.
It determines the meridiem (AM or PM) based on the hour.
The formatted time string is then displayed in the specified HTML element.
Example
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Clock Program</title>
    <script src="clock.js"></script>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div id="clock"></div>
</body>
</html>
Technologies Used
JavaScript
HTML
CSS
License
This project is licensed under the MIT License
