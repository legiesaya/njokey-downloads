# Njokey Presence - Downloads

Public download hub for **Njokey Presence**, a desktop app for consent-based location
verification of remote employees.

## Download

| Platform | File |
|---|---|
| Windows 10/11 (x64) | [Njokey-Presence-Setup-0.1.0.exe](https://github.com/legiesaya/njokey-downloads/releases/latest/download/Njokey-Presence-Setup-0.1.0.exe) |

Permanent "always latest" link for websites:

```
https://github.com/legiesaya/njokey-downloads/releases/latest/download/Njokey-Presence-Setup-0.1.0.exe
```

## Verify your download

SHA-256:

```
b9cd76a03f9fed60216c6e364b501ad761ac957da0744eff7a323ee976b4c42a
```

Check it in PowerShell:

```powershell
Get-FileHash .\Njokey-Presence-Setup-0.1.0.exe -Algorithm SHA256
```

## Installing

The installer is per-user, so no administrator rights are needed. It creates desktop and
Start-menu shortcuts.

The installer is not yet code-signed, so Windows SmartScreen may warn about an "unknown
publisher" the first time. Choose **More info** then **Run anyway**.

## Note

This repository hosts release binaries only. The application source is maintained separately.
