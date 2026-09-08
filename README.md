# Dcecheck

VB6 WMI-based DCE status checker derived from the Microsoft WMI SDK process-management sample. Connects to a local or remote `winmgmts` host, asynchronously enumerates `Win32_Process`, and reports whether DCE RPC, Directory, DTS, Security Client, and Integrated Logon processes are running or configured. UI caption is "DCE Status"; output binary is `DCECheck.exe`.

**Source last updated:** 1997-06-01 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `DCECheck` (`Dcecheck.vbp`) | VB6 | WinForms exe | WMI DCE process/status monitor |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Dcecheck.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Microsoft WBEM Scripting library (WMI)
- Registered OCX dependencies referenced by the `.vbp` (may need to be installed separately):
  - `MSCOMCT2.OCX`
  - `MSCOMCTL.OCX`

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Dcecheck`.
Based on Microsoft WMI SDK sample (copyright 1997-1999 Microsoft Corporation). Company name in project file: Microsoft.

## License

MIT © 2026 VaderConsulting for Dave Robinson's modifications. Original Microsoft sample code remains under its original terms. See `LICENSE`.
