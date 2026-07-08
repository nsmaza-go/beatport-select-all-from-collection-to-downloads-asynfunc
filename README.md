# beatport-select-all-from-collections-to-downloads-asynfunc
The Problem
As a Beatport customer, I had purchased and downloaded a large music library. After accidentally deleting the files from my computer, I returned to Beatport's downloads page to re-download them — only to find there was no way to select all tracks across multiple pages at once.

With 150+ purchased tracks spread across several pages, I had to manually select each one individually. If you made a mistake on any page, you had to start over from the beginning.

The Solution
I built a self-invoking asynchronous JavaScript function that automates this process. When pasted into the browser console, it:

Automatically selects all tracks on the current page
Detects and clicks the "Next" button to advance to the next page
Waits for the new page to load before continuing
Stops automatically when it reaches the final page

How to Use It
Navigate to your Beatport downloads page
Open your browser's developer console (F12 → Console)
Paste the script and press Enter
Wait for it to complete — progress is logged in the console

Why This Matters
This is a gap in Beatport's current UX. A native "Select All Across Pages" in the downloads page feature would significantly improve the experience for customers managing large libraries.
