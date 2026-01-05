# Crypto Portfolio Manager (Chrome Extension)
Project Overview

Crypto Portfolio Manager is a functional Chrome Extension designed to help users track and manage their virtual currency holdings in real-time.
The extension provides a dashboard to view holdings, calculate total portfolio value in USD, and visualize asset distribution.

Key Features
* Real-Time Data: Fetches live cryptocurrency exchange rates from the CEX.IO API.
* Data Persistence: Uses a DAO (Data Access Object) pattern to manage user holdings locally via localStorage, ensuring data is saved between sessions.
* Visual Analytics: Integrates Chart.js to provide dynamic pie charts of the user's portfolio distribution.
* Responsive UI: Built with Bootstrap 5 for a clean, modern interface that works as a standalone popup window.
* Activity Tracking: Automatically tracks and displays the last modified timestamp for each currency update.

Technologies Used
* Core: JavaScript (ES6+), HTML5, CSS3.
* Web APIs: Chrome Extensions API (Manifest V3), Fetch API.
* Librari: Chart.js, Bootstrap 5, Font Awesome.

Installation Instructions
1. Download the repository as a ZIP file and extract it.
2. Open Chrome and navigate to chrome://extensions.
3. Enable Developer Mode (top-right corner).
4. Click Load unpacked and select the folder containing the extension files.
5. Pin the extension to your toolbar for easy access.


Developed by Yarden Maman & Tal Alper
