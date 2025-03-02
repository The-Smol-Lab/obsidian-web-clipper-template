# Importing Web Clipper Templates in Obsidian

This guide explains how to import JSON files containing web clipper templates into Obsidian.

## Prerequisites

- [Obsidian](https://obsidian.md/) installed on your device
- A JSON file containing the web clipper template you want to import

## Steps to Import a Template

1. **Open Obsidian** and navigate to the vault where you want to use the template.

2. **Access Template Settings**:
   - Click the gear icon (⚙️) in the lower left corner to open Settings
   - Select "Templates" from the sidebar menu

3. **Import the Template**:
   - Click the "Import" button in the top right corner of the template settings screen
   - A file browser will open - navigate to and select your JSON template file
   - Click "Open" to import the template

4. **Verify the Import**:
   - The imported template should now appear in your templates list
   - You can select it to view or edit its properties

## Template Configuration (Post-Import)

After importing your template, you may want to:

1. **Rename the template** if needed by clicking on its name field
2. **Adjust the behavior** settings (for example, "Create new note")
3. **Modify the note name format** using available variables like `{{title}}`, `{{date}}`, and `{{published}}`
4. **Set the note location** (folder or path where clipped content will be saved)
5. **Select a vault** if you're using multiple vaults
6. **Configure template triggers** to automatically select this template based on URL patterns

## Troubleshooting

- **Import button not working**: Make sure your JSON file has the correct format for Obsidian templates
- **Template not appearing after import**: Try restarting Obsidian
- **Formatting issues**: Check the JSON structure of your template file for errors

## Using Your Imported Template

1. When using the Obsidian Web Clipper browser extension, your imported template will appear as an option
2. Select it from the template dropdown when clipping web content
3. The clipped content will be formatted and saved according to your template settings

## Backing Up Templates

It's a good practice to keep backups of your templates:
- You can export existing templates using the "Export" button in the template settings
- Save these JSON files in a secure location for future use

## Additional Resources

- [Obsidian Help: Templates](https://help.obsidian.md/Plugins/Templates)
- [Obsidian Forum: Web Clipper Discussions](https://forum.obsidian.md/)
