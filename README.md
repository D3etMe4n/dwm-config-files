# DWM Config

### Include slstatus, dmenu, st and slock

![Alt text](/img/heroImage.png?raw=true "Title")

#### What i use:

- **Feh** as wallpapers manager
- **vifm** as file manager (include config)
- **dunst** as notifications manager (include config)
- **flameshot** for screenshots
- **brightnessctl** and **pamixer** for volume and brightness control
- **[Ubuntu Mono Nerd Font](https://archlinux.org/packages/community/any/ttf-ubuntumono-nerd/)** & **[JetBrainsMono Font](https://archlinux.org/packages/community/any/ttf-jetbrains-mono/)** - as fonts
- **picom** - as compositor(i use fork from [pijulius](https://github.com/pijulius))

#### Installation

1.  Install `git`

    ```
    sudo pacman -Sy git
    ```

2.  Copy this repository to home folder

    ```
    cd $HOME
    sudo git clone https://github.com/octagony/dwm-config-files.git
    ```

3.  Make `script.sh` executable and run it

    ```
    sudo chmod +x script.sh
    ./script.sh
    ```

#### Feh directory (for backgrounds):

```
/home/{user_name}/.wallpapers
```

#### DWM Patches:

- **alwayscenter**
- **activetagindicatorbar**
- **attachbottom**
- **autostart**
- **pertag**
- **preserveonrestart**
- **restartsig**
- **statuspadding**
- **fullgaps**
- **barpadding**
- **status2d**

#### DMenu Patches:

- **caseinsensitive**
- **lineheight**
- **fuzzyhighlight**
- **center**
- **border**
- **grid**

#### St Patches:

- **alpha**
- **scrollback**
- **scrollback-mouse**
- **glyph-wide-support**

#### Slock Patches:

- **capscolor**
- **message**
