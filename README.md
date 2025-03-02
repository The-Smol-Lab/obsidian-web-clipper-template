# Importing Templates into Obsidian Web Clipper (Chrome Extension)

This guide explains how to import JSON files containing templates into the Obsidian Web Clipper Chrome extension.

## Prerequisites

- [Obsidian](https://obsidian.md/) installed on your device
- [Obsidian Web Clipper](https://chrome.google.com/webstore/detail/obsidian-web-clipper/plplajofbhcfhdpkhoibkocphcmjlkmi) extension installed in Chrome or a Chromium-based browser
- A JSON file containing the web clipper template you want to import

## Steps to Import a Template

1. **Open Chrome** and ensure the following extensions are installed:
   - Click the Extensions icon (🧩) in your toolbar, then select "Manage Extensions."
   - Install the [Obsidian Web Clipper](https://chrome.google.com/webstore/detail/obsidian-web-clipper/plplajofbhcfhdpkhoibkocphcmjlkmi) extension if not already installed.
   - Install the [YouTube Text Tools](https://chromewebstore.google.com/detail/youtube-text-tools/pcmahconeajhpgleboodnodllkoimcoi) extension and enable it for enhanced text extraction from YouTube pages.
   - Ensure both extensions are enabled.

2. **Access the Obsidian Web Clipper**:
   - Click the Obsidian Web Clipper extension icon in your toolbar.

3. **Open Template Settings**:
   - In the extension popup, click the gear icon (⚙️) or the settings option.
   - Navigate to the "Templates" section in the settings panel.

4. **Import the Template**:
   - Click the "Import" button in the templates interface.
   - A file browser will appear—navigate to and select your JSON template file.
   - Click "Open" to import the template.

5. **Verify the Import**:
   - The imported template should appear in your templates list.
   - Select it to review or edit its properties if needed.

## Template Configuration (Post-Import)

After importing, configure your template in the extension settings:

1. **Edit the Template Name**: Click the name field to rename it.
2. **Set the Behavior**: Choose an option like "Create new note."
3. **Configure the Note Name Format**: Use variables such as `{{title}}`, `{{date}}`, or `{{published}}`.
4. **Define the Note Location**: Specify the folder or path where clipped content will be saved.
5. **Select a Vault**: Choose a vault from the dropdown if using multiple vaults.
6. **Set Up Template Triggers**: Define URL patterns (e.g., `https://example.com/*`) to auto-select this template.

## Troubleshooting

- **Import Button Not Working**: Verify your JSON file matches the expected Obsidian Web Clipper template format.
- **Template Not Appearing**: Refresh the extension or restart your browser.
- **Formatting Issues**: Check your JSON file for syntax errors.
- **Extension Not Connecting to Obsidian**: Ensure Obsidian is running and the Obsidian URI is configured correctly.

## Using Your Imported Template

1. Visit a webpage you want to clip.
2. Click the Obsidian Web Clipper extension icon.
3. Select your imported template from the dropdown menu.
4. Click the "Clip" button to save the content per your template settings.

## Backing Up Templates

To safeguard your templates:
- Use the "Export" button in the extension’s template settings to save templates as JSON files.
- Store these files in a secure location for backup or sharing.

## Template JSON Structure

If creating or editing templates manually, follow this structure:

```json
{
  "name": "Template Name",
  "behavior": "Create new note",
  "noteName": "{{title}}",
  "noteLocation": "Folder/Path",
  "vault": "Default",
  "triggers": [
    "https://example.com/*"
  ]
}
```

## Additional Resources

- [Obsidian Web Clipper on Chrome Web Store](https://chrome.google.com/webstore/detail/obsidian-web-clipper/plplajofbhcfhdpkhoibkocphcmjlkmi)
- [Web Clipper Interpreter](https://help.obsidian.md/web-clipper/interpreter)
- [YouTube Text Tools Extension](https://chromewebstore.google.com/detail/youtube-text-tools/pcmahconeajhpgleboodnodllkoimcoi)
