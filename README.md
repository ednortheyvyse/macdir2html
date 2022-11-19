# macdir2html

I put together a simple GUI for LinuxDir2HTML.

## LinuxDir2HTML
LinuxDir2HTML is a small program to help create an offline manifest of your files in an easily navigable html format. It is a CLI-only clone of [Snap2HTML](https://www.rlvision.com/snap2html/). LinuxDir2HTML is a rewrite of [DiogenesList](https://github.com/ZapperDJ/DiogenesList), making significant improvements to it:

- Python 3.6+
- Doesn't fail on symlinks (symlinks are ignored)
- More graceful invocation and sane usage
- Much, much, much faster
- Highly improved code

LinuxDir2HTML will produce essentially an identical output to Snap2HTML by using the same HTML template from that project.

