# macdir2html

macdir2html is a small app that adds user prompts to the command-line based tool [LinuxDir2HTML](https://github.com/homeisfar/LinuxDir2HTML). LinuxDir2HTML is a Mac version of the Windows program [Snap2HTML](https://www.rlvision.com/snap2html/). macdir2html currently requires xcode to run LinuxDir2HTML's python script but will prompt you if you do not have it. 

It works on both M1 and Intel chips and has been tested on Big Sur and Monterey.

# How to
1. Open the App and it will want you to select the directory you want to snapshot.
2. Then choose the name of the snapshot. By default it will name it the directory name and _Report
3. It will then want you to select the output location of the snapshot.
4. It will warn you if the snapshot report already exists, you can either cancel or replace it.

## LinuxDir2HTML
LinuxDir2HTML is a small program to help create an offline manifest of your files in an easily navigable html format. It is a CLI-only clone of [Snap2HTML](https://www.rlvision.com/snap2html/). LinuxDir2HTML is a rewrite of [DiogenesList](https://github.com/ZapperDJ/DiogenesList), making significant improvements to it:

- Python 3.6+
- Doesn't fail on symlinks (symlinks are ignored)
- More graceful invocation and sane usage
- Much, much, much faster
- Highly improved code

LinuxDir2HTML will produce essentially an identical output to Snap2HTML by using the same HTML template from that project.

## Troubleshooting
- Make sure you have the latest version of xcode installed.
- Try opening up xcode and accepting the T&C's.
