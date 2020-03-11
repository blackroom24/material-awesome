## Material and Mouse driven theme for [AwesomeWM 4.3](https://awesomewm.org/)
### Original work by PapyElGringo, official development seem to have moved to [material-shell](https://github.com/PapyElGringo/material-shell)

Note: This Fork is specific for my Workstation

An almost desktop environment made with [AwesomeWM](https://awesomewm.org/) following the [Material Design guidelines](https://material.io) with a performant opiniated mouse/keyboard workflow to increase daily productivity and comfort.

[![](./theme/PapyElGringo-theme/demo.gif?raw=true)](https://www.reddit.com/r/unixporn/comments/anp51q/awesome_material_awesome_workflow/)
*[Click to view in high quality](https://www.reddit.com/r/unixporn/comments/anp51q/awesome_material_awesome_workflow/)*

| Tiled         | Panel         | Exit screen   |
|:-------------:|:-------------:|:-------------:|
|![](https://i.imgur.com/fELCtep.png)|![](https://i.imgur.com/7IthpQS.png)|![](https://i.imgur.com/rcKOLYQ.png)|



## Installation
### Note: the best transition is from gnome to material-awesome as KDE-plasma can break some indicators until plasma is purged entierly.

### 1) Get all the dependencies
- [AwesomeWM](https://awesomewm.org/) as the window manager - Arch install: awesome
- [Roboto](https://fonts.google.com/specimen/Roboto) as the **font** - Arch install: ttf-roboto
- [Rofi](https://github.com/DaveDavenport/rofi) for the app launcher - Arch install: rofi
- [Compton](https://github.com/tryone144/compton) for the compositor (blur and animations) Arch install: compton
- [xclip](https://github.com/astrand/xclip) for copying screenshots to clipboard 
- (Optional) [Materia](https://github.com/nana-4/materia-theme) as GTK theme - Arch Install: materia-theme
- (Optional) [Papirus Dark](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) as icon theme Arch Install: wget -qO- https://git.io/papirus-icon-theme-install | sh
- (Optional) [lxappearance](https://sourceforge.net/projects/lxde/files/LXAppearance/) to set up the gtk and icon theme
- (Optional) [xbacklight](https://www.x.org/archive/X11R7.5/doc/man/man1/xbacklight.1.html) for adjusting brightness on laptops (disabled by default)

### 2) Clone the configuration

```
git clone https://github.com/blackroom24/material-awesome.git ~/.config/awesome
```
### 3) Set the themes
Start **lxappearance** to active the **icon** theme and **GTK** theme
Note: for cursor theme, edit `~/.icons/default/index.theme` and `~/.config/gtk3-0/settings.ini`, for the change to also show up in applications run as root, copy the 2 files over to their respective place in `/root`.

### 4) Read the documentation
The documentation live within the source code.

The project is split in functional directories and in each of them there is a readme where you can get additionnal informations about the them.

* [Configuration](./configuration) is about all the **settings** available
* [Layout](./layout) hold the **disposition** of all the widgets
* [Module](./module) contain all the **features** available
* [Theme](./theme) hold all the **aestetic** aspects
* [Widget](./widget) contain all the **widgets** available
