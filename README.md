# GEn
Game Engine to be used by GEMS Studio

## Dependencies

This project requires SDL2 and SDL2_Image, and is planned to use SDL2_Mixer. 

## On Linux:
On Linux, you can install the dependencies with the included package managers. This is not an all inclusive list, so if you don't find your distro here, just Google it, but these are the most common distros.
### Debian and Derivatives:
`sudo apt install gcc libsdl2-dev libsdl2-image-dev`

### Fedora and Derivatives:
`sudo dnf install SDL2 SDL2-devel SDL2_Image`

### Arch and Derivatives:
`sudo pacman -S sdl2 sdl2-image`

## On MacOS:
MacOS does not come with a package manager pre-installed, so users have 2 options: [Homebrew](https://brew.sh) or [Macports](https://macports.org).
Homebrew is recommended, but MacPorts is a suitable alternative.  
For both, you need Apple Command Line Developement tools, which you can install with `xcode-select --install` and following the steps. This give you access to the clang compiler and other critical utilities pre-included with Linux systems that are necessary for the following steps
### Homebrew(Recommended):
Open Terminal, then paste this command:  
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`  
Give it necessary permissions, and follow the steps at the end. You may have to quit and reopen terminal for it to work.
Once Homebrew has been installed, type:  
`brew install sdl2 sdl2_image`
to install the dependencies

### MacPorts(Alternative)
Go to https://www.macports.org/install.php and download the appropriate .pkg for your OS version.  
Ater installation, type  
`sudo port install libsdl2 libsdl2_image`  
to install the dependencies.


## On Windows
Unlike Linux or MacOS, Windows is not Unix-like, which makes the use of other options necessary. The 2 main options covered here will be Cygwin and WSL. Although
