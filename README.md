# Penelope desktop

Downloads for the Penelope desktop app. The app's source is private; this repository only holds releases.

## Linux (AppImage)

1. Install FUSE 2 once, which AppImages need. On Arch: `sudo pacman -S fuse2`.
2. Download `Penelope-linux-x86_64.AppImage` from the [latest release](https://github.com/Leabua/penelope-releases/releases/latest).
3. Make it runnable and open it:

   ```sh
   mkdir -p ~/Applications
   mv ~/Downloads/Penelope-linux-x86_64.AppImage ~/Applications/
   chmod +x ~/Applications/Penelope-linux-x86_64.AppImage
   ~/Applications/Penelope-linux-x86_64.AppImage
   ```

Penelope checks for new versions when it opens and every 6 hours. When one is out, it offers to download it and restart. Keep the file where it is and don't rename it, so updates replace it in place.

## Windows and macOS

Some releases attach Windows and macOS builds as zip files. They are not code-signed yet, so the system may warn on first launch, and they do not update themselves.
