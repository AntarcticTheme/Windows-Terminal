# Antartic Windows Terminal
Antartic for the Windows Terminal.

## Installation 
1. Open Windows Terminal
2. Click Settings
3. Open JSON File

From the JSON file, replace the contents of `"defaults"` 

```pwsh
    "profiles": 
    {
        "defaults": {},
```

with the contents of `windows-terminal-theme.json`.

Under `"schemes":`
```
"schemes": 
    [
```
Paste the contents of `windows-terminal-palette`.

Now, save the file and restart the terminal.