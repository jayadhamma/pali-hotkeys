# PALI UNICODE HOTKEYS (Jaya 2025)

## Overview

This AutoHotkey script lets you type all the Pali diacritics (and several extended letters) quickly using Alt, Shift, and Ctrl combinations. It is based on an earlier script by Ānandajoti Bhikkhu, expanded to include the extra characters I needed. For more Dhamma resources go to [http://www.nibbida.com](http://www.nibbida.com)

## How to use

- **Alt + key** gives the lowercase diacritic letter.  
- **Alt + Shift + key** gives the uppercase.  
- **Ctrl** is used for dot-below vs dot-above variants where both exist.

## FULL HOTKEY LIST

| Letter Type | Key Combination | Character |
|------------|----------------|-----------|
| Vowels (macrons) | Alt + a | ā |
| | Alt + i | ī |
| | Alt + u | ū |
| | Alt + e | ē |
| | Alt + o | ō |
| | Alt + Shift + a | Ā |
| | Alt + Shift + i | Ī |
| | Alt + Shift + u | Ū |
| | Alt + Shift + e | Ē |
| | Alt + Shift + o | Ō |
| Consonants with dot below | Alt + t | ṭ |
| | Alt + d | ḍ |
| | Alt + n | ṇ |
| | Alt + l | ḷ |
| | Alt + s | ṣ |
| | Alt + Shift + t | Ṭ |
| | Alt + Shift + d | Ḍ |
| | Alt + Shift + n | Ṇ |
| | Alt + Shift + l | Ḷ |
| | Alt + Shift + s | Ṣ |
| Nasals / special letters | Alt + m | ṁ |
| | Alt + Shift + m | Ṁ |
| | Alt + Ctrl + m | ṃ |
| | Alt + Ctrl + Shift + m | Ṃ |
| | Alt + Ctrl + n | ṅ |
| | Alt + Ctrl + Shift + n | Ṅ |
| | Alt + h | ḥ |
| | Alt + Shift + h | Ḥ |
| Additional diacritics | Alt + r | ṛ |
| | Alt + Shift + r | Ṛ |
| | Alt + Ctrl + r | ṝ |
| | Alt + Ctrl + Shift + r | Ṟ |
| | Alt + Ctrl + s | ś |
| | Alt + Ctrl + Shift + s | Ś |

## INSTALLATION

### Option A — Create your own shortcut in the Startup folder (recommended if Windows blocks the EXE)

Some users find that Windows silently blocks downloaded.exe files. In that case:

1. Right-click **Pali-Unicode-Jaya2025.exe** and choose "Create shortcut".  
2. Press **Win + R**, type: `shell:startup`, press Enter.  
3. Or go directly to the Startup folder at:  
C:\Users\YOURUSERNAME\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup  
*(This path is for Windows 10 and Windows 11.)*  
4. Move the shortcut into that folder.  
5. Double-click the shortcut once to allow Windows to trust the file.  

This avoids SmartScreen or blocking issues.

### Option B — Run the included EXE normally

1. Double-click **Pali-Unicode-Jaya2025.exe** to activate the hotkeys.  
2. To autostart at login:  
- Press **Win + R**, type: `shell:startup`, press Enter.  
- Or navigate to:  

  ```
  C:\Users\YOURUSERNAME\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
  ```  

  *(Windows 10/11)*  
- Copy the `.exe` into that folder.  

### Option C — Use the AHK script

1. Install AutoHotkey from [https://www.autohotkey.com](https://www.autohotkey.com)  
2. Double-click **Pali-Unicode-AutoHotkeyScript-Jaya2025.ahk**.  
3. To autostart:  
- Press **Win + R**, type: `shell:startup`, press Enter.  
- Or go to:  

  ```
  C:\Users\YOURUSERNAME\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
  ```  

  *(Windows 10/11)*  
- Copy the `.ahk` file into that folder.  

## Notes

- Creating a shortcut manually (Option A) is reliable and avoids Windows blocking.  
- If characters show incorrectly, switch to a Unicode font such as **Noto Serif**, **Gentium**, or **Charis SIL**.  
- You can freely edit or remap any hotkey by opening the `.ahk` file in a text editor.  

## ACKNOWLEDGMENT

This script is based on an earlier version by Ānandajoti Bhikkhu, expanded to include the extra characters I needed.  
For more Dhamma resources visit: [http://www.nibbida.com](http://www.nibbida.com)
