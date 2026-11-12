# Kael

Kael is a local-first AI companion for Windows. The model, the voice and your
conversation history stay on your own machine — nothing is sent to us.

**This repository hosts release downloads only.** The application source is not
published here.

## Download

Grab the latest installer from **[Releases](https://github.com/Kizvi/kael-release/releases/latest)**,
or from [kaelith.ca/download.html](https://kaelith.ca/download.html), which always
points at the current version.

- **Windows 10 (1809 or later) 64-bit, or Windows 11**
- ~1 GB download, ~2 GB installed
- Per-user install into `%LOCALAPPDATA%\Programs\Kael` — no administrator rights
  and no UAC prompt
- A licence key is required; activation happens on first launch

## Verifying a download

An installer this size deserves a check before you run it. Every release lists
the SHA-256 of its `Kael-Setup-*.exe` in the release notes. To compare on
Windows:

```powershell
Get-FileHash .\Kael-Setup-1.0.0.exe -Algorithm SHA256
```

The two strings must match exactly. If they don't, delete the file and download
it again — do not run it.

The installer is not yet code-signed, so Windows SmartScreen will show
"unrecognised app" on first run. That is expected. Choose **More info → Run
anyway**. Code signing is planned.

## Support

- Email: **support@armyoftheone.art**
- Website: [kaelith.ca](https://kaelith.ca)

Issues are not tracked in this repository — email reaches us faster.

---

Kael is built and published by [Army of the One](https://armyoftheone.art).
