<img src="https://cdn.rawgit.com/herrbischoff/awesome-command-line-apps/master/assets/logo.svg" width="600">

> 为了庆祝 TUI(文本用户界面) 而精心挑选的命令行应用程序
>
> _“知识带来恐惧” (火星大学校训)_

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/herrbischoff/awesome-command-line-apps.svg?branch=master)](https://travis-ci.org/herrbischoff/awesome-command-line-apps)

如果你想贡献，强烈建议你先阅读 [贡献指南](contributing.md)。

## 咖啡捐助

当你在这找到有用的东西时，你可以捐助我一杯咖啡。我花了很多时间和精力收集这份清单。适当的咖啡因将加速收集的进展。这也是我一天的真实写照。善良的陌生人请帮助我。如果你囊中羞涩或者不想捐助，也不必感到难过。这个仓库完全是免费的，也是有趣的。

捐助原作者: https://www.patreon.com/herrbischoff

## 目录

- [\*nix/\*nux](#nixnux)
  - [自动化](#%E8%87%AA%E5%8A%A8%E5%8C%96)
  - [备份](#%E5%A4%87%E4%BB%BD)
  - [基准测试](#%E5%9F%BA%E5%87%86%E6%B5%8B%E8%AF%95)
  - [云服务](#%E4%BA%91%E6%9C%8D%E5%8A%A1)
  - [压缩](#%E5%8E%8B%E7%BC%A9)
  - [内容创建](#%E5%86%85%E5%AE%B9%E5%88%9B%E5%BB%BA)
  - [转换](#%E8%BD%AC%E6%8D%A2)
  - [数据库](#%E6%95%B0%E6%8D%AE%E5%BA%93)
  - [数据处理](#%E6%95%B0%E6%8D%AE%E5%A4%84%E7%90%86)
  - [开发人员](#%E5%BC%80%E5%8F%91%E4%BA%BA%E5%91%98)
  - [配置文件管理](#%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6%E7%AE%A1%E7%90%86)
  - [下载工具](#%E4%B8%8B%E8%BD%BD%E5%B7%A5%E5%85%B7)
  - [电子邮件](#%E7%94%B5%E5%AD%90%E9%82%AE%E4%BB%B6)
  - [加密](#%E5%8A%A0%E5%AF%86)
  - [文件管理系统](#%E6%96%87%E4%BB%B6%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F)
  - [FTP](#ftp)
  - [游戏](#%E6%B8%B8%E6%88%8F)
  - [因特网中继聊天室(IRC)](#%E5%9B%A0%E7%89%B9%E7%BD%91%E4%B8%AD%E7%BB%A7%E8%81%8A%E5%A4%A9%E5%AE%A4irc)
  - [媒体](#%E5%AA%92%E4%BD%93)
  - [杂项](#%E6%9D%82%E9%A1%B9)
  - [网络](#%E7%BD%91%E7%BB%9C)
  - [演示](#%E6%BC%94%E7%A4%BA)
  - [生产力](#%E7%94%9F%E4%BA%A7%E5%8A%9B)
  - [RSS](#rss)
  - [搜索](#%E6%90%9C%E7%B4%A2)
  - [安全](#%E5%AE%89%E5%85%A8)
  - [系统](#%E7%B3%BB%E7%BB%9F)
  - [终端](#%E7%BB%88%E7%AB%AF)
  - [文本编辑器](#%E6%96%87%E6%9C%AC%E7%BC%96%E8%BE%91%E5%99%A8)
  - [版本控制](#%E7%89%88%E6%9C%AC%E6%8E%A7%E5%88%B6)
  - [VPN](#vpn)
  - [万维网](#%E4%B8%87%E7%BB%B4%E7%BD%91)
- [BSD](#bsd)
- [Linux](#linux)
- [Mac OS X](#mac-os-x)
- [助手](#%E5%8A%A9%E6%89%8B)
- [词汇表](#%E8%AF%8D%E6%B1%87%E8%A1%A8)

## *nix/\*nux

### 自动化

- [Ansible](https://www.ansible.com) - 自动发布，自动配置以及自动更新。
- [fswatch](https://github.com/emcrisostomo/fswatch) - 多个后端的跨平台文件更改监视器。

### 备份

- [Amanda](http://www.amanda.org) - Linux、 Windows、 UNIX 以及 OS X 的开源网络备份
- [Attic](https://attic-backup.org) - Python 编写的冗余备份程序。
- [Bacula](http://blog.bacula.org) - 通过不同类型的计算机网络管理数据的备份，恢复以及验证。
- [BorgBackup](https://github.com/borgbackup/borg) - 对 Attic 功能的显著加强。
- [duply](http://duply.net) - 几乎可以在任何地方轻松创建 GPG 加密，压缩备份。
- [mysqldump-secure](https://github.com/cytopia/mysqldump-secure) - 包含加密，压缩，日志，黑名单以及 Nagios 监控集成的安全 mysqldump 脚本。

### 基准测试

- [loadtest](https://github.com/alexfernandez/loadtest) - 对选定的 HTTP URL 运行负载测试。
- [pv](http://www.ivarch.com/programs/pv.shtml) - 监控管道处理数据进度的终端工具。
- [siege](https://www.joedog.org/siege-home/) - http 负载测试和基准测试工具。

### 云服务

- [awless](https://github.com/wallix/awless) - 亚马逊云强大的命令行界面。
- [awscli](https://aws.amazon.com/cli/) - 亚马逊云官方命令行界面。
- [cadaver](http://www.webdav.org/cadaver/) - Unix 的 WebDAV 命令客户端。

### 压缩

- [archivemount](http://www.cybernoia.de/software/archivemount.html) - 使用 libarchive 挂载档案的 FUSE 文件系统。
- [dtrx](https://brettcsmith.org/2007/dtrx/) - 解决解除档案的所有麻烦。

### 内容创建

- [GitBook](https://www.npmjs.com/package/gitbook) - GitBook 命令行工具。

### 转换

- [binchunker](http://he.fi/bchunk/) - 将 **.bin / .cue** 格式的 CD 映像（有时是 **.raw / .cue** ）转换为 **.iso / .cdr** 格式。
- [Echo](https://github.com/misterGF/echo) - 将 HTML 的表格转换为 JSON/CSVs 格式。
- [Pandoc](http://pandoc.org/) - 通用文档转换器.

### 数据库

- [mycli](http://mycli.net) - 具有自动补全和语法高亮的 MySQL，MariaDB 和 Percona 的命令行界面。
- [pgcli](http://pgcli.com) - 具有自动补全和语法高亮的 Postgres 命令行界面。

### 数据处理

- [datamash](https://www.gnu.org/software/datamash/) - 对文本文件执行基本的统计功能。
- [jq](https://stedolan.github.io/jq/) - 轻量而灵活的 JSON 命令行处理器。

### 开发人员

- [bat](https://github.com/astaxie/bat) - Go 语言实现工具，类似 CURL，但是使用更加友好。
- [bcal](https://github.com/jarun/bcal) - 用于存储转换和计算的字节计算器。
- [caniuse-cmd](https://github.com/sgentle/caniuse-cmd) - 命令行使用 caniuse.com 。
- [clog](https://github.com/kentcdodds/clog-cli) - 版本更改生成工具 。
- [Cookiecutter](https://github.com/audreyr/cookiecutter) - 创建 cookiecutters (项目模板) 项目的命令行工具。
- [Critical](https://github.com/addyosmani/critical) - 提取 HTML 页面中的行内样式。
- [Grunt](http://gruntjs.com) - JavaScript 任务运行器。
- [gulp](http://gulpjs.com) - 自动化打包工具。
- [how2](https://github.com/santinic/how2) - 终端使用 stackoverflow 。
- [http-prompt](https://github.com/eliangcs/http-prompt) - 基于 HTTPie 和 prompt_toolkit 构建，具有自动补全和语法高亮功能的交互式 HTTP 命令行客户端。
- [HTTPie](https://github.com/jkbrzt/httpie) - 用户友好的 CURL 的替代方案，具有直观的 UI，支持 JSON，语法高亮，类 wget 下载和扩展等等。
- [penthouse](https://github.com/pocketjoso/penthouse) - 生成当前页面实际使用的样式。
- [Publoy](http://abhiomkar.github.io/publoy/) - 将静态网页发布到 Dropbox 的命令行工具。
- [Rebound](https://github.com/shobrook/rebound) - 程序异常时立即拉取 Stack Overflow 答案。
- [saws](https://github.com/donnemartin/saws) - 亚马逊云命令行增强工具。
- [sift](https://sift-tool.org) - 快速而强大的开源工具，可以替代 grep。
- [Yarn](https://yarnpkg.com) - 一致而安全的包管理器，可以替代 npm 。

### 配置文件管理

**.** 开头配置文件管理， Mac 默认掩藏这种文件。下面这条命令开启在访达显示配置文件，设置 **NO** 就是掩藏。

```bash
defaults write com.apple.finder AppleShowAllFiles Yes && killall Finder
```

- [dotdrop](https://github.com/deadc0de6/dotdrop) - 保存配置文件一次，可以在任何地方使用它。
- [homeshick](https://github.com/andsens/homeshick) - 使用 bash 编写， Git 来同步配置文件的工具。

### 下载工具

- [aria2](http://aria2.sourceforge.net) - 轻量、多协议和多源命令行下载工具。
- [peerflix](https://github.com/mafintosh/peerflix) - node.js 种子下载器。

### 电子邮件

- [abook](http://abook.sourceforge.net/) - 基于文本的地址簿程序，旨在与 mutt 邮件客户端一起使用。
- [Alpine](http://www.washington.edu/alpine/) - 快速，易于使用的电子邮件客户端，同时适用于没有经验的电子邮件用户以及最苛刻的高级用户。
- [imapsync](https://github.com/imapsync/imapsync) - IMAP 同步，复制以及迁移工具。
- [isync](http://isync.sourceforge.net/) - 用于同步 Maildir 以及 IMAP4 邮箱的命令行工具。
- [Mutt](http://www.mutt.org) - 所有邮件客户端都很糟糕，这个稍微好一点。
- [Notmuch](https://notmuchmail.org) - 基于标签，快速、全局搜索的电子邮件系统。
- [OfflineIMAP](https://github.com/OfflineIMAP/offlineimap) - 将你的电子邮箱与 Maildir 双向同步的工具。
- [piler](http://www.mailpiler.org/wiki/start) - 功能丰富的开源电子邮件归档方案，是商业电子邮件归档产品的替代方案。
- [Sup](https://github.com/sup-heliotrope/sup) - 用线程标记风格的电子邮件客户端。
- [Terjira](https://github.com/keepcosmos/terjira) - Jira 的命令行工具.

### 加密

- [EncFS](https://vgough.github.io/encfs/) - 在用户文件夹加密文件系统。
- [GnuPG](https://www.gnupg.org) - 免费且完整执行由 RFC4880（也称为 PGP ）定义的 OpenPGP 标准。

### 文件管理系统

- [FDUPES](https://github.com/adrianlopezroche/fdupes) - 识别或者删除特定文件夹的重复文件。
- [Midnight Commander](http://www.midnight-commander.org) - 功能丰富的可视化文件管理器。
- [Ncdu](https://dev.yorhel.nl/ncdu) - 带有 ncurses 接口的磁盘使用分析器。
- [ranger](http://ranger.nongnu.org/) - 具有 curses 接口， VI 键绑定的简约可视化文件管理器。
- [vifm](http://vifm.info) - 基于 ncurses 的文件管理器，vi 类似的按键绑定、模式、选项以及配置，也从参考了 mutt。
- [zfsnap](http://www.zfsnap.org/) - 以简单的方式滚动 ZFS 快照。

### FTP

- [CurlFtpFS](http://curlftpfs.sourceforge.net/) - 基于 FUSE 和 libcurl，用于访问 FTP 主机的文件系统。
- [LFTP](http://lftp.tech/) - 复杂的 ftp/http 客户端，同时支持多种网络协议的文件传输。
- [NcFTP](http://www.ncftp.com/ncftp/) - 实现文件传输协议的免费应用程序集合。

### 游戏

- [Angband](http://rephial.org/) - Angband 是一款免费的单人地下城探索游戏。
- [Cataclysm: Dark Days Ahead](http://en.cataclysmdda.com/) - 罗格瑞克在后世界末日的世界里。
- [Curse of War](https://a-nikolaev.github.io/curseofwar/) - 快节奏的实时动作策略游戏。
- [dopewars](http://dopewars.sourceforge.net) - 在纽约街头交易毒品，积累巨额财产并偿还高利贷，同时避开那些烦人的警察。
- [Frotz](http://frotz.sourceforge.net/) - Infocom 游戏和其他 Z-machine 游戏的运行器。
- [Nethack](http://nethack.org) - 在各种计算机系统上运行的单人地下城探索游戏。
- [vitetris](http://www.victornils.net/tetris/) - 俄罗斯方块终端克隆版，类似任天堂早期的俄罗斯方块游戏。

### 因特网中继聊天室(IRC)

- [BitlBee](https://www.bitlbee.org/main.php/news.r.html) - 因特网中继聊天室到其他聊天网络的网关。
- [Irssi](https://github.com/irssi/irssi) - 未来的聊天客户端。
- [WeeChat](https://weechat.org/) - WeeChat 是一个快速、轻量以及可扩展的聊天客户端。

### 媒体

- [abcde](https://abcde.einval.com/wiki/) - 更好的 CD 解码器.
- [AtomicParsely](http://atomicparsley.sourceforge.net/) - 用于读取和解析 MPEG-4 文件，同时设置元数据的轻量级命令行程序。
- [Audiogrep](https://antiboredom.github.io/audiogrep/) - 剪切音频工具.
- [Beets](http://beets.io/) - 极客的音乐管理器。
- [cmus](https://cmus.github.io) - 类 Unix 操作系统的小型、快速且功能强大的控制台音乐播放器。
- [FFmpeg](http://ffmpeg.org) - 用于录制、转换以及流式传输音频和视频的一站式跨平台解决方案。
- [Gifsicle](http://www.lcdf.org/gifsicle/) - 用于创建、编辑以及获取 GIF 信息的命令行工具。
- [HandBrakeCLI](https://handbrake.fr) - 用于将视频从任何格式转换为现代编解码器广泛支持的格式。
- [Legofy](https://github.com/JuanPotato/Legofy) - 将图片或者 gif 转换为乐高风格的 Python 程序。
- [MediaInfo](https://github.com/MediaArea/MediaInfo) - 统一地展示视频和音频文件的标签数据。
- [MKVToolNix](https://mkvtoolnix.download/) - 在 Linux、 other Unices 和 Windows 下创建、更改和检查 Matroska 文件的工具。
- [mopidy](https://www.mopidy.com/) - 连接到 Spotify 和 Soundcloud 的自主托管音乐播放器守护程序。
- [moviemon](https://github.com/iCHAIT/moviemon) - 展示本地电影相关信息的强大工具。
- [mp3fs](https://khenriks.github.io/mp3fs/) - 基于 FUSE 的文件转码系统，可以将 FLAC 格式转换为 MP3 。
- [mp4v2](https://code.google.com/archive/p/mp4v2) - 读取、创建以及修改 mp4 文件的工具。
- [mpg123](http://mpg123.org) - 控制台快速播放和解码的 MPEG 播放器。
- [ncmpcpp](http://rybczak.net/ncmpcpp/) - 基于 NCurses 音乐播放器守护程序客户端。
- [OptiPNG](http://optipng.sourceforge.net) - 可将图像文件无损压缩为更小尺寸的 PNG 图片优化器。
- [Pngcrush](http://pmt.sourceforge.net/pngcrush/) - PNG 文件优化器，可移植网络图片。
- [Shellpic](https://github.com/larsjsol/shellpic) - 在终端显示  ASCII 图像。
- [subdownloader](https://github.com/beatfreaker/subdownloader) - 一条命令下载一个或多个文件的字幕。
- [ttystudio](https://github.com/chjj/ttystudio) - 终端录制 GIF。
- [Video Transcoding Scripts](https://github.com/donmelton/video-transcoding-scripts) - 转码、检查以及转换视频的工具。
- [Videogrep](https://antiboredom.github.io/videogrep/) - 自动剪切视频的 python 程序。
- [youtube-dl](http://rg3.github.io/youtube-dl/) - 从 YouTube.com 或者其他网站下载视频的小型命令行程序。

### 杂项

- [ansiweather](https://github.com/fcambus/ansiweather) - ANSI 颜色 和 Unicode 符号显示天气的终端程序。
- [FIGlet](http://www.figlet.org) - 普通文本制作巨型字符的程序
- [license](https://nishanths.github.io/license/) - 命令行产生证书，所有 github 支持的证书。
- [pockyt](https://github.com/arvindch/pockyt) - [Pocket](https://getpocket.com) 的终端客户端。
- [wego](https://github.com/schachmat/wego/) - 天气的终端客户端。

### 网络

- [Bandwidth Monitor NG](https://www.gropp.org/?id=projects&sub=bwm-ng) - 小型实时网络宽带监视器终端应用。
- [Blucat](http://blucat.sourceforge.net/blucat/) - 蓝牙 netcat。
- [gping](https://github.com/orf/gping) - 图形化 Ping 命令。
- [iftop](http://www.ex-parrot.com/pdw/iftop/) - 展示宽带的使用率。
- [localtunnel](https://github.com/localtunnel/localtunnel) - 将本地主机暴露给世界各地，方便于测试和共享。
- [mtr](http://www.bitwizard.nl/mtr/) - 结合了 **traceroute** 以及 **ping** 功能的单个网络诊断工具。
- [Netcat](http://netcat.sourceforge.net) - 使用 TCP/IP 协议跨网络读取以及写入数据的网络工具。
- [Nethogs](https://github.com/raboof/nethogs) - Linux **net top** 工具。
- [ngrep](http://ngrep.sourceforge.net) - 基于 grep 的网络数据包分析器。
- [nmap](https://nmap.org) - 网络发现和安全审核工具。
- [vnStat](http://humdi.net/vnstat/) - Linux 和 BSD 的终端网络流量监视器，并且记录所选接口的网络流量。

### 演示

- [termui](https://github.com/gizak/termui) - 跨平台、易于编译和完全可定制的终端仪表板。
- [WOPR](https://github.com/yaronn/wopr) - 用于创建丰富的终端报告、演示文稿和信息图表的简单标记语言。

### 生产力

- [doing](http://brettterpstra.com/projects/doing/) - 用于跟踪你正在做的事情，并且跟踪你已完成工作的命令行工具。
- [idea](https://github.com/IonicaBizau/idea) - 轻量级命令行工具，快速而轻松地将想法保存在安全的地方。
- [ledger](http://ledger-cli.org) - 从 UNIX 命令访问的强大双重记账系统。
- [MapSCII](https://github.com/rastapasta/mapscii) - OpenStreetMap 客户端，呈现可探索的盲文和 ASCII 世界地图。
- [pdfgrep](https://pdfgrep.org) - 搜索 PDF 文本内容的命令行工具。
- [pin-cushion](https://github.com/ELLIOTTCABLE/pin-cushion) - Pinboard.in 接口的简单命令行工具。
- [Remind](https://www.roaringpenguin.com/products/remind) - 精密的日历和闹钟程序。
- [SC-IM](https://github.com/andmarti1424/sc-im) - 基于 ncurses 的电子表格程序。
- [Taskwarrior](http://taskwarrior.org) - 命令行管理 TODO 的开源免费软件。
- [Timetrap](https://github.com/samg/timetrap) - 简单的时间跟踪器。
- [Watson](http://tailordev.github.io/Watson/) - 优雅的时间跟踪器。
- [woof](http://www.home.unix-ag.org/simon/woof.html) - 一次性 HTTP 文件共享。

### RSS

- [newsbeuter](https://www.newsbeuter.org) - [Mutt](http://www.mutt.org/) 的 RSS 阅读器。
- [rss2email](http://www.allthingsrss.com/rss2email/) - 从电子邮件获取新闻的 Windows 、 UNIX 免费开源工具。

### 搜索

- [fd](https://github.com/sharkdp/fd) - fd 是简单、快速且对用户友好的 **find** 替代命令。
- [ripgrep](https://github.com/BurntSushi/ripgrep) - 使用正则表达式极速递归搜索目录。
- [The Silver Searcher](http://geoff.greer.fm/ag/) - 快速搜索代码的工具。

### 安全

- [Aircrack-ng](http://aircrack-ng.org) - 802.11 WEP 和 WPA-PSK 密钥破解程序，捕获到足够的数据包后可以破解密钥。
- [Let's Encrypt](https://letsencrypt.org) - 免费、开放的自动证书颁发机构。

* [storm]（http://stormssh.readthedocs.io/en/master/） - 一个管理 ssh 连接的命令行工具。
*
* [autossh](http://www.harding.motd.ca/autossh/) - 自动重启 SSH 会话和隧道。
* [sshfs](https://github.com/libfuse/sshfs) - 本地通过 SSH 安装远程文件夹。
* [storm](http://stormssh.readthedocs.io/en/master/) - 管理 SSH 连接的工具。

### 系统

- [ApacheTop](http://freecode.com/projects/apachetop) - 展示顶级 Apache 信息的工具，包括每秒请求数、每秒字节数以及请求最多的 URL 等等。
- [dstat](http://dag.wiee.rs/home-made/dstat/) - 替代 vmstat、iostat、 netstat 以及 ifstat 的多功能工具。
- [htop](http://hisham.hm/htop/) - 交互式流程查看器。
- [iotop](http://repo.or.cz/iotop.git) - 查看硬盘存储情况以及新增的存储。
- [maybe](https://github.com/p-e-w/maybe) - 你在希望它发生之前，看看程序做了什么。
- [netboot.xyz](https://netboot.xyz) - 单个菜单通过网络启动多个操作系统的安装程序或者应用程序。
- [screenFetch](https://github.com/KittyKatt/screenFetch) - 终端获取桌面截图的系统以及主题信息。

### 终端

- [asciinema](https://asciinema.org) - 用于录制终端会话，并在网络上共享的免费开源解决方案。
- [autojump](https://github.com/wting/autojump) - 轻松完成目录跳转的 **cd** 命令。
- [bgrep](http://debugmo.de/2009/04/bgrep-a-binary-grep/) - 类似 grep 的二进制字符串。
- [byobu](http://byobu.co) - 基于文本的窗口管理器和终端多路复用器。
- [ccat](https://github.com/jingweno/ccat) - 语法高亮的 **cat** 命令。
- [cheat](https://github.com/chrisallenlane/cheat) - 在命令行中创建和查看交互式帮助文档。
- [desk](https://github.com/jamesob/desk) - 轻量的 shell 工作区管理器。
- [dit](https://github.com/vulpino/dit) - 通过 git 管理配置文件(**.** 开头文件) 。
- [Fisherman](https://github.com/fisherman/fisherman) - fish shell 的极简插件管理器。
- [fundle](https://github.com/tuvistavie/fundle) - fish shell 的最小包管理器。
- [fzf](https://github.com/junegunn/fzf) - 通用模糊查找器。
- [Marker](https://github.com/pindexis/marker) - 终端命令调色板。
- [MultiTail](https://www.vanheusden.com/multitail/) - 监控多个终端窗口的日志文件和命令，着色、过滤和合并后输出。
- [PathPicker](https://facebook.github.io/PathPicker/) - 命令解析输出后，PathPicker 会为你提供好看的 UI ，并且选择出你感兴趣的文件。
- [pick](https://github.com/calleerlandsson/pick) - 模糊选择任何东西。
- [SCREEN](http://www.guckes.net/Screen/) - 控制台和终端的窗口管理器。
- [tmux](https://tmux.github.io) - 终端多路复用器。
- [yank](https://github.com/mptre/yank) - 将终端的输出结果复制到剪贴板。
- [z](https://github.com/rupa/z) - 基于 frecency 跟踪最常用的目录。

### 文本编辑器

- [Diakonos](http://diakonos.pist0s.ca) - 受众广泛的 Linux 编辑器。
- [Emacs](https://www.gnu.org/software/emacs/) - 可扩展、可定制的文本编辑器。
- [Kakoune](http://kakoune.org) - 具有多种选择和正交设计的模态编辑器。
- [Neovim](https://neovim.io) - Vim 编辑器的现代版本，具有许多高级功能。
- [Vim](http://www.vim.org) - 高级文本编辑器，旨在提供理想 Unix Vi 编辑器的完整功能集。
- [Vis](https://github.com/martanne/vis) - 高效文本编辑器。

### 版本控制

- [Bazaar](http://bazaar.canonical.com/en/) - Windows、Ubuntu、 GNU/Linux 以及 Mac OS X 轻松管理源代码。
- [Git](https://www.git-scm.com) - Git 是免费开源的分布式版本控制工具。
- [gitfs](https://www.presslabs.com/gitfs/) - 文件系统的版本控制.
- [grv](https://github.com/rgburke/grv) - 命令行浏览 Git 仓库。
- [Mercurial](https://www.mercurial-scm.org) - 免费的分布式源码管理工具。
- [tig](https://github.com/jonas/tig) - 基于 ncurses 的 Git 文本模式界面。

### VPN

- [OpenVPN](https://openvpn.net/index.php/open-source.html) - 全功能的开源 SSL VPN 解决方案。
- [racoon](http://ipsec-tools.sourceforge.net) - IPsec 自动连接的网络密钥交换（IKE）守护程序
- [strongSwan](https://www.strongswan.org/) - Linux 开源的 IPsec。

### 万维网

- [ELinks](http://elinks.or.cz) - 高级且功能丰富的文本浏览器。
- [GoAccess](https://goaccess.io) - 实时可视化 Web 日志分析和交互式查看器。
- [googler](https://github.com/jarun/googler) - 谷歌终端搜索，包括谷歌网站搜索和谷歌新闻。
- [pageres](https://github.com/sindresorhus/pageres) - 各种分辨率捕获网站的屏幕截图。

## BSD

- [ezjail](http://erdgeist.org/arts/software/ezjail/) - Jail 管理框架。
- [pkgsrc](http://www.pkgsrc.org) - 便携式构建系统。
- [poudriere](https://github.com/freebsd/poudriere) - 端口/包构建和测试系统。

## Linux

- [aptly](https://www.aptly.info/) - Debian 存储库管理的瑞士军刀 。
- [btrfs](https://btrfs.wiki.kernel.org/index.php/Main_Page) - Linux 的文件写入系统，旨在实现高级功能，同时专注于容错，修复和轻松管理。
- [deborphan](http://freecode.com/projects/deborphan) -  查找你的 Debian/GNU 系统上安装的包，并且没有其他包依赖查找到的包。
- [IPTraf](http://iptraf.seul.org) - Linux 终端网络统计工具。

## Mac OS X

- [Fink](http://www.finkproject.org) - Unix 开源软件的全部 Darwin 世界。
- [Homebrew](http://brew.sh) - OS X 缺失的包管理器。
- [itunes-remote](https://github.com/mischah/itunes-remote) - iTunes 命令行工具 。
- [MacPorts](https://www.macports.org) - 基于 X11 、Aqua 的开源软件，编译、安装和升级软件包命令行工具。
- [mas](https://github.com/mas-cli/mas) - App Store 命令行工具。
- [Night Shift Shell Utility](https://github.com/jenghis/nshift) - 控制 macOS Night Shift 的简单 shell 工具。
- [reminders-cli](https://github.com/keith/reminders-cli) - Reminders 的简单交互命令行工具。
- [tag](https://github.com/jdberry/tag) - 操纵文件上的标签，并且查询带有标签的文件。
- [XLD](http://tmkk.undo.jp/xld/index_e.html) - 无损解码、转换和播放各种音频文件的工具。

## 助手

- [crontab.guru](http://crontab.guru) - 定时任务表达式编辑器。

## 词汇表

- [curses](https://web.archive.org/web/20190409151623/https://en.wikipedia.org/wiki/Curses_(programming_library)) - 字符终端处理库
- [ncurses](http://www.gnu.org/software/ncurses/) - new curses 简称  ncurses，出现较多，特做说明。

## License

<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
