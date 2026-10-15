# Nightman

Installers for Nightman, which keeps a folder of Ableton Live Projects in order: Fields on each Project, a Layout that sorts them into folders, and nightly Backups. This repo holds only the releases.

## Installing

Download the newest release from [the releases page](https://github.com/BAD-LISTENER-Labs/nightman-releases/releases/latest):

| Computer | File |
|---|---|
| Windows | `Nightman_<version>_x64-setup.exe` |
| macOS (Apple silicon or Intel) | `Nightman_<version>_universal.dmg` |
| Linux | `Nightman_<version>_amd64.AppImage` |

Nightman isn't signed by Microsoft or Apple, so the first time you open it your computer warns that it doesn't know who made it. That's expected. Here's how to get past the warning.

### Windows: SmartScreen

1. Run the installer. Windows says "Windows protected your PC".
2. Click **More info**, then **Run anyway**.
3. The installer then runs as usual. Nightman is in the Start menu afterwards.

### macOS: Gatekeeper

1. Open the `.dmg` and drag Nightman into Applications.
2. Open Nightman from Applications. macOS says it can't verify the developer. Click **Done** (or **Cancel**).
3. Open **System Settings → Privacy & Security**, scroll down to the message about Nightman, and click **Open Anyway**. Confirm with your password.

   On older macOS versions you can instead **right-click** (or Control-click) Nightman in Applications, choose **Open**, and then click **Open** in the dialog.

You only do this once. After that Nightman opens like any other app.

### Linux

Make the AppImage executable (`chmod +x Nightman_*.AppImage`) and run it.

## Updates

When Nightman starts, it checks the releases page for a newer version. If it finds one, it asks before installing anything. Each update is signed with Nightman's own key, and the app refuses one whose signature doesn't match. To stop checking, open **Setup…** and untick **Check for a newer version of Nightman when it starts**.

