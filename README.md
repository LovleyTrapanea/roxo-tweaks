# roxo-tweaks
A themed Windows tweaking utility with a soft Halloween look. Apply and undo privacy, performance and Explorer tweaks, and control Windows Update.

# Roxo Tweaks

A themed Windows tweaking utility with a soft Halloween look, built with PowerShell and WPF.

## Features

- **Tweaks:** privacy, performance, Explorer and cleanup tweaks. Every tweak can be undone, except the two cleanup ones.
- **Updates:** choose between default, security only, or disabled Windows Update. Also includes quick tools to open Windows Update, update apps with winget, and repair Windows Update.
- **Safety:** can create a system restore point before applying tweaks.

## Run

Open PowerShell as Administrator and run:

```
irm https://raw.githubusercontent.com/USERNAME/roxo-tweaks/main/RoxoTweaks.ps1 | iex
```

## Requirements

- Windows 10 or Windows 11
- PowerShell 5.1 or newer
- Administrator rights

## Disclaimer

Use at your own risk. Create a restore point before applying tweaks. Some changes need a sign-out or restart to take effect.
