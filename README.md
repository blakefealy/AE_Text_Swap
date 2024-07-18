# AE_Text_Swap
SUMMARY: This script will swap the text values of two selected text layers in the timeline of an After Effects composition
CREDIT: Blake Fealy

### Installing and Assigning a Keyboard Shortcut to `Text_Swap.jsx` in Adobe After Effects

#### Installing JSX file

###### Windows

1. **Copy the JSX File**:
   - Copy `Text_Swap.jsx` to the following directory:
     ```
     C:\Program Files\Adobe\Adobe After Effects <version>\Support Files\Scripts
     ```
   - To appear in the "Scripts" menu instead of "File > Scripts," place it in:
     ```
     C:\Program Files\Adobe\Adobe After Effects <version>\Support Files\Scripts\ScriptUI Panels
     ```

1.5. **Restart After Effects**:
   - If After Effects was open during installation, restart it.

###### Mac

1. **Copy the JSX File**:
   - Copy `Text_Swap.jsx` to the following directory:
     ```
     /Applications/Adobe After Effects <version>/Scripts
     ```
   - To appear in the "Scripts" menu instead of "File > Scripts," place it in:
     ```
     /Applications/Adobe After Effects <version>/Scripts/ScriptUI Panels
     ```
### Assigning Script As Keyboard Shortcut

2. **Restart After Effects**:
   - If After Effects was open during installation, restart it.

2. **Edit the `Shortcuts` File**:
- Open the `Adobe After Effects <version> Prefs` file in a text editor.

3. **Add the Shortcut**:
- Find the `[“Main”]` section in the file. This is where you can define custom shortcuts.
- Add an entry for your script. The format for adding a new shortcut is as follows:
  ```
  “Text_Swap.jsx” = “<Shortcut>”;
  ```
  For example, if your script is named `Text_Swap.jsx` and you want to assign `Ctrl+Alt+M` (Windows) or `Cmd+Opt+M` (Mac) as the shortcut:
  ```
  “Text_Swap.jsx” = “Ctrl+Alt+M”;  // For Windows
  “Text_Swap.jsx” = “Cmd+Opt+M”;   // For Mac
  ```

4. **Save and Close the File**:
- Save the `Prefs` file and close the text editor.

5. **Restart After Effects**:
- Restart After Effects for the changes to take effect.
