# Keyboard Shortcuts Script for my.clerk.io UI

This user-friendly script facilitates interaction with the my.clerk.io user interface by enabling keyboard shortcuts. It is designed to enhance your efficiency and make navigation smoother. The following keyboard shortcuts are currently available:

- Enter Key: Confirm and Proceed
- Escape Key: Cancel and Return

## How to Customize keybinds (Chrome only)
You can customize the keyboard shortcuts according to your preference by following these steps:

Open the Clerk.io extension options by clicking on the extension icon in your browser toolbar.

In the options page, you will find the settings for the keyboard shortcuts.

Enable or disable the desired shortcuts by toggling the corresponding checkboxes.

To change the default keyboard shortcuts, click on the input field for the shortcut you want to modify and press the desired key. The input field will be automatically updated with the selected key.

Click the "Save Settings" button to save your changes.

Remember, these shortcuts are meant to enhance your navigation and user experience within the my.clerk.io interface. I hope you find them useful and time-saving.

## Installation

If using chrome:
1. Open Chrome: Start Google Chrome. In the top-right corner of the browser, click on the three vertical dots to open the main menu.

2. Navigate to Extensions: In the dropdown menu, select More Tools > Extensions. This will open a new tab that shows all your installed extensions.

3. Enable Developer Mode: On the Extensions page, look for a toggle switch at the top-right corner labeled Developer Mode. If it's not already enabled, click on the toggle to enable it.

4. Load Unpacked Extension: Click on the Load unpacked button which will appear after you have enabled Developer Mode. This will open a file dialogue box.

5. Select the Extension Folder: In the file dialogue box, navigate to the location where you installed this repo. Select the folder "chrome" and click Open or Select Folder (the exact wording may vary depending on your operating system).

6. Verify the Extension: Your extension should now be listed among your other installed extensions. You should see its name, version, and a few options to manage it. Check if the extension icon appears in your Chrome extensions.


If using firefox:
Load the extension into your Firefox browser by navigating to `about:debugging`, clicking "This Firefox", then "Load Temporary Add-on...", and select the .zip file in the `firefox/web-ext-artifacts` directory.

If updating chrome manifest, use `node convertManifest.js` to update firefox manifest

## Contributing

Please submit a pull request if you'd like to contribute.

## Todo:
- Make backspace shortcut to go back a page
- Make button that deletes all automatically generated 'best practice' content/designs
- Remove cmd-z functionality on designs

## License

See the LICENSE file for license rights and limitations.