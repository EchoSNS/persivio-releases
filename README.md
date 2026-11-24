# Persivio downloads

Installers and update files for **Persivio**, a download manager for Windows, macOS and Linux.
See [Releases](../../releases/latest).

| System | File |
|---|---|
| Windows | `Persivio_x.y.z_x64-setup.exe` (or the `.msi`) |
| macOS 11 or newer | `Persivio_x.y.z_universal.dmg` |
| Linux | `.AppImage` or `.deb` |
| Browser | `Persivio-extension_x.y.z.zip` (see the README inside) |

The installers are not code-signed yet, so Windows and macOS show a warning. Compare your
file with `SHA256SUMS.txt` in the release:

```powershell
Get-FileHash .\Persivio_x.y.z_x64-setup.exe
```

Updates inside the app are always signed and verified, independent of that warning.

Persivio is licensed under MIT or Apache-2.0. Download and share only what you have the right to.
