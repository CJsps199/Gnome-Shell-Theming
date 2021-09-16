# Gnome-Shell-Theming
Mojave Theme for the Gnome Shell with my own extra tweaks. (Roundness)

Only WhiteSur-light-red & WhiteSur-dark-red have extra rounded off features. 
Also managed to get it to not cut off the application overview with Dash-to-Dock.
Tested on Pop-OS 21.04 with Gnome-Shell 3.38
|
|
|
|
|
|
Global Menu:

GitHub manual build works best. (Extension via Gnome-Shell-Integrations does not work).
Following instructions are easy.

Fildem Menu: https://github.com/gonzaarcr/Fildem
|
|
|
|
|
|
Gnome Shell Extensions used:

User Themes: https://extensions.gnome.org/extension/19/user-themes/   *(Enables the ability to change shell themes via Gnome-Tweaks.)*

Dock:

Floating Dock: https://extensions.gnome.org/extension/3730/floating-dock/
or 
Dash-to-Dock: https://extensions.gnome.org/extension/307/dash-to-dock/
|
|
|
|
|
|
Steps to follow: (APT & GIT)

sudo apt install gnome-tweak-tool gnome-tweaks git
cd $HOME; mkdir .themes;
git clone https://github.com/CJsps199/Gnome-Shell-Theming.git;
cd Gnome-Shell-Theming;
mv themes/* $HOME/.themes/


Or After Dowloading, Open themes folder in your File Manager and manually copy the theme colors you prefer into the .themes folder in your home directory ($HOME)


