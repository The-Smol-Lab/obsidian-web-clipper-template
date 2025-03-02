# Importing Templates into Obsidian Web Clipper (Chrome Extension)

This guide explains how to import JSON files containing templates into the Obsidian Web Clipper Chrome extension.

## Prerequisites

- [Obsidian](https://obsidian.md/) installed on your device
- [Obsidian Web Clipper](https://chrome.google.com/webstore/detail/obsidian-web-clipper/plplajofbhcfhdpkhoibkocphcmjlkmi) extension installed in Chrome/Chromium-based browser
- A JSON file containing the web clipper template you want to import

## Steps to Import a Template

1. **Open Chrome** and click on the Obsidian Web Clipper extension icon in your toolbar.

2. **Access Template Settings**:
   - Click the gear icon (⚙️) or settings option in the extension popup
   - Navigate to the templates section of the settings panel

3. **Import the Template**:
   - Click the "Import" button in the settings interface
   - A file browser will open - navigate to and select your JSON template file
   - Click "Open" to import the template

4. **Verify the Import**:
   - The imported template should now appear in your templates list
   - You can select it to view or edit its properties

## Template Configuration (Post-Import)

After importing your template, you can configure it directly in the extension settings:

1. **Edit the template name** by clicking on the name field
2. **Set the behavior** (for example, "Create new note")
3. **Configure the note name format** using variables like `{{title}}`, `{{date}}`, and `{{published}}`
4. **Define the note location** (folder or path where clipped content will be saved)
5. **Select a vault** from the dropdown if you're using multiple vaults
6. **Set up template triggers** to automatically select this template when specific URL patterns are detected

## Troubleshooting

- **Import button not working**: Make sure your JSON file has the correct format for Obsidian Web Clipper templates
- **Template not appearing after import**: Try refreshing the extension or restarting your browser
- **Formatting issues**: Check the JSON structure of your template file for errors
- **Extension not connecting to Obsidian**: Ensure Obsidian is running and the Obsidian URI is properly configured

## Using Your Imported Template

1. Browse to any webpage you want to clip
2. Click the Obsidian Web Clipper extension icon
3. Select your imported template from the dropdown menu
4. Click the clip button to save the content according to your template settings

## Backing Up Templates

It's a good practice to keep backups of your templates:
- You can export existing templates using the "Export" button in the extension's template settings
- Save these JSON files in a secure location for future use or sharing with others

## Template JSON Structure

If you're creating or modifying templates manually, ensure they follow this general structure:
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

- [Obsidian Web Clipper on Chrome Web Store](https://obsidian.md/clipper)
- [Obsidian Forum: Web Clipper Discussions](https://forum.obsidian.md/tag/web-clipper)
- [Obsidian Help: URI Schemes](https://help.obsidian.md/Advanced+topics/Using+obsidian+URI)
