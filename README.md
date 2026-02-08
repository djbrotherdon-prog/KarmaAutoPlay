# Karma AutoPlay Helper

This is a small, one-time helper utility for **Karaosoft Karma**.

Recent versions of Karma removed the **GUI checkboxes** that previously allowed users to automatically enable AutoPlay when adding songs to the playlist.  
However, the **backend functionality still exists** — it just requires two settings to be present in the user configuration file.

This tool simply adds or updates those settings.

---

## What this tool restores

The following two AutoPlay options were removed from the Karma user interface, but are still supported internally:

- **Automatically set any “Singerless” media to AutoPlay**
- **Automatically set singer-assigned media to AutoPlay**

This utility allows you to turn those options **On or Off** again.

---

## What the tool does (and does NOT do)

**What it does:**
- Updates your personal `user.config` file used by Karma
- Adds the missing AutoPlay settings if they do not exist
- Allows you to toggle them On or Off
- Launches Karma after the change is made

**What it does NOT do:**
- ❌ Does not modify Karma executables
- ❌ Does not patch or hook Karma
- ❌ Does not add unsupported features

It only sets configuration values that Karma already understands and uses.

---

## First-time run behavior (important)

When you run the tool **for the first time**:

1. You will be prompted **twice** to choose:
   - **On** or **Off** for Karma AutoPlay
2. The tool will:
   - Apply the settings
   - Create a **desktop shortcut** for future use
3. Karma will then launch automatically

After that, you can simply use the desktop shortcut whenever you want to change the setting again.

---

## How to use

1. Download `KarmaAutoPlay.exe`
2. Double-click to run
3. Choose **On** or **Off** when prompted
4. Karma will start with the selected behavior applied

Windows may display a warning about an unknown publisher.  
This is normal for small personal utilities — click **More info → Run anyway**.

---

## Notes

- This is intended as a **one-time workaround** for a removed UI feature
- If Karaosoft restores these options in a future update, this tool will no longer be necessary
- Settings are user-specific and do not affect other users on the system

---

## Disclaimer

This project is not affiliated with or endorsed by Karaosoft.  
It exists solely to restore access to configuration options that are still present in the software but no longer exposed in the user interface.
