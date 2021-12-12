- winget https://github.com/microsoft/winget-cli
- Windows Terminal: `winget install Microsoft.WindowsTerminal`

## Windows tools & softwares
- Vlc - Video player `winget install VideoLAN.VLC`
- 7zip - File zip & extract `winget install 7zip.7zip`
- Obs - screen recorder `winget install "OBS Studio"`
- Powertoys - utilities for Windows `winget install Microsoft.PowerToys`

## Development
 - Git - scm: `winget install Git.Git`
 - Fork - git gui client: `winget install Fork.Fork`
 - VsCode: `winget install Microsoft.VisualStudioCode`
 - Visual Studio: `winget install Microsoft.VisualStudio.2022.Community`
 - Yarn - package manager: `winget install Yarn.Yarn`
 - Linqpad: `winget search linqpad`
 - Postman: `winget install Postman.Postman`
 - Nvm for windows: `winget search --name "NVM for Windows"`
 - Sql server toolkit: `winget search SQLServer`
 
 ## Vscode extensions
 - [vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
 - [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
 - [angular2-switcher](https://marketplace.visualstudio.com/items?itemName=infinity1207.angular2-switcher)
 - [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
 
 ## Visual Studio extensions
 - [Git Diff Margin](https://marketplace.visualstudio.com/items?itemName=LaurentKempe.GitDiffMargin)
 - [VsVim 2022](https://marketplace.visualstudio.com/items?itemName=JaredParMSFT.VsVim2022Preview)
 - [Match margin](https://marketplace.visualstudio.com/items?itemName=VisualStudioPlatformTeam.MatchMargin2022)
 - [Code Cleanup On Save](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.CodeCleanupOnSave)
 - [Format document on Save](https://marketplace.visualstudio.com/items?itemName=mynkow.FormatdocumentonSave&ssr=false#overview)
 - [Visual Studio Theme Pack](https://marketplace.visualstudio.com/items?itemName=idex.vsthemepack)
 
 ## Communication
 - Slack: `winget search Slack`
 - Teams: `winget install Microsoft.Teams`
 
 ## Configurations
 
 **.gitconfig**
 ```.gitconfig
[alias]
  pm = pull origin master
  s = status -s
  p = pull
  ps = push
  b = branch
  curr = branch --show-current
  c = checkout
  cm = commit -m
  ca = commit -am
  ru = remote update
  asc = branch --sort=-committerdate
```

**_vimrc**
```
syntax on
set ignorecase
set smartindent
:imap jj <Esc>
```

**_vsvimrc**
```
map gk :vsc Edit.PreviousMethod
map gj :vsc Edit.NextMethod
map gr :vsc Edit.FindAllReferences
map gD :vsc Edit.GoToImplementation
:imap jj <Esc>
```
