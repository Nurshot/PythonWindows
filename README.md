# Unofficial Python Installers for Windows

For older Python versions in the *security* maintenance status, https://www.python.org/ officially releases only the source code and no installers. But what if you want an easy way to install these versions on Windows? Here, you can obtain unofficial Windows installers for the following versions of Python.

- 3.5.5 to 3.5.10
- 3.6.9 to 3.6.15
- 3.7.10 to 3.7.16
- 3.8.11 to 3.8.16
- 3.9.14 to 3.9.16

For each Python version, this repository includes the following.

- 64-bit executable installer (e.g. python-3.5.5-amd64-full.exe)
- 32-bit executable installer (e.g. python-3.5.5-full.exe)
- 64-bit embeddable zip file (e.g. python-3.5.5-embed-amd64.zip)
- 32-bit embeddable zip file (e.g. python-3.5.5-embed-win32.zip)
- 64-bit NuGet package (e.g. python.3.5.5.nupkg)
- 32-bit NuGet package (e.g. pythonx86.3.5.5.nupkg)
- Windows help file (e.g. python355.chm)

These installers were built from the source distributions published at https://www.python.org/downloads/source/, patched to fix some bugs in the build scripts and to include debugging symbols and debug binaries. For the more technical among you, see [Notes.md](Notes.md) for further information about how I built the installers and how you may build them yourself.

## Git History

In an effort to keep the size of this repository low, the Git history will not be kept. All updates will be made via force-pushes. If you fork this repository and wish to update your fork, see https://stackoverflow.com/questions/9646167/clean-up-a-fork-and-restart-it-from-the-upstream.

## License

These files are provided under the MIT License. See [LICENSE.txt](LICENSE.txt).

## Who am I

I am Aohan Dang (https://www.linkedin.com/in/aohan-dang-536643a7/), a professional software developer and Python enthusiast.
