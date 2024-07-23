# FocusPause

**FocusPause** is a Chrome extension that enhances your video watching experience by automatically pausing videos when you switch away from the browser and resuming them when you return. This is especially useful for people who multitask with multiple applications, such as developers who switch between coding tutorials and their IDE.

## Features

- **Automatic Pausing**: Videos are automatically paused when the browser tab loses focus.
- **Automatic Resuming**: Videos are automatically resumed when the browser tab gains focus.
- **Works on All Websites**: The extension works on any website with video elements.
- **Simple Setup**: Easy to install and use with no configuration needed.

## Installation

1. Clone or download this repository.
2. Open Chrome and go to `chrome://extensions/`.
3. Enable "Developer mode" using the toggle switch in the top right.
4. Click "Load unpacked" and select the folder containing the extension files.

## Usage

- Open a video on any website with a `video` element.
- Switch to another application on your desktop.
- The video will pause automatically.
- Switch back to the browser tab.
- The video will resume playing automatically.

## Files

- `manifest.json`: Defines the extension's properties and permissions.
- `background.js`: Handles the background tasks for the extension.
- `content.js`: Contains the logic for pausing and resuming videos based on tab visibility.

