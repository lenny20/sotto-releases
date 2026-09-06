# SottoWrite for desktop

Installers for the SottoWrite screenplay editor for Mac, Windwos and Linux.

These are early builds and are not yet signed, so each system shows a warning the first time you try to open SottoWrite. The steps for getting past this warning are given below.

SottoWrite Desktop is still in beta. Please report any bugs to hello@sottowrite.com

## macOS

**Which file:** Apple silicon Macs (M1, M2, M3, M4 and later) take
`SottoWrite-<version>-mac-arm64.dmg`. Intel Macs take
`SottoWrite-<version>-mac-x64.dmg`. Not sure which you have? Apple menu ▸
About This Mac: "Chip: Apple M…" means arm64, "Processor: Intel…" means x64.

**Install:** open the `.dmg` and drag SottoWrite into Applications. Eject
the disk image.

**First launch:** macOS says "Apple could not verify SottoWrite is free of
malware". Click Done. Open System Settings ▸ Privacy & Security, scroll to
the Security section, and click "Open Anyway" beside the SottoWrite line.
Confirm once more and it opens. You only do this the first time.

New versions: the app tells you when one is available and opens this page.
Download the new `.dmg` and drag it over the old copy.

## Windows

**Which file:** `SottoWrite-<version>-win-x64.exe`.

**Install:** run the `.exe`. Windows shows a blue "Windows protected your
PC" screen. Click "More info", then "Run anyway". The installer lets you
choose the folder and puts a shortcut on the desktop.

New versions download in the background. When one is ready the app offers
"Restart now"; if you choose "Later", it installs the next time you quit.

## Linux

**Which file:** `SottoWrite-<version>-linux-x86_64.AppImage` is the one to
pick. It runs anywhere and updates itself. The
`SottoWrite-<version>-linux-amd64.deb` is for Debian and Ubuntu users who
prefer a package; it does not update itself, so you come back here for new
versions.

**AppImage:** make it executable and run it. On Ubuntu 24.04 and newer, run **sudo apt install libfuse2t64** first to allow AppImage to run. Then, in a terminal, in the folder
you downloaded to:

    chmod +x SottoWrite-*.AppImage
    ./SottoWrite-*.AppImage

Or right-click the file, Properties, tick "Allow executing as program", and
double-click it. Keep the file somewhere permanent, because that file is
the app.

**.deb:** double-click it in your file manager, or in a terminal:

    sudo apt install ./SottoWrite-*.deb

SottoWrite then appears in your application menu.

## Your screenplays

SottoWrite Desktop saves each script as a `.sotto` file wherever you choose. Each screenplay file
keeps its own version history beside it. Updating or reinstalling the app
never touches your files.
