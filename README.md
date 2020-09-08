<img src="https://cdn.rawgit.com/herrbischoff/awesome-command-line-apps/master/assets/logo.svg" width="600">

> A curated list of useful command line apps, in celebration of the TUI.
>
> _“Knowledge brings fear” (Mars University Mission Statement)_

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

If you want to contribute, you are highly encouraged to do so. Please read the [contribution guidelines](contributing.md).


## Caffeinating

When you find something helpful in here, you could buy me a coffee. I spend a lot of time and effort on curating this list. Keeping me properly caffeinated accelerates things. And it would really make my day. Kindness of strangers and all that. If you can't or won't, no hard feelings. It's available completely free for a reason. Still, it would be awesome.

<https://github.com/sponsors/herrbischoff>


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
- [Restic](https://restic.net) - Fast, secure, efficient backup program.


### Benchmarking

- [hyperfine](https://github.com/sharkdp/hyperfine) - Benchmark commands through the command line.
- [loadtest](https://github.com/alexfernandez/loadtest) - Runs a load test on the selected HTTP URL.
- [pv](http://www.ivarch.com/programs/pv.shtml) - Monitor the progress of data through a pipeline.
- [siege](https://www.joedog.org/siege-home/) - HTTP load testing and benchmarking utility.

### Cloud Services

- [awless](https://github.com/wallix/awless) - Mighty command-line interface for Amazon Web Services.
- [awscli](https://aws.amazon.com/cli/) - Official Amazon AWS command-line interface.
- [cadaver](http://www.webdav.org/cadaver/) - WebDAV client for Unix.
- [google-drive-upload](https://github.com/labbots/google-drive-upload) - Upload and sync files to Google Drive.

### Compression

- [archivemount](http://www.cybernoia.de/software/archivemount.html) - FUSE filesystem using libarchive to mount archives.
- [dtrx](https://github.com/moonpyk/dtrx) - Takes all the hassle out of extracting archives.

### Content Creation

- [GitBook](https://www.npmjs.com/package/gitbook) - Library and cmd utility to generate GitBooks.

### Conversion

- [binchunker](http://he.fi/bchunk/) - Converts a CD image in a ".bin/.cue" format (sometimes ".raw/.cue") to a set of .iso and .cdr tracks.
- [Echo](https://github.com/misterGF/echo) - Convert HTML tables to JSON/CSVs.
- [Pandoc](http://pandoc.org/) - Universal document converter.

### Databases

- [mycli](http://mycli.net) - Command-line interface for MySQL, MariaDB, and Percona with auto-completion and syntax highlighting.
- [pgcli](http://pgcli.com) - Command-line interface for Postgres with auto-completion and syntax highlighting.
- [usql](https://github.com/xo/usql) - Universal command-line interface for SQL databases.

### Data Processing

- [datamash](https://www.gnu.org/software/datamash/) - Perform basic numeric, textual and statistical operations on textual data files.
- [edcount](https://github.com/haroldfreeman/edcount) - Estimate distinct count of values from standard input.
- [jq](https://stedolan.github.io/jq/) - Lightweight and flexible JSON processor.

### Developer

- [bat](https://github.com/astaxie/bat) - Go implement CLI, cURL-like tool for humans.
- [bcal](https://github.com/jarun/bcal) - Byte calculator for storage conversions and calculations.
- [bitwise](https://github.com/mellowcandle/bitwise) - Interactive bit manipulator in curses.
- [caniuse-cmd](https://github.com/sgentle/caniuse-cmd) - All the power of caniuse.com with none of the GUI.
- [clog](https://github.com/kentcdodds/clog-cli) - Conventional changelog for the rest of us.
- [Cookiecutter](https://github.com/audreyr/cookiecutter) - Creates projects from cookiecutters (project templates).
- [Critical](https://github.com/addyosmani/critical) - Extract & inline critical-path CSS in HTML pages.
- [grex](https://github.com/pemistahl/grex) - Generate regular expressions from user-provided test cases.
- [Grunt](http://gruntjs.com) - The JavaScript Task Runner.
- [gulp](http://gulpjs.com) - Automate and enhance your build workflow.
- [how2](https://github.com/santinic/how2) - Stack Overflow from the terminal.
- [http-prompt](https://github.com/eliangcs/http-prompt) - Interactive HTTP client featuring autocomplete and syntax highlighting, built on HTTPie and prompt_toolkit.
- [HTTPie](https://github.com/jkbrzt/httpie) - User-friendly cURL replacement featuring intuitive UI, JSON support, syntax highlighting, wget-like downloads, extensions, etc.
- [penthouse](https://github.com/pocketjoso/penthouse) - Critical path CSS generator.
- [Publoy](http://abhiomkar.github.io/publoy/) - Command line tool to deploy your static web apps via Dropbox.
- [Rebound](https://github.com/shobrook/rebound) - Instantly fetch Stack Overflow results when you get a compiler error.
- [saws](https://github.com/donnemartin/saws) - Supercharged AWS command-line interface.
- [shellcheck](https://github.com/koalaman/shellcheck) - Static analysis tool for shell scripts.
- [sift](https://sift-tool.org) - Fast and powerful open source alternative to grep.
- [tokei](https://github.com/XAMPPRocky/tokei) - Quickly display statistics about your code like number of files, total lines, comments and blanks, grouped by language.
- [Yarn](https://yarnpkg.com) - Deterministic, secure alternative to npm.

### Dotfile Management

- [dotdrop](https://github.com/deadc0de6/dotdrop) - Save your dotfiles once, deploy them everywhere.
- [homeshick](https://github.com/andsens/homeshick) - Git dotfiles synchronizer written in Bash.

### Download Utilities

- [aria2](http://aria2.sourceforge.net) - Lightweight multi-protocol & multi-source command-line download utility.
- [peerflix](https://github.com/mafintosh/peerflix) - Streaming torrent client for node.js.

### Email

- [abook](http://abook.sourceforge.net/) - Text-based address book program designed to use with mutt mail client.
- [Alpine](http://alpine.x10host.com/alpine/) - Fast, easy to use email client.
- [imapsync](https://github.com/imapsync/imapsync) - IMAP synchronisation, sync, copy or migration tool.
- [isync](http://isync.sourceforge.net/) - Synchronize Maildir and IMAP4 mailboxes both ways.
- [Mutt](http://www.mutt.org) - All mail clients suck, this one just sucks less.
- [Notmuch](https://notmuchmail.org) - Fast, global-search and tag-based email system.
- [OfflineIMAP](https://github.com/OfflineIMAP/offlineimap) - Two-way sync your e-mail mailboxes as a local Maildir.
- [piler](http://www.mailpiler.org/wiki/start) - Email archiving solution, a viable alternative to commercial products.
- [Sup](https://github.com/sup-heliotrope/sup) - Curses threads-with-tags style email client.
- [Terjira](https://github.com/keepcosmos/terjira) - Command line power tool for Jira.

### Encryption

- [EncFS](https://vgough.github.io/encfs/) - Provides an encrypted filesystem in user-space.
- [GnuPG](https://www.gnupg.org) - Complete and free implementation of the OpenPGP standard as defined by RFC4880 (also known as PGP).

### Filesystem Management

- [dust](https://github.com/bootandy/dust) - More intuitive version of 'du'.
- [FDUPES](https://github.com/adrianlopezroche/fdupes) - Identify or delete duplicate files residing within specified directories.
- [Midnight Commander](http://www.midnight-commander.org) - Feature-rich visual file manager.
- [Ncdu](https://dev.yorhel.nl/ncdu) - Disk usage analyzer with an ncurses interface.
- [ranger](http://ranger.nongnu.org/) - Minimalistic visual file manager featuring curses interface with vi key bindings.
- [vifm](http://vifm.info) - ncurses based file manager with vi like keybindings/modes/options/commands/configuration, which also borrows some useful ideas from mutt.
- [zfsnap](http://www.zfsnap.org/) - Rolling ZFS snapshots the easy way.

### FTP

- [CurlFtpFS](http://curlftpfs.sourceforge.net/) - Filesystem for accessing FTP hosts based on FUSE and libcurl.
- [LFTP](http://lftp.tech/) - Sophisticated ftp/http client, and a file transfer program supporting a number of network protocols.
- [NcFTP](http://www.ncftp.com/ncftp/) - Set of free application programs implementing the File Transfer Protocol (FTP).

### Games

- [Angband](http://rephial.org/) - Free, single-player dungeon exploration game.
- [Cataclysm: Dark Days Ahead](https://cataclysmdda.org/) - Roguelike set in a post-apocalyptic world.
- [Curse of War](https://a-nikolaev.github.io/curseofwar/) - Fast-paced real-time action strategy game.
- [dopewars](http://dopewars.sourceforge.net) - Deal in drugs on the streets of New York, amassing a huge fortune and paying off the loan shark, while avoiding the ever-annoying police.
- [Frotz](http://frotz.sourceforge.net/) - Interpreter for Infocom games and other Z-machine games.
- [Nethack](http://nethack.org) - Single player dungeon exploration game that runs on a wide variety of computer systems.
- [vitetris](http://www.victornils.net/tetris/) - Tetris clone.

### IRC

- [BitlBee](https://www.bitlbee.org/main.php/news.r.html) - IRC to other chat networks gateway.
- [Irssi](https://github.com/irssi/irssi) - The client of the future.
- [WeeChat](https://weechat.org/) - Fast, light and extensible chat client.

### Media

- [abcde](https://abcde.einval.com/wiki/) - A Better CD Encoder.
- [AtomicParsely](http://atomicparsley.sourceforge.net/) - Reads, parses and sets metadata into MPEG-4 files.
- [Audiogrep](https://antiboredom.github.io/audiogrep/) - Creates audio supercuts.
- [Beets](http://beets.io/) - The music geek's media organizer.
- [cmus](https://cmus.github.io) - Small, fast and powerful console music player for Unix-like operating systems.
- [FFmpeg](http://ffmpeg.org) - Records, converts and streams audio and video.
- [Gifsicle](http://www.lcdf.org/gifsicle/) - Creates, edits, and gets information about GIF images and animations.
- [HandBrakeCLI](https://handbrake.fr) - Converts video from nearly any format to a selection of modern, widely supported codecs.
- [Legofy](https://github.com/JuanPotato/Legofy) - Makes images look like they were built out of Lego.
- [MediaInfo](http://mediaarea.net/en/MediaInfo) - Convenient unified display of the most relevant technical and tag data for video and audio files.
- [MKVToolNix](https://mkvtoolnix.download/) - Set of tools to create, alter and inspect Matroska files under Linux, other Unices and Windows.
- [mopidy](https://www.mopidy.com/) - Self-hosted MPD daemon that connects to Spotify and Soundcloud.
- [moviemon](https://github.com/iCHAIT/moviemon) - Everything about your movies within the command-line.
- [mp3fs](https://khenriks.github.io/mp3fs/) - FUSE-based transcoding filesystem from FLAC to MP3.
- [mp4v2](https://code.google.com/archive/p/mp4v2) - Library and tools to provide functions to read, create, and modify mp4 files.
- [mpg123](http://mpg123.org) - Fast console MPEG Audio Player and decoder library.
- [ncmpcpp](http://rybczak.net/ncmpcpp/) - NCurses based MPD client.
- [OptiPNG](http://optipng.sourceforge.net) - PNG optimizer that recompresses image files to a smaller size, without losing any information.
- [Pngcrush](http://pmt.sourceforge.net/pngcrush/) - Optimizer for PNG (Portable Network Graphics) files.
- [Shellpic](https://github.com/larsjsol/shellpic) - Display images inline in the shell, ASCII-art is so 2013.
- [subdownloader](https://github.com/beatfreaker/subdownloader) - Downloading subtitles for one or more files is just a command away.
- [ttystudio](https://github.com/chjj/ttystudio) - Terminal-to-gif recorder minus the headaches.
- [Video Transcoding Scripts](https://github.com/donmelton/video_transcoding) - Utilities to transcode, inspect and convert videos.
- [Videogrep](https://antiboredom.github.io/videogrep/) - Automatic supercuts with Python.
- [youtube-dl](http://rg3.github.io/youtube-dl/) - Download videos from YouTube.com and a few more sites.

### Miscellaneous

- [ansiweather](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols.
- [cointop](https://github.com/miguelmota/cointop) - Interactive cryptocurrency tracking.
- [FIGlet](http://www.figlet.org) - Program for making large letters out of ordinary text.
- [license](https://nishanths.github.io/license/) - Create LICENSEs from the command-line.
- [pockyt](https://github.com/arvindch/pockyt) - Composable Pocket client for the terminal.
- [wego](https://github.com/schachmat/wego/) - Weather client for the terminal.

### Networking

- [bandwhich](https://github.com/imsnif/bandwhich) - Displays current network utilization by process, connection and remote IP or hostname.
- [Bandwidth Monitor NG](https://www.gropp.org/?id=projects&sub=bwm-ng) - Small and simple live network and disk IO bandwidth monitor.
- [Blucat](http://blucat.sourceforge.net/blucat/) - netcat for Bluetooth.
- [gping](https://github.com/orf/gping) - Ping, but with a graph.
- [httping](https://www.vanheusden.com/httping/) - Like 'ping' but for http requests.
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

- [doing](http://brettterpstra.com/projects/doing/) - Keeping track of what you’re doing and tracking what you’ve done.
- [idea](https://github.com/IonicaBizau/idea) - Lightweight CLI tool and module for keeping ideas in a safe place quick and easy.
- [ledger](http://ledger-cli.org) - Powerful, double-entry accounting system that is accessed from the UNIX command-line.
- [MapSCII](https://github.com/rastapasta/mapscii) - OpenStreetMap client, renders an explorable Braille & ASCII world map.
- [pdfgrep](https://pdfgrep.org) - Command-line utility to search text in PDF files.
- [pin-cushion](https://github.com/ELLIOTTCABLE/pin-cushion) - Simple, maintained command-line interface to the Pinboard.in API.
- [Remind](https://www.roaringpenguin.com/products/remind) - Sophisticated calendar and alarm program.
- [SC-IM](https://github.com/andmarti1424/sc-im) - ncurses-based spreadsheet application.
- [Taskwarrior](http://taskwarrior.org) - Manage your Todo list.
- [Timetrap](https://github.com/samg/timetrap) - Simple timetracker.
- [Watson](http://tailordev.github.io/Watson/) - Elegant time tracking.
- [woof](http://www.home.unix-ag.org/simon/woof.html) - Simple one-off HTTP file sharing.

### RSS

- [newsbeuter](https://www.newsbeuter.org/) - The Mutt of RSS feed readers.
- [rss2email](http://www.allthingsrss.com/rss2email/) - Get news from RSS feeds in email.
- [rsstail](https://www.vanheusden.com/rsstail/) - Monitors a single RSS feed and emits only new entries.

### Searching

- [fd](https://github.com/sharkdp/fd) - fd is a simple, fast and user-friendly alternative to 'find'.
- [fselect](https://github.com/jhspetersson/fselect) - 'find' replacement with SQL-like syntax.
- [fzf](https://github.com/junegunn/fzf) - A general-purpose fuzzy finder.
- [ripgrep](https://github.com/BurntSushi/ripgrep) - Recursively search directories for a regex pattern extremely fast.
- [sd](https://github.com/chmln/sd) - Intuitive find-and-replace alternative to 'sed'.
- [The Silver Searcher](http://geoff.greer.fm/ag/) - Blazingly fast tool for searching code.

### Security

- [acme.sh](https://github.com/Neilpang/acme.sh) - Pure Unix shell script implementing ACME client protocol, for Let's Encrypt.
- [Aircrack-ng](http://aircrack-ng.org) - 802.11 WEP and WPA-PSK keys cracking program that can recover keys once enough data packets have been captured.
- [Let's Encrypt](https://letsencrypt.org) - Free, automated and open Certificate Authority.
- [pass](https://www.passwordstore.org) - The standard Unix password manager.

### SSH

- [autossh](https://www.harding.motd.ca/autossh/ ) - Automatically restart SSH sessions and tunnels.
- [sshfs](https://github.com/libfuse/sshfs) - Locally mount a remote folder via SSH.
- [storm](http://stormssh.readthedocs.io/en/master/) - Manage your SSH connections.

### System

- [ApacheTop](http://freecode.com/projects/apachetop) - Curses-based top-like display for Apache information, including requests per second, bytes per second, most popular URLs, etc.
- [bottom](https://github.com/ClementTsang/bottom) - Graphical process/system monitor with a customizable interface and multitude of features.
- [dstat](http://dag.wiee.rs/home-made/dstat/) - Versatile replacement for vmstat, iostat, netstat and ifstat.
- [htop](http://hisham.hm/htop/) - Interactive process viewer.
- [iotop](http://repo.or.cz/iotop.git) - Find out what's stressing and increasing load on your hard disks.
- [maybe](https://github.com/p-e-w/maybe) - See what a program does before deciding whether you really want it to happen.
- [netboot.xyz](https://netboot.xyz) - Boot multiple Operating System installers or utilities over the network from a single menu.
- [procs](https://github.com/dalance/procs) - Modern replacement for 'ps'.
- [screenFetch](https://github.com/KittyKatt/screenFetch) - Fetches system/theme information in terminal for desktop screenshots.

### Terminal

- [asciinema](https://asciinema.org) - Record terminal sessions and share them on the web.
- [autojump](https://github.com/wting/autojump) - 'cd' command that learns - easily navigate directories from the command line.
- [bat](https://github.com/sharkdp/bat) - 'cat' clone with syntax highlighting and Git integration.
- [bgrep](http://debugmo.de/2009/04/bgrep-a-binary-grep/) - Like grep but for binary strings.
- [byobu](http://byobu.co) - Text-based window manager and terminal multiplexer.
- [ccat](https://github.com/jingweno/ccat) - Colorizing the 'cat' command.
- [cheat](https://github.com/chrisallenlane/cheat) - Create and view interactive cheatsheets.
- [desk](https://github.com/jamesob/desk) - Lightweight workspace manager for the shell.
- [dit](https://github.com/vulpino/dit) - Dotfile manager that hooks into Git.
- [exa](https://github.com/ogham/exa) - Modern version of 'ls'.
- [Fisher](https://github.com/jorgebucaran/fisher) - Package manager for the fish shell.
- [fundle](https://github.com/tuvistavie/fundle) - Minimalist package manager for dish shell.
- [Marker](https://github.com/pindexis/marker) - The terminal command palette.
- [MultiTail](https://www.vanheusden.com/multitail/) - Monitor logfiles and command output in multiple windows in a terminal, colorize, filter and merge.
- [PathPicker](https://facebook.github.io/PathPicker/) - After parsing the output from a command, PathPicker presents you with a nice UI to select which files you're interested in.
- [pick](https://github.com/calleerlandsson/pick) - Fuzzy select anything.
- [SCREEN](http://www.guckes.net/Screen/) - "Window manager" for the console and terminals.
- [Starship](https://starship.rs) - Minimal, blazing-fast and infinitely customizable prompt for any shell.
- [tealdeer](https://github.com/dbrgn/tealdeer) - Very fast implementation of 'tldr'.
- [tmux](https://tmux.github.io) - Terminal multiplexer.
- [yank](https://github.com/mptre/yank) - Yank terminal output to clipboard.
- [z](https://github.com/rupa/z) - Tracks your most used directories, based on "frecency".
- [zoxide](https://github.com/ajeetdsouza/zoxide) - Similar to 'z' but a standalone binary, therefore shell-independent.

### Text Editors

- [Diakonos](https://github.com/Pistos/diakonos) - Linux editor for the masses.
- [Emacs](https://www.gnu.org/software/emacs/) - Extensible, customizable text editor.
- [Kakoune](http://kakoune.org) - Modal editor with multiple selections and orthogonal design.
- [Micro](https://github.com/zyedidia/micro) - Modern and intuitive text editor.
- [Neovim](https://neovim.io) - Modern version of the Vim editor with many advanced features.
- [Vim](http://www.vim.org) - Advanced text editor that seeks to provide the power of the de-facto Unix editor 'Vi', with a more complete feature set.
- [Vis](https://github.com/martanne/vis) - Highly efficient text editor.

### Version Control

- [Bazaar](http://bazaar.canonical.com/en/) - Easily manage source code on Windows, Ubuntu, GNU/Linux, and Mac OS X.
- [fossil](https://fossil-scm.org) - Simple, high-reliability, distributed SCM with integrated bug tracking, wiki, forum, and technotes.
- [Git](https://www.git-scm.com) - Git is a free and open source distributed version control system.
- [gitfs](https://www.presslabs.com/gitfs/) - Version controlled file system.
- [grv](https://github.com/rgburke/grv) - ncurses based text-mode Git repository browser.
- [Mercurial](https://www.mercurial-scm.org) - Free, distributed source control management tool.
- [tig](https://github.com/jonas/tig) - ncurses based text-mode interface for Git.

### VPN

- [OpenVPN](https://github.com/OpenVPN/openvpn) - Full-featured open source SSL VPN solution.
- [racoon](http://ipsec-tools.sourceforge.net) - Internet Key Exchange (IKE) daemon for automatically keying IPsec connections.
- [strongSwan](https://www.strongswan.org/) - Open Source IPsec for Linux.

### World Wide Web

- [ELinks](http://elinks.or.cz) - Advanced and well-established feature-rich text mode web (HTTP/FTP/..) browser.
- [GoAccess](https://goaccess.io) - Real-time visual web log analyzer and interactive viewer.
- [googler](https://github.com/jarun/googler) - Google Search, Google Site Search, Google News from the terminal.
- [pageres](https://github.com/sindresorhus/pageres) - Capture screenshots of websites in various resolutions.


## BSD

- [ezjail](http://erdgeist.org/arts/software/ezjail/) - Jail administration framework.
- [iocage](https://iocage.io) - Convenient, lightweight & easy container management for BSD jails.
- [pkgsrc](http://www.pkgsrc.org) - Portable package build system.
- [poudriere](https://github.com/freebsd/poudriere) - Port/package build and test system.

## Linux

- [aptly](https://www.aptly.info/) -  Swiss army knife for Debian repository management.
- [btrfs](https://btrfs.wiki.kernel.org/index.php/Main_Page) - Copy-on-write file system for Linux aimed at implementing advanced features while focusing on fault tolerance, repair and easy administration.
- [deborphan](http://freecode.com/projects/deborphan) - Finds packages installed on your Debian system that have no other packages depending on them.
- [IPTraf](http://iptraf.seul.org) - Network statistics utility for Linux.


## Mac OS X

- [Fink](http://www.finkproject.org) - The full world of Unix Open Source software for Darwin.
- [Homebrew](http://brew.sh) - The missing package manager for OS X.
- [itunes-remote](https://github.com/mischah/itunes-remote) - Control iTunes via CLI.
- [MacPorts](https://www.macports.org) - Compile, install and upgrade either command-line, X11 or Aqua based open-source software.
- [mas](https://github.com/mas-cli/mas) - Mac App Store command line interface.
- [Night Shift Shell Utility](https://github.com/jenghis/nshift) - Simple shell utility to control the macOS Night Shift feature.
- [reminders-cli](https://github.com/keith/reminders-cli) - Simple interface for interacting with Reminders.
- [tag](https://github.com/jdberry/tag) - Manipulate tags on files and query for files with those tags.
- [XLD](http://tmkk.undo.jp/xld/index_e.html) - Tool to decode/convert/play various lossless audio files.


## Helpers

- [crontab.guru](http://crontab.guru) - Cron schedule expression editor.


## License

<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
