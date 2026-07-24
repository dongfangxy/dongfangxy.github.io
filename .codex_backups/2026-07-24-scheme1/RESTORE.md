# Scheme 1 CSS Backup

This directory contains the original `css/yucss.css` from before the
2026-07-24 Scheme 1 appearance refinement.

- Original SHA-256: `FC5C50B30EC15DB829A8FCE77C4DD1E3F3C6977B69E670CFC1D70BF577B15DFB`
- Backup file: `.codex_backups/2026-07-24-scheme1/yucss.css`

Restore from the repository root with PowerShell 7:

```powershell
pwsh -NoLogo -NoProfile -Command 'Copy-Item -LiteralPath ''.codex_backups\2026-07-24-scheme1\yucss.css'' -Destination ''css\yucss.css'' -Force'
```

Verify the restored file:

```powershell
pwsh -NoLogo -NoProfile -Command 'Get-FileHash -Algorithm SHA256 -LiteralPath ''css\yucss.css'''
```
