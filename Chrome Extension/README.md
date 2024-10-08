# Tab Title Fetcher Chrome Extension

### A simple Chrome extension that fetches the title of the active browser tab and displays it in the extension's popup.

## Features
- Fetches the title of the active tab in the current window.
- Displays the tab title in a clean and simple popup interface.

## How It Works
1. Click on the extension icon in the Chrome toolbar.
2. A popup will appear with a "Get Tab Title" button.
3. Upon clicking the button, the title of the currently active tab will be displayed in the popup.

## Getting Started

### Prerequisites
- Google Chrome Browser
- Basic knowledge of HTML, JavaScript, and Chrome extension development

### Installation
1. *Clone the repository*:
   bash
   git clone https://github.com/yourusername/tab-title-fetcher.git
   
   
2. *Navigate to the extension page in Chrome*:
   1. Open Chrome and go to chrome://extensions/.
   2. Enable *Developer Mode* in the top right corner.
   3. Click on *Load unpacked*.
   4. Select the folder where you cloned the repository.
   
3. *Test the extension*:
   1. Click on the extension icon in the toolbar.
   2. Click the *Get Tab Title* button to fetch and display the title of the active tab.

## Folder Structure
- manifest.json: Defines the extension and its permissions.
- popup.html: The HTML file that creates the extension’s popup.
- popup.js: Handles the JavaScript functionality to fetch and display the tab title.

## Code Overview
### Manifest File (manifest.json)
The manifest.json file defines the permissions and structure of the extension. This extension uses the following key features:
- tabs permission to access the current tab's title.
- A popup UI (popup.html) that the user interacts with.

### Popup HTML (popup.html)
The popup consists of a button and a text field that will display the active tab’s title.

### JavaScript (popup.js)
This script uses Chrome's chrome.tabs.query API to access the active tab and display its title inside the popup.

## Permissions
- tabs: Required to access the active tab's title.

You can add more sections depending on your project, such as "Future Improvements" or "Acknowledgements" if applicable.

Make sure to replace placeholders like https://github.com/yourusername/tab-title-fetcher.git and yourusername with your actual repository URL and GitHub username.
