
# Qres-Powershell

A script that works like qres.exe to modify, display resolution and refresh rate of your monitor via powershell cli.

# Usage

Set resolution to 1920x1080 with a 60Hz refresh rate.

```pwsh
.\qres-powershell.ps1 1920 1080 60
```

# Possible Issues

- The refresh should match the available refresh rates in the display settings. Ex: you will need to 143.80, instead of 144. if your display settings in windows shows only 143.80 as an option.

# Todo

- add an option for scaling
- kill explorer and start explorer ?