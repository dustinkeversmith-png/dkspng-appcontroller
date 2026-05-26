
# Shortcut

Shortcut/Obsidian

### Method 1: The Quick Copy-Paste (Best for Initial Setup)

If you just built a perfect layout and want your new or other vaults to match it right now, you can manually copy your configuration folder.

1. Close Obsidian to prevent file conflicts.
    
2. Open your system's file manager (File Explorer on Windows or Finder on macOS) and navigate to your **source vault** folder.
    
3. Reveal hidden files to see the `.obsidian` folder:
    
    - **Windows:** Check the **View** tab at the top and ensure **Hidden items** is checked.
        
    - **macOS:** Press `Cmd + Shift + .` (period).
        
4. Copy the entire `.obsidian` folder.
    
5. Navigate to your **destination vault**, paste the folder, and choose **Replace/Overwrite** if prompted.
    

> ⚠️ **Note:** This copies everything, including your `workspace.json` file, which tracks open tabs. When you open the destination vault, it might look for notes from your first vault that don't exist. Simply close those empty tabs, and your plugins, snippets, and themes will remain fully intact.

### Method 2: Create a "Template Vault" (Best for Future Vaults)

If you frequently spin up new project vaults and want a consistent starting line, turn your ideal setup into a blueprint.

1. Configure a blank vault exactly how you like it (install your go-to plugins, themes, and core settings), but leave it entirely empty of actual markdown notes.
    
2. Name this folder something like `_Vault_Template`.
    
3. Whenever you need a new vault, simply duplicate that template folder in your file explorer, rename the copy to your new project name, and open it in Obsidian.