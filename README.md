<img src="https://cdn.rawgit.com/herrbischoff/awesome-command-line-apps/master/assets/logo.svg" width="600">

> A curated list of useful command line apps, in celebration of the TUI.
>
> _“Knowledge brings fear” (Mars University Mission Statement)_

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/herrbischoff/awesome-command-line-apps.svg?branch=master)](https://travis-ci.org/herrbischoff/awesome-command-line-apps)

If you want to contribute, you are highly encouraged to do so. Please read the [contribution guidelines](contributing.md).


## Caffeinating

When you find something helpful in here, you could buy me a coffee. I spend a lot of time and effort on curating this list. Keeping me properly caffeinated accelerates things. And it would really make my day. Kindness of strangers and all that. If you can't or won't, no hard feelings. It's available completely free for a reason. Still, it would be awesome.

<a href="https://www.buymeacoffee.com/Oi5LPJ4lr" target="_blank"><img src="https://bmc-cdn.nyc3.digitaloceanspaces.com/BMC-button-images/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>


## Contents

- [\*nix/\*nux](#nixnux)
    - [Automation](#automation)
    - [Backup](#backup)
    - [Benchmarking](#benchmarking)
    - [Cloud Services](#cloud-services)
    - [Compression](#compression)
    - [Content Creation](#content-creation)
    - [Conversion](#conversion)
    - [Data Processing](#data-processing)
    - [Databases](#databases)
    - [Developer](#developer)
    - [Dotfile Management](#dotfile-management)
    - [Download Utilities](#download-utilities)
    - [Email](#email)
    - [Encryption](#encryption)
    - [Filesystem Management](#filesystem-management)
    - [FTP](#ftp)
    - [Games](#games)
    - [IRC](#irc)
    - [Media](#media)
    - [Miscellaneous](#miscellaneous)
    - [Networking](#networking)
    - [Presentation](#presentation)
    - [Productivity](#productivity)
    - [RSS](#rss)
    - [Searching](#searching)
    - [Security](#security)
    - [SSH](#ssh)
    - [System](#system)
    - [Terminal](#terminal)
    - [Text Editors](#text-editors)
    - [Version Control](#version-control)
    - [VPN](#vpn)
    - [World Wide Web](#world-wide-web)
- [BSD](#bsd)
- [Linux](#linux)
- [Mac OS X](#mac-os-x)
- [Helpers](#helpers)


## \*nix/\*nux

### Automation

- [Ansible](https://www.ansible.com) - Automate deployment, configuration, and upgrading.
- [fswatch](https://github.com/emcrisostomo/fswatch) - Cross-platform file change monitor with multiple backends.

### Backup

- [Amanda](http://www.amanda.org) - Open Source Network Backup for Linux, Windows, UNIX and OS X.
- [Attic](https://attic-backup.org) - Deduplicating backup program written in Python.
- [Bacula](http://blog.bacula.org) - Manage backups, recovery, and verification of computer data across a network of computers of different kinds.
- [BorgBackup](https://github.com/borgbackup/borg) - Significantly improved fork of Attic.
- [duply](http://duply.net) - Easily create GPG encrypted, compressed backups of any data almost anywhere.
- [mysqldump-secure](https://github.com/cytopia/mysqldump-secure) - Secure mysqldump script with encryption, compression, logging, blacklisting and Nagios monitoring integration.


### Benchmarking

- [hyperfine](https://github.com/sharkdp/hyperfine) - Benchmark commands through the command line.
- [loadtest](https://github.com/alexfernandez/loadtest) - Runs a load test on the selected HTTP URL.
- [pv](http://www.ivarch.com/programs/pv.shtml) - Terminal-based tool for monitoring the progress of data through a pipeline.
- [siege](https://www.joedog.org/siege-home/) - http load testing and benchmarking utility.

### Cloud Services

- [awless](https://github.com/wallix/awless) - A mighty command line interface for Amazon Web Services.
- [awscli](https://aws.amazon.com/cli/) - Official Amazon AWS command-line interface.
- [cadaver](http://www.webdav.org/cadaver/) - Command-line WebDAV client for Unix.

### Compression

- [archivemount](http://www.cybernoia.de/software/archivemount.html) - FUSE filesystem using libarchive to mount archives.
- [dtrx](https://github.com/moonpyk/dtrx) - Takes all the hassle out of extracting archives.

### Content Creation

- [GitBook](https://www.npmjs.com/package/gitbook) - Library and cmd utility to generate GitBooks.

### Conversion

- [binchunker](http://he.fi/bchunk/) - Converts a CD image in a ".bin / .cue" format (sometimes ".raw / .cue") to a set of .iso and .cdr tracks.
- [Echo](https://github.com/misterGF/echo) - Convert HTML tables to JSON/CSVs.
- [Pandoc](http://pandoc.org/) - A universal document converter.

### Databases

- [mycli](http://mycli.net) - Command line interface for MySQL, MariaDB, and Percona with auto-completion and syntax highlighting.
- [pgcli](http://pgcli.com) - Command line interface for Postgres with auto-completion and syntax highlighting.

### Data Processing

- [datamash](https://www.gnu.org/software/datamash/) - Perform basic numeric, textual and statistical operations on textual data files.
- [edcount](https://github.com/haroldfreeman/edcount) - Estimate distinct count of values from standard input.
- [jq](https://stedolan.github.io/jq/) - Lightweight and flexible command-line JSON processor.

### Developer

- [bat](https://github.com/astaxie/bat) - Go implement CLI, cURL-like tool for humans.
- [bcal](https://github.com/jarun/bcal) - Byte CALculator for storage conversions and calculations.
- [bitwise](https://github.com/mellowcandle/bitwise) - Terminal based interactive bit manipulator in curses.
- [caniuse-cmd](https://github.com/sgentle/caniuse-cmd) - All the power of caniuse.com with none of the GUI.
- [clog](https://github.com/kentcdodds/clog-cli) - A conventional changelog for the rest of us.
- [Cookiecutter](https://github.com/audreyr/cookiecutter) - Command-line utility that creates projects from cookiecutters (project templates).
- [Critical](https://github.com/addyosmani/critical) - Extract & Inline Critical-path CSS in HTML pages.
- [Grunt](http://gruntjs.com) - The JavaScript Task Runner.
- [gulp](http://gulpjs.com) - Automate and enhance your build workflow.
- [how2](https://github.com/santinic/how2) - stackoverflow from the terminal.
- [http-prompt](https://github.com/eliangcs/http-prompt) - Interactive command-line HTTP client featuring autocomplete and syntax highlighting, built on HTTPie and prompt_toolkit.
- [HTTPie](https://github.com/jkbrzt/httpie) - User-friendly cURL replacement featuring intuitive UI, JSON support, syntax highlighting, wget-like downloads, extensions, etc.
- [penthouse](https://github.com/pocketjoso/penthouse) - Critical Path CSS Generator.
- [Publoy](http://abhiomkar.github.io/publoy/) - Command line tool to deploy your static webapps via Dropbox.
- [Rebound](https://github.com/shobrook/rebound) - Instantly fetch Stack Overflow results when you get a compiler error.
- [saws](https://github.com/donnemartin/saws) - Supercharged AWS Command Line Interface.
- [sift](https://sift-tool.org) - Fast and powerful open source alternative to grep.
- [Yarn](https://yarnpkg.com) - Deterministic, secure alternative to npm.

### Dotfile Management

- [dotdrop](https://github.com/deadc0de6/dotdrop) - Save your dotfiles once, deploy them everywhere.
- [homeshick](https://github.com/andsens/homeshick) - Git dotfiles synchronizer written in bash.

### Download Utilities

- [aria2](http://aria2.sourceforge.net) - Lightweight multi-protocol & multi-source command-line download utility.
- [peerflix](https://github.com/mafintosh/peerflix) - Streaming torrent client for node.js.

### Email

- [abook](http://abook.sourceforge.net/) - text-based addressbook program designed to use with mutt mail client.
- [Alpine](http://alpine.x10host.com/alpine/) - Fast, easy to use email client that is suitable for both the inexperienced email user as well as for the most demanding of power users.
- [imapsync](https://github.com/imapsync/imapsync) - IMAP synchronisation, sync, copy or migration tool.
- [isync](http://isync.sourceforge.net/) - Command line application to synchronize Maildir and IMAP4 mailboxes both ways.
- [Mutt](http://www.mutt.org) - All mail clients suck. This one just sucks less.
- [Notmuch](https://notmuchmail.org) - Fast, global-search and tag-based email system.
- [OfflineIMAP](https://github.com/OfflineIMAP/offlineimap) - Two-way sync your e-mail mailboxes as a local Maildir.
- [piler](http://www.mailpiler.org/wiki/start) - Feature rich open source email archiving solution, and a viable alternative to commercial email archiving products.
- [Sup](https://github.com/sup-heliotrope/sup) - A curses threads-with-tags style email client.
- [Terjira](https://github.com/keepcosmos/terjira) - Command line power tool for Jira.

### Encryption

- [EncFS](https://vgough.github.io/encfs/) - Provides an encrypted filesystem in user-space.
- [GnuPG](https://www.gnupg.org) - Complete and free implementation of the OpenPGP standard as defined by RFC4880 (also known as PGP).

### Filesystem Management

- [FDUPES](https://github.com/adrianlopezroche/fdupes) - Identify or delete duplicate files residing within specified directories.
- [Midnight Commander](http://www.midnight-commander.org) - Feature rich visual file manager.
- [Ncdu](https://dev.yorhel.nl/ncdu) - Disk usage analyzer with an ncurses interface.
- [ranger](http://ranger.nongnu.org/) - Minimalistic visual file manager featuring curses interface with VI key bindings.
- [vifm](http://vifm.info) - ncurses based file manager with vi like keybindings/modes/options/commands/configuration, which also borrows some useful ideas from mutt.
- [zfsnap](http://www.zfsnap.org/) - Rolling ZFS snapshots the easy way.

### FTP

- [CurlFtpFS](http://curlftpfs.sourceforge.net/) - Filesystem for accessing FTP hosts based on FUSE and libcurl.
- [LFTP](http://lftp.tech/) - Sophisticated ftp/http client, and a file transfer program supporting a number of network protocols.
- [NcFTP](http://www.ncftp.com/ncftp/) - A set of free application programs implementing the File Transfer Protocol (FTP).

### Games

- [Angband](http://rephial.org/) - Angband is a free, single-player dungeon exploration game.
- [Cataclysm: Dark Days Ahead](http://en.cataclysmdda.com/) - Roguelike set in a post-apocalyptic world.
- [Curse of War](https://a-nikolaev.github.io/curseofwar/) - Fast-paced real-time action strategy game.
- [dopewars](http://dopewars.sourceforge.net) - Deal in drugs on the streets of New York, amassing a huge fortune and paying off the loan shark, while avoiding the ever-annoying police.
- [Frotz](http://frotz.sourceforge.net/) - Interpreter for Infocom games and other Z-machine games.
- [Nethack](http://nethack.org) - Single player dungeon exploration game that runs on a wide variety of computer systems.
- [vitetris](http://www.victornils.net/tetris/) - Terminal-based Tetris clone, much like the early Tetris games by Nintendo.

### IRC

- [BitlBee](https://www.bitlbee.org/main.php/news.r.html) - IRC to other chat networks gateway.
- [Irssi](https://github.com/irssi/irssi) - The client of the future.
- [WeeChat](https://weechat.org/) - WeeChat is a fast, light and extensible chat client.

### Media

- [abcde](https://abcde.einval.com/wiki/) - A Better CD Encoder.
- [AtomicParsely](http://atomicparsley.sourceforge.net/) - Lightweight command line program for reading, parsing and setting metadata into MPEG-4 files.
- [Audiogrep](https://antiboredom.github.io/audiogrep/) - Creates audio supercuts.
- [Beets](http://beets.io/) - The music geek's media organizer.
- [cmus](https://cmus.github.io) - Small, fast and powerful console music player for Unix-like operating systems.
- [FFmpeg](http://ffmpeg.org) - A complete, cross-platform solution to record, convert and stream audio and video.
- [Gifsicle](http://www.lcdf.org/gifsicle/) - Command-line tool for creating, editing, and getting information about GIF images and animations.
- [HandBrakeCLI](https://handbrake.fr) - Tool for converting video from nearly any format to a selection of modern, widely supported codecs.
- [Legofy](https://github.com/JuanPotato/Legofy) - Python program that takes a static image or gif and makes it so that it looks as if it was built out of LEGO.
- [MediaInfo](http://mediaarea.net/en/MediaInfo) - Convenient unified display of the most relevant technical and tag data for video and audio files.
- [MKVToolNix](https://mkvtoolnix.download/) - A set of tools to create, alter and inspect Matroska files under Linux, other Unices and Windows.
- [mopidy](https://www.mopidy.com/) - Self hosted MPD daemon that connects to Spotify and Soundcloud.
- [moviemon](https://github.com/iCHAIT/moviemon) - Everything about your movies within the command line.
- [mp3fs](https://khenriks.github.io/mp3fs/) - FUSE-based transcoding filesystem from FLAC to MP3.
- [mp4v2](https://code.google.com/archive/p/mp4v2) - Library and tools to provide functions to read, create, and modify mp4 files.
- [mpg123](http://mpg123.org) - Fast console MPEG Audio Player and decoder library.
- [ncmpcpp](http://rybczak.net/ncmpcpp/) - NCurses based MPD client.
- [OptiPNG](http://optipng.sourceforge.net) - PNG optimizer that recompresses image files to a smaller size, without losing any information.
- [Pngcrush](http://pmt.sourceforge.net/pngcrush/) - An optimizer for PNG (Portable Network Graphics) files.
- [Shellpic](https://github.com/larsjsol/shellpic) - Display images inline in the shell, ASCII-art is so 2013.
- [subdownloader](https://github.com/beatfreaker/subdownloader) - Downloading subtitles for one or more files is just a command away.
- [ttystudio](https://github.com/chjj/ttystudio) - A terminal-to-gif recorder minus the headaches.
- [Video Transcoding Scripts](https://github.com/donmelton/video-transcoding-scripts) - Utilities to transcode, inspect and convert videos.
- [Videogrep](https://antiboredom.github.io/videogrep/) - Automatic supercuts with python.
- [youtube-dl](http://rg3.github.io/youtube-dl/) - A small command-line program to download videos from YouTube.com and a few more sites.

### Miscellaneous

- [ansiweather](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols.
- [cointop](https://github.com/miguelmota/cointop) - Interactive cryptocurrency tracking.
- [FIGlet](http://www.figlet.org) - Program for making large letters out of ordinary text.
- [license](https://nishanths.github.io/license/) - Create LICENSEs from the command-line.
- [pockyt](https://github.com/arvindch/pockyt) - composable [Pocket](https://getpocket.com) client for the terminal.
- [wego](https://github.com/schachmat/wego/) - Weather client for the terminal.

### Networking

- [Bandwidth Monitor NG](https://www.gropp.org/?id=projects&sub=bwm-ng) - Small and simple console-based live network and disk io bandwidth monitor.
- [Blucat](http://blucat.sourceforge.net/blucat/) - netcat for Bluetooth.
- [gping](https://github.com/orf/gping) - Ping, but with a graph.
- [iftop](http://www.ex-parrot.com/pdw/iftop/) - Display bandwidth usage on an interface.
- [localtunnel](https://github.com/localtunnel/localtunnel) - Exposes your localhost to the world for easy testing and sharing.
- [mtr](http://www.bitwizard.nl/mtr/) - Combines the functionality of the 'traceroute' and 'ping' programs in a single network diagnostic tool.
- [Netcat](http://netcat.sourceforge.net) - Networking utility which reads and writes data across network connections, using the TCP/IP protocol.
- [Nethogs](https://github.com/raboof/nethogs) - Linux 'net top' tool.
- [ngrep](http://ngrep.sourceforge.net) - grep as a network packet analyzer.
- [nmap](https://nmap.org) - Network discovery and security auditing utility.
- [vnStat](http://humdi.net/vnstat/) - Console-based network traffic monitor for Linux and BSD that keeps a log of network traffic for the selected interface(s).

### Presentation

- [termui](https://github.com/gizak/termui) - Cross-platform, easy-to-compile, and fully-customizable terminal dashboard.
- [WOPR](https://github.com/yaronn/wopr) - Simple markup language for creating rich terminal reports, presentations and infographics.

### Productivity

- [doing](http://brettterpstra.com/projects/doing/) - A command line tool for keeping track of what you’re doing and tracking what you’ve done.
- [idea](https://github.com/IonicaBizau/idea) - Lightweight CLI tool and module for keeping ideas in a safe place quick and easy.
- [ledger](http://ledger-cli.org) - Powerful, double-entry accounting system that is accessed from the UNIX command-line.
- [MapSCII](https://github.com/rastapasta/mapscii) - OpenStreetMap client, renders an explorable Braille & ASCII world map.
- [pdfgrep](https://pdfgrep.org) - Command line utility to search text in PDF files.
- [pin-cushion](https://github.com/ELLIOTTCABLE/pin-cushion) - Simple, maintained CLI interface to the Pinboard.in API.
- [Remind](https://www.roaringpenguin.com/products/remind) - Sophisticated calendar and alarm program.
- [SC-IM](https://github.com/andmarti1424/sc-im) - An ncurses-based spreadsheet application.
- [Taskwarrior](http://taskwarrior.org) - Free and Open Source Software that manages your TODO list from your command line.
- [Timetrap](https://github.com/samg/timetrap) - Simple command line timetracker.
- [Watson](http://tailordev.github.io/Watson/) - Elegant time tracking with a CLI.
- [woof](http://www.home.unix-ag.org/simon/woof.html) - Simple one-off HTTP file sharing.

### RSS

- [newsbeuter](https://www.newsbeuter.org) - The Mutt of RSS feed readers.
- [rss2email](http://www.allthingsrss.com/rss2email/) - A free, open-source tool for Windows and UNIX for getting news from RSS feeds in email.

### Searching

- [fd](https://github.com/sharkdp/fd) - fd is a simple, fast and user-friendly alternative to 'find'.
- [fselect](https://github.com/jhspetersson/fselect) - 'find' replacement with SQL-like syntax.
- [ripgrep](https://github.com/BurntSushi/ripgrep) - Recursively search directories for a regex pattern extremely fast.
- [The Silver Searcher](http://geoff.greer.fm/ag/) - A blazingly fast tool for searching code.

### Security

- [Aircrack-ng](http://aircrack-ng.org) - 802.11 WEP and WPA-PSK keys cracking program that can recover keys once enough data packets have been captured.
- [Let's Encrypt](https://letsencrypt.org) - A free, automated and open Certificate Authority.

### SSH

- [autossh](http://www.harding.motd.ca/autossh/) - Automatically restart SSH sessions and tunnels.
- [sshfs](https://github.com/libfuse/sshfs) - Locally mount a remote folder via SSH.
- [storm](http://stormssh.readthedocs.io/en/master/) - A command line tool to manage your ssh connections.

### System

- [ApacheTop](http://freecode.com/projects/apachetop) - Curses-based top-like display for Apache information, including requests per second, bytes per second, most popular URLs, etc.
- [dstat](http://dag.wiee.rs/home-made/dstat/) - Versatile replacement for vmstat, iostat, netstat and ifstat.
- [htop](http://hisham.hm/htop/) - An interactive process viewer.
- [iotop](http://repo.or.cz/iotop.git) - Find out what's stressing and increasing load on your hard disks.
- [maybe](https://github.com/p-e-w/maybe) - See what a program does before deciding whether you really want it to happen.
- [netboot.xyz](https://netboot.xyz) - Boot multiple Operating System installers or utilities over the network from a single menu.
- [screenFetch](https://github.com/KittyKatt/screenFetch) - Fetches system/theme information in terminal for desktop screenshots.

### Terminal

- [asciinema](https://asciinema.org) - Free and open source solution for recording terminal sessions and sharing them on the web.
- [autojump](https://github.com/wting/autojump) - A cd command that learns - easily navigate directories from the command line.
- [bgrep](http://debugmo.de/2009/04/bgrep-a-binary-grep/) - Like grep but for binary strings.
- [byobu](http://byobu.co) - Text-based window manager and terminal multiplexer.
- [ccat](https://github.com/jingweno/ccat) - Colorizing the cat command.
- [cheat](https://github.com/chrisallenlane/cheat) - Create and view interactive cheatsheets on the command-line.
- [desk](https://github.com/jamesob/desk) - Lightweight workspace manager for the shell.
- [dit](https://github.com/vulpino/dit) - Dotfile manager that hooks into git.
- [Fisherman](https://github.com/fisherman/fisherman) - A blazing fast, modern plugin manager for fish shell.
- [fundle](https://github.com/tuvistavie/fundle) - Minimalist package manager for fish shell.
- [fzf](https://github.com/junegunn/fzf) - A general-purpose command-line fuzzy finder.
- [Marker](https://github.com/pindexis/marker) - The terminal command palette.
- [MultiTail](https://www.vanheusden.com/multitail/) - Monitor logfiles and command output in multiple windows in a terminal, colorize, filter and merge.
- [PathPicker](https://facebook.github.io/PathPicker/) - After parsing the output from a command, PathPicker presents you with a nice UI to select which files you're interested in.
- [pick](https://github.com/calleerlandsson/pick) - Fuzzy select anything.
- [SCREEN](http://www.guckes.net/Screen/) - A "window manager" for the console and terminals.
- [tmux](https://tmux.github.io) - A terminal multiplexer.
- [yank](https://github.com/mptre/yank) - Yank terminal output to clipboard.
- [z](https://github.com/rupa/z) - Tracks your most used directories, based on 'frecency'.

### Text Editors

- [Diakonos](http://diakonos.pist0s.ca) - A linux editor for the masses.
- [Emacs](https://www.gnu.org/software/emacs/) - An extensible, customizable text editor.
- [Kakoune](http://kakoune.org) - Modal editor with multiple selections and orthogonal design.
- [Neovim](https://neovim.io) - Modern version of the Vim editor with many advanced features.
- [Vim](http://www.vim.org) - Advanced text editor that seeks to provide the power of the de-facto Unix editor 'Vi', with a more complete feature set.
- [Vis](https://github.com/martanne/vis) - A highly efficient text editor.

### Version Control

- [Bazaar](http://bazaar.canonical.com/en/) - Easily manage source code on Windows, Ubuntu, GNU/Linux, and Mac OS X.
- [fossil](https://fossil-scm.org) - Simple, high-reliability, distributed SCM with integrated bug tracking, wiki, forum, and technotes.
- [Git](https://www.git-scm.com) - Git is a free and open source distributed version control system.
- [gitfs](https://www.presslabs.com/gitfs/) - Version controlled file system.
- [grv](https://github.com/rgburke/grv) - ncurses based text-mode Git repository browser.
- [Mercurial](https://www.mercurial-scm.org) - Free, distributed source control management tool.
- [tig](https://github.com/jonas/tig) - ncurses based text-mode interface for Git.

### VPN

- [OpenVPN](https://openvpn.net/index.php/open-source.html) - Full-featured open source SSL VPN solution.
- [racoon](http://ipsec-tools.sourceforge.net) - Internet Key Exchange (IKE) daemon for automatically keying IPsec connections.
- [strongSwan](https://www.strongswan.org/) - Open Source IPsec for Linux.

### World Wide Web

- [ELinks](http://elinks.or.cz) - Advanced and well-established feature-rich text mode web (HTTP/FTP/..) browser.
- [GoAccess](https://goaccess.io) - Real-time visual web log analyzer and interactive viewer.
- [googler](https://github.com/jarun/googler) - Google Search, Google Site Search, Google News from the terminal.
- [pageres](https://github.com/sindresorhus/pageres) - Capture screenshots of websites in various resolutions.


## BSD

- [ezjail](http://erdgeist.org/arts/software/ezjail/) - Jail administration framework.
- [iocage](https://iocage.io) - Convenient, Lightweight & Easy Container Management for jails.
- [pkgsrc](http://www.pkgsrc.org) - Portable package build system.
- [poudriere](https://github.com/freebsd/poudriere) - Port/Package build and test system.

## Linux

- [aptly](https://www.aptly.info/) -  Swiss army knife for Debian repository management.
- [btrfs](https://btrfs.wiki.kernel.org/index.php/Main_Page) - Copy on write (CoW) filesystem for Linux aimed at implementing advanced features while focusing on fault tolerance, repair and easy administration.
- [deborphan](http://freecode.com/projects/deborphan) - Finds packages installed on your Debian/GNU system that have no other packages depending on them.
- [IPTraf](http://iptraf.seul.org) - Console-based network statistics utility for Linux.


## Mac OS X

- [Fink](http://www.finkproject.org) - The full world of Unix Open Source software for Darwin.
- [Homebrew](http://brew.sh) - The missing package manager for OS X.
- [itunes-remote](https://github.com/mischah/itunes-remote) - Control iTunes via CLI.
- [MacPorts](https://www.macports.org) - Compile, install and upgrade either command-line, X11 or Aqua based open-source software.
- [mas](https://github.com/mas-cli/mas) - Mac App Store command line interface.
- [Night Shift Shell Utility](https://github.com/jenghis/nshift) - Simple shell utility to control the macOS Night Shift feature.
- [reminders-cli](https://github.com/keith/reminders-cli) - A simple CLI for interacting with Reminders.
- [tag](https://github.com/jdberry/tag) - Manipulate tags on files and query for files with those tags.
- [XLD](http://tmkk.undo.jp/xld/index_e.html) - Tool to decode/convert/play various 'lossless' audio files.


## Helpers

- [crontab.guru](http://crontab.guru) - Cron schedule expression editor.


## License

<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
