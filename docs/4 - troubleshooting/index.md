# Troubleshooting

> [!WARNING]
> Before making any major changes to your vault, consider creating a backup of your files to prevent data loss.

## Common Issues & Solutions

| Problem | Solution |
|---------|----------|
| Obsidian won't open my vault | • Check if the vault folder still exists at the specified location<br>• Verify you have read/write permissions for the folder<br>• Try restarting Obsidian or your computer |
| Images aren't displaying in notes | • Verify the image path is correct and the file exists in your vault<br>• Ensure image links use relative paths (e.g., `![[image.png]]`)<br>• Check if the image format is supported (.png, .jpg, .gif, etc.) |
| Template hotkey isn't working | • Make sure the Templates core plugin is enabled in Settings<br>• Verify your template folder path is correctly set<br>• Check for hotkey conflicts in Settings > Hotkeys |
| Notes aren't appearing in graph view | • Check if your notes contain any links to other notes<br>• Verify the notes are within your vault<br>• Try adjusting the graph view filters |
| Text formatting isn't appearing correctly | • Ensure you're using proper Markdown syntax<br>• Check for missing spaces after formatting characters<br>• Try toggling between Edit and Preview mode |

## Advanced Troubleshooting

> [!TIP]
> For persistent issues, try these additional steps:

1. **Clear Obsidian cache**
   - Close Obsidian
   - Navigate to your vault folder
   - Delete the `.obsidian/cache` folder
   - Restart Obsidian

2. **Check for plugin conflicts**
   - Disable community plugins and see if the issue persists
   - Re-enable plugins one by one to identify the problematic one

3. **Verify file permissions**
   - Ensure your user account has full read/write access to the vault folder
   - Check if any files are locked by other applications

4. **Update Obsidian**
   - Make sure you're using the latest version of Obsidian
   - Some issues may be resolved in newer releases

> [!NOTE]
> If you're experiencing issues with specific plugins, check the plugin's GitHub repository for known issues or contact the developer.

## Getting Help

If you're still experiencing problems after trying these solutions:

- Visit the [Obsidian Forum](https://forum.obsidian.md/)
- Join the [Obsidian Discord](https://discord.gg/obsidianmd)
- Search or post in the [Obsidian Subreddit](https://www.reddit.com/r/ObsidianMD/)

> [!SUCCESS]
> Remember to provide details about your operating system, Obsidian version, and installed plugins when seeking help from the community.
