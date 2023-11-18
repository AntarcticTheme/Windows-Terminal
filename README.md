# Antarctic Windows Terminal
Antarctic for the Windows Terminal.

Please refer to the [change log](https://github.com/AntarcticTheme/Windows-Terminal/blob/main/CHANGELOG.md) for updates on our most recent modifications.

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
If you are planning on using Antarctic with Oh My Posh + Windows Terminal, please check the [README.md](https://github.com/AntarcticTheme/Oh-My-Posh#oh-my-posh--windows-terminal) for further instructions. 

<h3 align="center">
  <img src="https://github.com/AntarcticTheme/.github/blob/main/images/footer.png" alt="Footer"/><br/>
</h3>