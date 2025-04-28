# Zed Champions Tracker

A simple, self-contained HTML tool for manually tracking your Zed Run racing and breeding stable.

## Features

*   Track racing horses (name, bloodline, gender, stars).
*   Record race results (position, odds, time, ZED +/-, MM change, augments used).
*   Track breeding horses.
*   Record breeding events (parents, foal details, stud fee).
*   Manage a list of known augments.
*   View overall statistics (total races, ZED change, retirement earnings, stud fees).
*   Filter and sort horse tables.
*   Export and import all tracker data as a JSON backup.

## How to Use

1.  Download the `zed_tracker.html` file.
2.  Open the file directly in your web browser (e.g., Chrome, Firefox, Edge).
3.  Start adding your horses, races, and breeding data using the forms provided.

## IMPORTANT: Data Storage

*   All data you enter (horses, races, breeding records, augments) is stored **locally in your web browser's `localStorage`**.
*   The data is **NOT** stored within the `zed_tracker.html` file itself.
*   **Sharing the `zed_tracker.html` file will NOT share your tracked data.** Each user opening the file will have their own separate data stored in their own browser.
*   Use the **Export Data** feature (in the Settings tab) regularly to create backups of your data as a JSON file. You can restore from this backup using the **Import Data** feature.

## Known Limitations / Future Ideas

*   Purely manual data entry.
*   No integration with external APIs (e.g., ZED API).
*   Data is local to the specific browser and computer used. Clearing browser data can erase tracker data (use Export!).
*   Could add more detailed analysis or charting features.

## Contributing

Feel free to fork this repository and suggest improvements via Pull Requests. 