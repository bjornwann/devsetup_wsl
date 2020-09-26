### Terminal Styling Setup WSL Ubuntu VS Code

## Installation Ubuntu
- zsh https://linuxhint.com/install_zsh_shell_ubuntu_1804/
- skip fonts and install them on windows instead

## Windows Powershell
- In powershell: 
git clone https://github.com/powerline/fonts.git --depth=1cd fonts.\install.ps1
this will take a while to install all fonts. you can delete the folder after.

## Windows Terminal
- set font in settings in windows terminal in the Ubuntu section
  {
        "guid": "{2c4de342-38b7-51cf-b940-2309a097f518}",
        "hidden": false,
        "name": "Ubuntu",
        "source": "Windows.Terminal.Wsl",
        "startingDirectory": "//wsl$/Ubuntu/home/username/",
        "fontFace": "Font Face Powerline"
      }
- replace the line "fontFace": "Font Face Powerline" with the font of your choice

## VS code
- settings
- user
- features
- integrated terminal
- font-family: pick your powerline font