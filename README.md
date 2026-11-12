# CompliPrint Print Connector: downloads

Installers for the **CompliPrint Print Connector**, the small program that lets
[CompliPrint](https://compliprint.patriotpf.com) print labels straight to a
store's label printers, with no print dialog.

This repository holds the installers only. The source code is private.

## Windows

**[Download the latest Windows installer](https://github.com/aka-kolton/compliprint-connector-releases/releases/latest/download/CompliPrint-Print-Connector-Setup.exe)**

- Windows 10 or 11, 64-bit.
- Installs for the person signed in to Windows, with no administrator
  password. It runs as a small dot by the clock and starts when you sign in.
- **Not code-signed yet**, so your browser and Windows each warn once. That is
  expected for this installer; the steps below get past both.

### Install on Windows

1. **Keep the download.** If your browser says the file *isn't commonly
   downloaded*:
   - **Edge:** click the **⋯** next to the download, then **Keep**, then
     **Show more**, then **Keep anyway**.
   - **Chrome:** click **Keep**.
2. **Open** `CompliPrint-Print-Connector-Setup.exe`. If a blue
   **"Windows protected your PC"** box appears, click **More info**, then
   **Run anyway**.
3. **Follow the installer** and click **Finish**. The Print Connector starts
   straight away.
4. **Check it is running:** look for the CompliPrint dot by the clock. It may
   be hidden under the **^** arrow. Grey means no CompliPrint tab is open yet,
   green means one is connected.
5. **Add your printer:** open CompliPrint in **Chrome or Edge**, go to
   **Printers → Add Printer**, and pick your printer from the list.

To update, download and run the newest installer the same way: it replaces
the old version. To uninstall: **Settings → Apps → Installed apps →
CompliPrint Print Connector → Uninstall**.

## macOS

**[Download the latest Mac installer](https://github.com/aka-kolton/compliprint-connector-releases/releases/latest/download/CompliPrint-Print-Connector.pkg)**

- macOS 13 (Ventura) or newer, Apple silicon or Intel.
- Signed with Patriot Print Fulfillment LLC's Developer ID and notarized by
  Apple, so macOS opens it without a warning.
- Installs **CompliPrint Print Connector** in Applications. It runs in the menu
  bar and starts when you log in.

### Install on a Mac

1. **Open** the downloaded `CompliPrint-Print-Connector.pkg` and follow the
   installer. It asks for your Mac password once.
2. **Check it is running:** look for the printer icon in the menu bar at the
   top of the screen.
3. **Using Safari?** Click **Continue** when the Print Connector asks to set up
   Safari printing, and enter your Mac password. Chrome and Edge need nothing.
4. **Add your printer:** open CompliPrint, go to **Printers → Add Printer**,
   and pick your printer from the list. The printer must already be added in
   **System Settings → Printers & Scanners**.

To update, run the newest installer: it replaces the old version.

## All versions

Every version is listed under [Releases](https://github.com/aka-kolton/compliprint-connector-releases/releases).
Each release carries both installers under the same file names, so the links
above always fetch the newest one.

## Help

The same setup steps are on the Help page inside CompliPrint, under
**Downloads**.
