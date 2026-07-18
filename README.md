# Njokey Presence - Downloads

Public download hub for **Njokey Presence**, a desktop app for consent-based location
verification of remote employees.

## Download

| Platform | File |
|---|---|
| Windows 10/11 (x64) | [Njokey-Presence-Setup.exe](https://github.com/legiesaya/njokey-downloads/releases/latest/download/Njokey-Presence-Setup.exe) |

Permanent "always latest" link for websites:

```
https://github.com/legiesaya/njokey-downloads/releases/latest/download/Njokey-Presence-Setup.exe
```

## Verify your download

SHA-256:

```
f24f0f2de7b1288a9c7ccd1481b2840507936bba358e3640f3480c8974b706c3
```

Check it in PowerShell:

```powershell
Get-FileHash .\Njokey-Presence-Setup.exe -Algorithm SHA256
```

## Installing

The installer is per-user, so no administrator rights are needed. It creates desktop and
Start-menu shortcuts.

The installer is not yet code-signed, so Windows SmartScreen may warn about an "unknown
publisher" the first time. Choose **More info** then **Run anyway**.

## Note

This repository hosts release binaries only. The application source is maintained separately.
