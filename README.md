# Karma AutoPlay Helper

This is a small helper utility for **Karaosoft Karma** that restores access to AutoPlay options that were removed from the Karma user interface but are still supported by the software.

Recent versions of Karma removed the GUI checkboxes that controlled AutoPlay behavior when adding songs to the playlist.  
However, the underlying settings and logic still exist in Karma’s configuration.

This tool simply exposes those settings again in a safe, user-friendly way.

---

## What this tool restores

The following AutoPlay options were removed from the Karma GUI but are still honored internally:

- **Automatically set singer-assigned media to AutoPlay**
- **Automatically set any “Singerless” media to AutoPlay**

Each option can now be enabled or disabled **independently**.

---

## What the tool does (and does NOT do)

**What it does:**
- Reads and updates your personal `user.config` file used by Karma
- Adds the missing AutoPlay settings if they do not exist
- Lets you enable or disable each setting individually using checkboxes
- Creates a desktop shortcut for easy future access
- Launches Karma after changes are applied

**What it does NOT do:**
- ❌ Does not modify Karma executables
- ❌ Does not patch, hook, or inject into Karma
- ❌ Does not add unsupported features

It only updates configuration values that Karma already understands and uses.

---

## First-time run behavior

When you run the tool **for the first time**:

1. It installs itself to a stable location (`C:\tools`)
2. A **desktop shortcut** named **“Karma AutoPlay”** is created
3. The settings window opens **once** (no duplicate prompts)

After the first run, you should always use the **desktop shortcut**.

---

## Using the tool

1. Double-click **Karma AutoPlay**
2. Choose your preferred settings:
   - ☑ Singer-assigned media AutoPlay
   - ☑ Singerless media AutoPlay
3. Click **Apply**
4. Karma will launch with the updated behavior

---

## Current settings display

The window shows:
- **Current settings** as read from Karma’s `user.config`
- **Selected settings** that will be applied

This makes it easy to see exactly what will change before clicking Apply.

---

## Safety and backups

- A backup of `user.config` is created before any changes are made
- Only the **two most recent backups** are kept automatically
- Settings are user-specific and do not affect other users on the system

---

## Notes

- This is intended as a **one-time workaround** for a removed UI feature
- If Karaosoft restores these options in a future update, this tool will no longer be necessary
- The tool can be safely deleted once the settings are configured

---

## Disclaimer

This project is **not affiliated with or endorsed by Karaosoft**.

It exists solely to restore access to configuration options that remain functional in Karma but are no longer exposed in the user interface.
