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

```pwsh
"schemes": 
    [
```
Paste the contents of `windows-terminal-palette`.

Now, save the file and restart the terminal.

## Oh My Posh + Windows Terminal
If you are planning on using the Antartic for Oh My Posh theme, please check the [README.md](https://github.com/AntarticTheme/Oh-My-Posh#oh-my-posh--windows-terminal) for further instructions. 