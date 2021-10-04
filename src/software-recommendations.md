# Software Recommendations
October 3, 2021

This article contains the software I use and recommend. Most of it
requires little to no elite knowledge of GNU/Linux or software in general;
not to say learning is bad...


## Operating systems

**I prefer to run UNIX-like operating systems.**

Of course for the most part I run [GNU/Linux](https://www.gnu.org/gnu/linux-and-gnu.en.html)
systems; Operating systems based off the GNU core utilities and the Linux kernel
that some people call "distros". My Linux distro of choice is
[Arch Linux](https://archlinux.org/), mostly because it has a phenomenal wiki and
a fast package manager with a large-enough pool of updated software,
all the configuration and software is kept as simple as possible making
maintenance a breeze, and the Arch User Repository (AUR) offers an excellent way to
install packages outside of the relatively small vanilla repos. The AUR makes
Arch (probably) the single distro with most software available for it.

**However this doesn't mean Arch Linux is flawless...**

For work, I use MacOS, because why the hell not. It's Unix-like without all the
crap Microsoft ships with Windows. As of recently, my love towards Apple slowly fading
away, but I can't turn a blind eye on the M1 macs; in one word: bizarre!


## (Other) Operating Systems

There is the issue of [systemd](https://www.freedesktop.org/wiki/Software/systemd/),
the innit system of choice for Arch Linux. Systemd does not follow the UNIX philosophy
of being a small, simple, one-purpose program that's easy to understand; Just like the
Linux kernel, it is large and overgrowing, and mostly monolithic. I choose to use systemd
and Arch Linux merely out of necessity and convenience; A distribution such as
[Artix](https://artixlinux.org/), Arch Linux without systemd, may ship more broken or
incomplete packages. There are also some packages I use that rely on systemd. If you are
willing to live with these slight flaws, then Artix or [Devuan](https://www.devuan.org/)
is for you.

Gnu/Linux isn't the only option when looking for a free and open-source software (FOSS)
operating systems. The BSD family of operating systems is a sold option and in
my opinion is more far superior to Linux. Yet, software availability isn't as good
as Linux, not to say that it lacks in this department. Plenty if not all popular
open source software projects on Linux are ported to the BSDs, specifically
FreeBSD; check the [FreshPorts website](https://www.freshports.org/) for an
updated list. If you are looking for a solid all around BSD operating system,
look no further than FreeBSD. It's the Arch Linux + Debian combo of the BSDs; Stable
with best software availability. For the elitists out there, OpenBSD is the way to go;
it emphasizes portability, standardization, correctness, proactive security and
integrated cryptography.

**I'm personally planning to embark on a journey to BSD paradise...**

## Terminal Emulator

Being on GNU/Linux the terminal is arguably on of the most important peices of
software. Two terminals emulators I recommend
[Alacritty](https://github.com/alacritty/alacritty) and Suckless'
[st](https://st.suckless.org/). Alacritty is a full featured terminal out of
the box with plenty of potions and customization to do in the config file. On
the other hand, st is really minimal removing all the "bloat" and unused
features found in most terminal emulators. I argue its unusable out of the box,
lacking many important features. If you decide on going the Suckless route, I
recommend trying out [Luke smith's fork](https://github.com/LukeSmithxyz/st);
basically, st with sain defaults.


## Shell

I normally have multiple shells installed on my system at once; dash and zsh.
I have zsh set to my user shell due to its convenient autocomplete plugin and memory
functions along with wonderful colorscheme compared to boring 'ol Bash.
However, I still keep Dash installed and run it occasionally to run more complex
one-liner commands.


## Text Editing

My choice of text editor is often vim; it offers a lot of complex and powerful
functionality while also being usable by anyone who can open and type in a
terminal. If you're not ready to get your feet wet with vim just yet, try
[micro](https://micro-editor.github.io/); a modern and intuitive terminal-based
text editor with syntax highlighting and mouse support, far superior to
[nano](https://www.nano-editor.org/) in my opinion. However, while I mostly use
vim to write I understand why people may wish to use a more "user friendly" option
such as a graphical text editor. For this I recommend [Notepadqq](https://notepadqq.com/s/).


## Desktop Environment

I personally prefer using the Dynamic Window Manager -
[DWM](https://dwm.suckless.org/) from Suckless as I find it to be the single
one that most easily gets out of my way and puts emphasis on what I really care
about: The actual programs I run on my machine. I also keep [xfce](https://xfce.org/)
on my system for the "traditional" desktop experience.


## Web Browser

My web browser of choice is [LibreWolf](https://librewolf-community.gitlab.io/).
This is a fork of Mozilla's [Firefox](https://www.mozilla.org/), but
with all Mozilla telemetry and bloat removed. It also includes uBlock Origin
out of the box, as a bonus. I chose to use this web browser simply because
it's the one with the least evil of them all. I combine LibreWolf with the
[Qutebrowser](https://qutebrowser.org/), one on the best "minimal" web browsers
that doesn't sacrifice functionality and performance. For the ultimate
"Suckless" experience, look no further that Suckless'
[surf](https://surf.suckless.org/).

A similar web browser is [ungoogled-chromium](https://github.com/Eloston/ungoogled-chromium);
essentially Chrome, but with all Google spyware and bloat removed. You get the
performance and wide support of Google Chrome, without any of the privacy concerns.
Then there's also the [Brave Browser](https://brave.com/), which blocks ads and
shows you more "privacy respecting" ads, paying you in their crypto, BAT. I find
it to be a bit bloated and not exactly my thing, but I don't hate it or oppose
people using it.


## Misc

Living mostly in the terminal, I found minimal yet powerful TUI replacements
for all the major GUI applications. To start with
[lf](https://github.com/gokcehan/lf) is my file manager of choice; it's
basically a [Ranger](https://ranger.github.io/) clone written in go. Being a
terminal application, it lacks the drag-and-drop functionality, which
convenient to have. You can have this functionality back by pairing lf with
[dragon](https://github.com/mwh/dragon). For any media consumption, I use
[mpv](https://mpv.io/), a minimal media player that does the job done.
It's true power is in the shear amount of customizeability and personalization.
My RSS/Atom feed reader of choice is [Newsboat](https://newsboat.org/), which
is terminal based. For those who prefer a GUI application,
[Newsflash](https://gitlab.com/news-flash/news_flash_gtk) is a
solid choice. For casual pdf viewing, I use [Zathura](https://pwmt.org/projects/zathura/),
a highly customizable and minimal pdf viewer. [SXIV](https://github.com/muennich/sxiv) as an
image viewer and [dmenu](https://tools.suckless.org/dmenu/) as an application menu.

> *configs to all the programs I mentioned in this article and more are hosted on my [GitHub](https://github.com/worthyox) page*

<small><a href="index.html">← Home</a></small>
