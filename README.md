# VillagePay WindowsApp
This public GitHub repository is used to store the releases of the VillagePay WindowsApp. The repository is intended for use by the program to check for new versions and update itself to the latest version automatically.

## Instructions for creating a new release
When creating a new release, make sure to tag it with a version number in the format of three digits separated by dots. The name of the release can be anything you want. The release should be marked as the latest version and should include a Setup.exe file, which is the installer for the application.

It's important to note that each new release should have a higher version number than the previous one.

## Usage
To use the VillagePay WindowsApp, download the latest release from the Releases section of this repository. Run the Setup.exe file to install the application on your Windows machine.

Once installed, the application will automatically check for new releases and download if a new version is available.

## Windows 7

Before installation several packages are required to be downloaded installed:
1. .NET Framework 4.5.2 - https://www.microsoft.com/en-US/download/details.aspx?id=42642
2. .NET Desktop Runtime 5.0.17 - https://dotnet.microsoft.com/en-us/download/dotnet/5.0
3. Visual C++ Redistributable - https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170

If you have issues with certificates when trying to log in - download and install ISRG Root X1 certificate with .der extension.
URL: https://letsencrypt.org/certificates/
