# Software Recommendations
September 30, 2021

This article contains the software I use and recommend; Most of it
requires little to no elite knowledge of GNU/Linux or software in general;
which doesn't mean learning is bad.

  I prefer running UNIX-like operating systems

## Operating systems

Of course for the most part I run GNU/Linux systems; Operating systems based
off the GNU core utilities and the Linux kernel that some people call "Linux
distros" for brevity. My Linux distro of choice is Arch Linux, mostly because
it offers a fast package manager with a large-enough pool of updated software,
all the configuration and software is kept as simple as possible making
maintainence a breeze, and the Arch User Repository offers an excellent way to
installs packages outside of the relatively small vanilla repos. The AUR makes
Arch (probably) the single distro with most software available for it.

  However this doesn't mean Arch Linux is flawless...

## (Other) Operating Systems

I think many more advanced Linux users wish to compile more software, for
example their kernel, from source. Compiling your software from source offers a
lot of performance advantages, and for this a distribution like Gentoo or KISS
Linux is what I'd recommend.

There is also the issue of systemd, the init system of choice for Arch Linux.
Systemd does not follow the UNIX philosophy of being a small, simple,
one-purpose program that's easy to understand; Just like the Linux kernel, it
is large and evergrowing, and mostly monolythic. I choose to use systemd and
Arch Linux merely out of necessity and convenience; A distribution such as
Artix, Arch Linux without systemd, may ship more broken or incomplete packages.
There are also some packages I use that rely on systemd. If you are willing to
live with these slight flaws, then Artix or Devuan is for you.

There are the BSDs too

## Shell

I normally have multiple shells installed on my system at once; Dash and Zsh.
I have Zsh set to my user shell due to its convenient autocomplete and memory
functions along with wonderful colorscheme compared to boring 'ol Bash.
However, I still keep Dash installed and run it ocassionaly to run more complex
one-liner commands.

## Text Editing

My choice of text editor is often vim; it offers a lot of complex and powerful
functionality while also being usable by anyone who can open and type in a
terminal. However, while I mostly use vim to write I understand why people may
wish to use a more "user friendly" option such as a graphical text editor. For
this I recommend [Notepadqq](https://notepadqq.com/s/).

## Window Management/"DE"

I personally prefer using the Dynamic Window Manager -
[DWM](https://dwm.suckless.org/) from Suckless as I find it to be the single
one that most easily gets out of my way and puts emphasis on what I really care
about: The actual programs I run on my machine. I also keep xfce on my system for
the "traditional" desktop experience.

## Web Browser

My web browser of choice is LibreWolf. This ia a fork of Mozilla's Firefox, but
with all Mozilla temeletary and bloat removed. It also includes uBlock Origin,
which to some people is a plus. I chose to use this web browser simply because
it's the most "minimalist" of them all, not counting independent web browsers
like Suckless' Surf.

A similar web browser is Ungoogled Chromium; essentially Chromw, but with
all Google spyware and bloat removed. You get the performance and wide support
of Google Chrome, without any of the privacy concerns. Then there's also the Brave
Browser, which blocks ads and shows you more "privacy respecting" ads, paying
you in their crypto, BAT. I find it to be a bit bloated and not exactly my
sorta thing, but I don't hate it or oppose people using it.
