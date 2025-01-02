# starship-themes
Customized [Starship](https://starship.rs/) Prompt Themes
## Prerequisites
1. Starship Prompt installed: `curl -fsSL https://starship.rs/install.sh | sh`

2. Requires installation of a [Nerd Font](https://github.com/ryanoasis/nerd-fonts) for icons to show up correctly.

I personally use [FiraCode Nerd Font](https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/FiraCode) and [FiraMono Nerd Font](https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/FiraMono)


Easy Direct Download links: (These may not be the latest version!)

[FiraCode Zip Download](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.3.0/FiraCode.zip)

[FiraMono Zip Download](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.3.0/FiraMono.zip)

Even easier windows Powershell nerd font installer (Note: Must be run as Administrator or they install to the User fonts directory which does not automatically show up in most programs.):


`& ([scriptblock]::Create((iwr 'https://to.loredo.me/Install-NerdFont.ps1'))) -Name fira-code, fira-mono -Scope AllUsers -Confirm:$false`

Installer info: [Nerd Font Installer](https://github.com/jpawlowski/nerd-fonts-installer-PS)


This is very much still a work in progress.  Please leave comments or create a PR if you'd like to make changes.
