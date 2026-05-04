## HandBrake-Portable

This is a portable version of [HandBrake](https://handbrake.fr) for Windows. Unlike the official version, it does not require the installation of .NET Desktop Runtime, because the .NET dependencies are included with the app.

### Usage

1. Download the correct version for your system from [Releases](https://github.com/YZgitter/HandBrake-Portable/releases). For most users that's **x86_x64**.
2. Extract the 7z archive and run HandBrake.exe to start the app.

By default, the settings are stored in the app folder, in a folder called *storage*. You can change this and make some other adjustments by modifying the *portable.ini* file.

Automatic updates are not supported. If you want to update and keep the settings and presets, the simplest way is to copy the existing *storage* folder to the new version.

### Build Process Transparency

The source code for HandBrake-Portable is the [official HandBrake repository](https://github.com/HandBrake/HandBrake). The code download, compilation, and release happen entirely on GitHub servers through automated [Action workflows](https://github.com/YZgitter/HandBrake-Portable/actions).

### Disclaimer

While HandBrake-Portable uses the HandBrake source code, the HandBrake team is not involved with this project. HandBrake-Portable is an unofficial fork, created to address a specific need.
