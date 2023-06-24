# Dotfiles

Windows & Linux dotfiles for work. The configuration for each application is kept minimal as to not conflict any security mechanisms.  
  
My personal dotfiles can be found on [Codeberg](https://codeberg.org/wbehrens/dotfiles).

## Windows

The Windows installation is done using [Powershell DSC](https://learn.microsoft.com/en-us/powershell/dsc/overview?view=dsc-2.0) and [winget](https://learn.microsoft.com/en-us/windows/package-manager/winget/).

### Winget

Winget comes pre-installed with newer versions of Windows and is used to install packages using `winget import` and `winget export`. The packages installed on Windows can be found in <config/winget/packages.json>.

## Linux

## TODO

- Windows subsystem for Linux
- Powertoys
- Firefox
- Switch to Fleet
- Configure windows sandbox
- Configure docker desktop
- windows openssh
