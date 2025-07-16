# cxs-methodology-manager

A fully offline, single-file knowledge base for bug bounty and hacking methodologies. Manage, edit, search, and back up your hacking techniques—no network required, 100% privacy.

---

[![Buy Now](https://img.shields.io/badge/Buy%20Now-Click%20Here-brightgreen?style=for-the-badge)](YOUR_PROJECT_LINK_HERE)



---

# Documentation


## Overview

This is a fully offline, single-file web application for managing, editing, and backing up hacking/bug bounty methodologies. It is designed for bug hunters and hackers, with all data stored locally in your browser (no network required, no external dependencies).

---

## Features

### 1. **Method List**
- **Display:** Shows a list of all your methods, each with a title and one or more description/command pairs.
- **Expand/Collapse:** Click a method’s title to expand/collapse its details.
- **Edit:** Click the ✎ icon to edit a method’s title, descriptions, and commands.
- **Add:** Use the + button to add a new method.
- **Delete:** click two times on ✎ icon, a trash icon appears to delete the method (permanently or temporarily).
- **Drag & Drop:** Reorder methods by dragging their headers.

### 2. **Description & Command Pairs**
- Each method can have multiple description/command pairs.
- **Add Pair:** Use the small + button inside a method to add more pairs.
- **Edit Pair:** When editing a method, you can edit the description and command.
- **Copy Command:** Click the "Copy" button to copy a command to your clipboard.

### 3. **Search**
- **Open Search:** Click the magnifying glass or press `Ctrl+F`.
- **Filter:** Search by method title, description text, or command.
- **Highlight:** Matches are highlighted; use arrows to jump between them.
- **Expand on Match:** Methods with matches auto-expand.

### 4. **Backup & Restore**
- **Backup:** Download all your methods as a JSON file.
- **Restore:** Upload a backup JSON to restore/replace all methods.
- **Warning:** Restoring will overwrite your current methods.

### 5. **Recently Deleted**
- **Temporary Delete:** Temporarily delete methods; they go to the "Recently Deleted" bin.
- **Restore:** Restore deleted methods from the bin.
- **Permanent Delete:** Permanently remove methods from the bin.
- **Delete All:** Remove all recently deleted methods at once.

### 6. **Theme Switching**
- **Cycle Theme:** Click the theme button to switch between Light, Dark, and Solarized themes.
- **Persistence:** Your theme choice is saved in local storage.

### 7. **Statistics**
- Footer displays counts for:
  - Total methods
  - Total commands
  - Recently deleted methods

### 8. **Accessibility & Responsiveness**
- Fully keyboard accessible (tab, enter, escape, etc.).
- Responsive design for mobile and desktop.

---

## How It Works

### Data Storage

- **Local Storage:** All methods, commands, and recently deleted items are saved in your browser’s local storage.
- **No Server:** No data ever leaves your device.

### Adding a Method

1. Click the **+** button (top right).
2. Enter a method name, description, and command.
3. Click the ✔ (checkmark) to save.
4. You can add more description/command pairs using the small + button inside the method.

### Editing a Method

1. Click the **✎** icon next to a method.
2. Edit the title, descriptions, or commands.
3. Click ✔ to save changes.

### Deleting a Method

  - **Click 2 times ✎:** Click the ✎ icon 2 times trash/delete icon will show and if you dont want to delete so it will hide automatically when you click outside (anywhere).
  - **Permanent:** Removes the method forever.
  - **Temporary:** Moves the method to "Recently Deleted" (can be restored).

### Restoring a Method

1. Click the **Recently Deleted** button (footer).
2. Click **Restore** next to a method to bring it back.

### Backup & Restore

- **Backup:** Click **Backup** (footer), then **Download Backup** to save a JSON file.
- **Restore:** Click **Restore** (footer), select a backup file, and confirm to replace all methods.

### Search

- Click the magnifying glass or press `Ctrl+F`.
- Enter your search term.
- Choose to search by method, text, or command.
- Use the up/down arrows to jump between matches.

### Theme

- Click the theme button (bottom of the page) to cycle through Light, Dark, and Solarized themes.

---

## Developer Notes

- **Single File:** All HTML, CSS, and JS are in one file for easy portability.
- **No Dependencies:** No external libraries or frameworks.
- **Offline:** Works without internet.

---

## Keyboard Shortcuts

- **Ctrl+F:** Open search bar.
- **Escape:** Close search or clear search input.
- **Alt+N:** Quick add a new method (unless editing or in an input).
- **Arrow Up/Down:** Navigate between search matches.

---

## Accessibility

- All buttons and inputs are accessible via keyboard.
- ARIA labels and roles are used for screen readers.
- Responsive for all device sizes.

---

## Troubleshooting

- **Data Loss:** If you clear your browser’s local storage, your methods will be lost unless you have a backup. (use separate browser for it like Microsoft edge if you dont use)
- **Restore Overwrites:** Restoring a backup will replace all current methods.
- **Browser Support:** Works in all modern browsers.

---

## Customization

- You can edit the HTML/CSS/JS directly in the file to add more features or change the look.
- All logic is in the `<script>` tag at the bottom of the file.

---

## Example Use Case

1. Add a method: "Find Directories of Target" with a description and a `gobuster` command.
2. Add another method: "Enumerate Subdomains" with multiple description/command pairs.
3. Use the search to quickly find "nmap" commands.
4. Backup your methodology before clearing your browser or moving to another device.

---

## Security & Privacy

- **No network requests:** 100% offline.
- **No analytics or tracking.**
- **All data is local.**

---

## Summary

This app is a powerful, portable, and private knowledge base for bug bounty and hacking methodologies. It’s designed for speed, flexibility, and total offline use, with robust features for editing, searching, backup, and recovery. 
