## HandBrake-Portable

This is a portable version of [HandBrake](https://github.com/HandBrake/HandBrake) for Windows. It doesn't need to be installed and it *doesn't* require the installation of the .NET Desktop Runtime, as the .NET dependencies are included with the app.

### Usage

1. Download the correct version for your system from [Releases](https://github.com/YZgitter/HandBrake-Portable/releases). For most users that's **x86_x64**.
2. Extract the downloaded archive and run HandBrake.exe.

By default, the settings are stored within the app folder. You can change this and make some other adjustments by modifying the *portable.ini* file.

If you need help using HandBrake, visit the [official website](https://handbrake.fr), which has links to the documentation and community support.
HandBrake-Portable should work the same as the version provided by the HandBrake team. But if you encounter a problem, you can report it by opening an issue.

### Build Process Transparency

The code for HandBrake-Portable is sourced from the official HandBrake repository. It was downloaded, compiled, and released entirely by Github Actions. You can review the whole process by examining the .yml files.
