# cxs-methodology-manager

A fully offline, single-file knowledge base for bug bounty and hacking methodologies. Manage, edit, search, and back up your hacking techniques—no network required, 100% privacy.

---

[![Buy Now](https://img.shields.io/badge/Buy%20Now-Click%20Here-brightgreen?style=for-the-badge)](https://shop.cyberxsociety.com/product/cxs-methodology-manager/)



---

# Documentation


# CXS Methodology Manager

**CXS Methodology Manager** is an advanced, fully offline, single-file HTML/CSS/JS tool designed for bug hunters, hackers, and cybersecurity professionals to organize, manage, and execute hacking methodologies, commands, and notes. All data is automatically saved in your browser’s local storage—no external dependencies, no server, and no internet required.

---

## Features

### 1. Method Management
- **Add New Methods:**  
  - Click the "+" button or use `Alt+N` to quickly add a new methodology.
  - Each method can have a title, tags, and multiple description/command pairs.
- **Edit Methods:**  
  - Click the pencil (✎) icon to edit a method’s title, tags, descriptions, and commands.
  - **Delete Icon Behavior:** Double-click the pen (edit) icon to reveal the delete (trash) icon. The delete icon will disappear if you click outside or anywhere else on the page.
  - Inline editing with validation to prevent duplicate or empty titles.
- **Delete Methods:**  
  - When the delete icon is visible (after double-clicking the pen icon), click it to delete the method.
  - Choose between permanent deletion or temporary (move to Recently Deleted).

### 2. Description & Command Pairs
- **Multiple Pairs per Method:**  
  - Each method can have several description/command pairs (e.g., explanation + command).
  - Add new pairs with the "+" button inside the method.
- **Drag-and-Drop Reordering:**  
  - Rearrange description/command pairs within a method using drag.
  - Methods themselves can also be reordered via drag-and-drop.

### 3. Search & Filter
- **Search Bar:**  
  - Click the search icon or press `Ctrl+F` to open the search bar.
  - Search by method title, description text, or command.
  - Highlights all matches and allows navigation between them.
- **Tag Filtering:**  
  - Filter methods by tags using the dropdown at the top.

### 4. Backup & Restore
- **Backup:**  
  - Download all your methods and commands as a JSON file for safekeeping.
- **Restore:**  
  - Restore from a backup file, either replacing or merging with current data.
  - Preview backup contents before restoring.

### 5. Undo & Redo (**NEW**)
- **Global Undo/Redo:**  
  - Instantly undo or redo any change (add, edit, delete, reorder, backup restore/merge, etc.) using `Ctrl+Z` (undo) and `Ctrl+Y` (redo).
  - Works for all actions, including mistakes during backup restore/merge or accidental deletions.
  - Undo/redo is **session-based**: history is cleared when you close or reload the browser tab.

### 6. Recently Deleted
- **Trash Bin:**  
  - Temporarily deleted methods are moved to "Recently Deleted."
  - Restore or permanently delete from the trash.
  - Option to clear all recently deleted items.

### 7. Theme Support
- **Theme Cycling:**  
  - Switch between Light, Dark, and Solarized themes with the theme button.
  - Theme preference is saved in local storage.

### 8. Statistics
- **Footer Stats:**  
  - Displays the number of methods, commands, and recently deleted items.

### 9. Social & Sharing
- **Social Bar:**  
  - Quick links to the official website, Telegram, Twitter/X, and GitHub.
- **Share Button:**  
  - Share the project link via native share dialog or copy to clipboard.

---

## Usage Guide

### Adding a Method
1. Click the "+" button at the top right or press `Alt+N`.
2. Enter a method name, optional tags (comma-separated and you can set it only when you create new methods and can't edit next time), description, and command.
3. Click the checkmark (✔) to save.
4. **Note:** After saving a new method, the browser will automatically refresh. This ensures all features (like drag-and-drop, search, and tag filters) are fully re-initialized and bug-free for the new method. This refresh is intentional to maintain a stable and consistent user experience.

### Editing a Method
1. Click the pencil (✎) icon next to a method.
2. Edit the title, descriptions, or commands.
3. **To delete:** Double-click the pen icon to reveal the trash icon, then click the trash icon. The delete icon will disappear if you click outside the method.
4. Click the checkmark (✔) to save changes.

### Deleting a Method
- When the delete icon is visible (after double-clicking the pen icon), click it to delete the method.
- Choose "Yes" for permanent deletion or "Temporary" to move to Recently Deleted.

### Adding Description/Command Pairs
- While editing a method, click the "+" button inside the method to add more pairs.

### Reordering
- Drag the method header to reorder methods.
- Drag description/command pairs within a method.

### Undo & Redo (**NEW**)
- Press `Ctrl+Z` to undo your last change, or `Ctrl+Y` to redo.
- Undo/redo works for all actions, including backup restore/merge, add, edit, delete, and drag-and-drop.
- **Note:** Undo/redo history is cleared when you close or reload the browser tab.

### Search & Filter
- Click the search icon or press `Ctrl+F` to search.
- Use the dropdown to filter by method, text, or command.
- Use the tag filter to show only methods with a specific tag.

### Backup & Restore
- Click "Backup" in the footer to download your data.
- Click "Restore" to import a backup (replace or merge).

### Recently Deleted
- Click "Recently Deleted" in the footer to view, restore, or permanently delete items.

### Theme
- Click the theme button at the bottom to cycle through Light, Dark, and Solarized themes.

---

## Data Storage

- **All data is stored locally in your browser’s local storage.**
- No data is sent to any server.
- Works fully offline.
- **Undo/redo history is NOT saved to local storage and is lost when you close or reload the browser.**

---

## Accessibility & Shortcuts

- **Keyboard Shortcuts:**
  - `Alt+N`: Quick add new method
  - `Ctrl+F`: Open search bar
  - `Ctrl+Z`: Undo last change (**NEW**)
  - `Ctrl+Y`: Redo last undo (**NEW**)
  - `Escape`: Close search or clear search input
  - `Arrow Up/Down`: Navigate search results

- **Accessible UI:**  
  - All buttons and inputs are accessible via keyboard and have ARIA labels.

---

## Social & Project Links

- [Official Website](https://cyberxsociety.com/)
- [Telegram](https://t.me/CyberXsociety)
- [Twitter/X](https://x.com/CyberXsociety)
- [GitHub Documentary](https://github.com/CyberXsociety/cxs-methodology-manager)
- [Share this project](https://shop.cyberxsociety.com/product/cxs-methodology-manager/)

---

## Technical Notes

- **Single-file HTML/CSS/JS:**  
  - No external libraries or dependencies.
  - All logic, styles, and UI are contained in one file.
- **Manual Drag-and-Drop:**  
  - Custom drag-and-drop for both methods and description/command pairs.
- **No External Storage:**  
  - 100% offline, privacy-respecting.
- **Undo/Redo:**  
  - Undo/redo is in-memory only and is not persisted between sessions.

---

## Tips & Warnings

- **Tips:**
  - Regularly use the Backup feature to save your data externally, especially before clearing browser data or switching devices.
  - Use tags to organize and quickly filter your methodologies.
  - Use the search and tag filter to quickly find specific methods or commands.
  - Make use of keyboard shortcuts for faster workflow.
  - Use undo/redo (`Ctrl+Z`/`Ctrl+Y`) to quickly recover from mistakes during editing, deleting, or restoring/merging backups.

- **Warnings:**
  - **Do NOT clear your browser’s local storage unless you have backed up your data.** All methods and commands will be lost.
  - **Do NOT use this tool for storing sensitive credentials or secrets.** While data is local, browsers are not designed for high-security storage.
  - **Do NOT open the file in multiple tabs and edit simultaneously.** This may cause data loss or overwrite issues.
  - **Do NOT rely solely on browser storage for long-term retention.** Always keep external backups.
  - **Do NOT share your backup file with others unless you are sure it contains no sensitive information.**
  - **Undo/redo history is lost when you close or reload the browser tab.**

---

## Ideal Use Cases

- Bug bounty hunters and penetration testers organizing attack methodologies.
- Red teamers and security researchers managing reusable command snippets.
- Anyone needing a portable, offline, and private methodology/command manager.

---

## FAQ

**Q: Is my data safe?**  
A: Yes, all data is stored locally in your browser. No data leaves your device.

**Q: Can I use this offline?**  
A: Absolutely! The tool is designed to work fully offline.

**Q: Can I import/export my data?**  
A: Yes, use the Backup and Restore features in the footer.

**Q: How do I reorder items?**  
A: Drag the method header to reorder methods, or the ≡ handle to reorder description/command pairs.

**Q: Can I undo/redo any action?**  
A: Yes! Use `Ctrl+Z` to undo and `Ctrl+Y` to redo any change made during your current session. Undo/redo history is cleared when you close or reload the browser tab.

**Q: Why does the browser refresh after I save a new method?**  
A: The automatic refresh ensures that all UI features (such as drag-and-drop, search, and tag filters) are fully re-initialized and work correctly for the new method. This helps prevent bugs and keeps the interface stable after adding new content.

---

If you need further help or want to contribute, visit the [GitHub Documentary](https://github.com/CyberXsociety/cxs-methodology-manager). 
