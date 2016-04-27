# Introduction #

Egg Window Manager uses certain files for configuration. On this page you will learn what are these files and how to configure it.



# Folders used by EggWM #

  * **~/.eggwm**
> The _eggwm.conf_ file contains basic information to configure the window manager.
> The contents of this file is described later.

  * **~/.eggwm/themes**
> This folder containing the themes to decorate the windows.
> Each theme is contained within a folder with the same name, which contains the files _style.qss_, _theme.inf_
> and other resources required for the theme, such as images.



# Files used by EggWM #

  * **~/.eggwm/eggwm.conf**
> This file contains information on the subject that uses EggWM. Has the following structure:
```
[Theme] 
name = Name of the theme to decorate windows 
```
> Note that the theme should be properly placed in their folder.

  * **~/.eggwm/themes/style.qss and ~/.eggwm/themes/theme.inf**
> Theme configuration files, see the appropriate section to view its contents.



# Configuration Example #

Below is an example of how it could be structured directory tree for the proper functioning of EggWM:

  * ~/.eggwm
    * eggwm.conf
    * themes
      * theme1
        * ...
      * theme2
        * ...

If, for example, you would use the theme of windows _theme2_, _eggwm.conf_ file would look like:
```
[theme] 
name=theme2 
```