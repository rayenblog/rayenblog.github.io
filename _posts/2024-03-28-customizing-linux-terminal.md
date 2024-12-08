---
title: How to customize linux terminal
date: 2024-03-28 6:00:00 +0100
tags: [linux, terminal, gnome]
categories: [os]
---
[![StandWithPalestine](https://raw.githubusercontent.com/Safouene1/support-palestine-banner/master/StandWithPalestine.svg)](https://techforpalestine.org/learn-more)

### Here you'll learn how to customize your linux terminal
![Linux terminal](assets/img/linux/1.png)

**Prerequisites:**
- A terminal, 'Obviously' (I'll be using Gnome terminal as an example).
- Starship installed, if you don't have it installed, [learn how to install starship](https://starship.rs/#prerequisites).
- Shell color scripts, I'm using [Derek Taylor's configs](https://gitlab.com/dwt1/shell-color-scripts#installing-shell-color-scripts-on-fedora).
- Fortune and lolcat.

### And now let's get started:

**1. Open up your terminal and type:**
```bash
nano .bashrc
```
Then hit enter and past the following lines at the end of your .bashrc:
```bash
colorscript -r
fortune | lolcat -g ba50a1:8350ba -h 1 -v 1
```

**2. After setting up everything correctly you should get something like this after relaunching your terminal:**

![Linux terminal](assets/img/linux/2.png)

**3. Now you need to configure your starship's config file:**
- Open up a terminal window and type
```bash
git clone https://github.com/rayenghanmi/dotfiles.git
```
- Then:
```bash
cd dotfiles/
cp starship.toml ~/.config/starship.toml
```

> Keep in mind that you need to use a [Nerd font](https://www.nerdfonts.com/font-downloads) as the default on your terminal for the starship customizations to work properly.
{: .prompt-warning }

**4. Relaunch your terminal and everything should be ok:**

![Linux terminal](assets/img/linux/3.png)

If you have any ideas, don't hesitate, reach out to [me](https://facebook.com/rayen.ghanmi.23)