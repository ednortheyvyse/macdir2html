# macdir2html

> **⚠️ This project has been superseded by MacDrive Snap and is no longer actively maintained.**
>
> For the latest version with improved functionality, ongoing development, and support, please visit:
>
> **MacDrive Snap**
> https://github.com/ednortheyvyse/MacDriveSnap

## About

macdir2html was a simple macOS application that provided a graphical interface for the command-line tool [LinuxDir2HTML](https://github.com/homeisfar/LinuxDir2HTML). It allowed users to create offline HTML snapshots of directory structures in a format similar to the Windows application [Snap2HTML](https://www.rlvision.com/snap2html/).

The application was designed to work on both Intel and Apple Silicon Macs and was tested on macOS Big Sur and Monterey.

## Looking for a Modern Replacement?

**MacDrive Snap** is the direct successor to macdir2html and provides a more modern and streamlined experience for creating searchable HTML snapshots of drives and folders on macOS.

👉 **Download or learn more:**
https://github.com/ednortheyvyse/MacDriveSnap

## Legacy Information

macdir2html relied on LinuxDir2HTML and required Xcode Command Line Tools to run the underlying Python script.

### Original Workflow

1. Open the application and select the directory you want to snapshot.
2. Choose a name for the snapshot.
3. Select the output location.
4. Confirm whether to replace an existing report if one already exists.

## LinuxDir2HTML

LinuxDir2HTML is a CLI-only clone of [Snap2HTML](https://www.rlvision.com/snap2html/) that creates offline HTML manifests of directory structures.

Key features include:

* Python 3.6+
* Symlink-safe operation (symlinks are ignored)
* Improved performance
* Cleaner invocation and usage
* Output compatible with Snap2HTML's HTML template

Project: https://github.com/homeisfar/LinuxDir2HTML

## Troubleshooting (Legacy)

If you are still using macdir2html:

* Ensure Xcode Command Line Tools are installed.
* Open Xcode at least once and accept any license agreements.
* Consider migrating to **MacDrive Snap**, which replaces this application and will receive future updates.
