# Claude for Chrome - API Key Edition

A modified version of the official "Claude for Chrome (Beta)" extension that enables **API Key mode**, allowing you to use the extension with your own Anthropic API key instead of requiring an OAuth login.

## Features

- ✅ **API Key Support**: Use your own Anthropic API key
- ✅ **No Subscription Required**: Bypass subscription checks
- ✅ **Full Functionality**: All original features remain intact
- ✅ **Privacy Focused**: Direct API communication without OAuth intermediaries

## Prerequisites

- Google Chrome browser
- An Anthropic API key (get one from [console.anthropic.com](https://console.anthropic.com/account/keys))

## Installation

Since this is a modified version, it cannot be published to the Chrome Web Store. You'll need to install it manually as an "unpacked extension":

### Step 1: Download the Extension

1. Download or clone this repository to your local machine
2. Unzip the files (if downloaded as a zip)
3. Remember the folder location (e.g., `/Users/yourname/Downloads/Claude-Chrome`)

### Step 2: Enable Developer Mode in Chrome

1. Open Chrome and navigate to `chrome://extensions`
2. In the top-right corner, toggle **"Developer mode"** ON
3. You should now see additional options like "Load unpacked"

### Step 3: Load the Extension

1. Click the **"Load unpacked"** button
2. Navigate to the folder where you extracted the extension
3. Select the folder and click **"Select"** (or "Open")
4. The extension should now appear in your extensions list

### Step 4: Configure Your API Key

1. Click the **extension icon** in your Chrome toolbar (you may need to pin it first)
2. Click the **settings/gear icon** or right-click the extension and select **"Options"**
3. In the left sidebar, select **"API configuration (internal)"**
4. Enter your Anthropic API key in the input field
5. Click **"Save API Key"**

## Usage

### Opening Claude

- **Keyboard Shortcut**: Press `Cmd+E` (Mac) or `Ctrl+E` (Windows/Linux)
- **Extension Icon**: Click the Claude icon in your browser toolbar

### Using the Chat Interface

1. Open the side panel using the shortcut or icon
2. Type your message in the input box
3. Claude will respond using your API key

### Managing Permissions

- Navigate to **Options > Permissions** to manage site permissions
- Grant Claude access to specific websites as needed

## Important Notes

⚠️ **This is NOT an official release**: This extension has been modified from the official version and is not endorsed by Anthropic.

⚠️ **API Costs**: Usage will be charged to your Anthropic API account. Monitor your usage at [console.anthropic.com](https://console.anthropic.com/).

⚠️ **Updates**: This version will not auto-update. You'll need to manually download and install new versions.

⚠️ **Security**: Only install extensions from sources you trust. Review the code if you have concerns.

## Troubleshooting

### Extension doesn't load
- Make sure Developer mode is enabled
- Try reloading the extension from `chrome://extensions`

### API Key not working
- Verify your API key is correct at [console.anthropic.com](https://console.anthropic.com/account/keys)
- Check that you've saved the key in the extension options
- Try reloading the extension after saving the key

### Chat interface shows login screen
- Reload the extension from `chrome://extensions`
- Reopen the side panel

## License

This project is a modification of the official Claude for Chrome extension. Original copyright belongs to Anthropic.

## Disclaimer

This is an unofficial modification for educational and personal use. Use at your own risk. The authors are not responsible for any issues arising from the use of this modified extension.
