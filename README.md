## HandBrake-Portable

This is a portable version of [HandBrake](https://handbrake.fr) for Windows. It doesn't have to be installed and it *doesn't* require the installation of the .NET Desktop Runtime, as all the dependencies are included.

### Usage

1. Download the correct version for your system from [Releases](https://github.com/YZgitter/HandBrake-Portable/releases). For most users that's **x86_x64**.
2. Extract the downloaded archive and run HandBrake.exe.

By default, the settings are stored in the app folder, in a folder called *storage*. You can change this and make some other adjustments by modifying the *portable.ini* file. Automatic updates are not supported. If you want to update and keep the settings, the simplest way is to get the new version and copy the *storage* folder from the previous version.

### Build Process Transparency

The source code for HandBrake-Portable is the [official HandBrake repository](https://github.com/HandBrake/HandBrake). The code download, compilation, and release are performed through automated [Action workflows](https://github.com/YZgitter/HandBrake-Portable/actions).
