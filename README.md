# New Microsoft Console Color Scheme for Windows

Apply the new color scheme by Microsoft for the console (Bash on Windows, PowerShell, and CMD.EXE) in Windows 10! (since the Insider Preview build 16257)
Much more visible than the classic scheme.

See for the specification of the scheme: https://blogs.msdn.microsoft.com/commandline/2017/08/02/updating-the-windows-console-colors/

## How to Use
Double-click the `.reg` file.  The one named `*_quickedit` enables the Quick Edit Mode by default.  This mode enables you to select by drag, copy and paste by right-click.
Open the registory editor and remove any values named `ColorTable*` in `\HKEY_CURRENT_USER\Console\[Your application name]` if the scheme is not applied.

## License
I have no qualification to claim any license because I have never touched with this scheme, so these files are distributed under the public domain.  See `LICENSE`.
