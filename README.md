# Awesome cl software with stars

<div align="center">
<h1>Awesome Common Lisp Application Software</h1>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 499,518 | 🐛 106 | 📅 2026-08-21

![Lisp logo](https://github.com/azzamsa/lisp-logo/blob/master/logos/lisp-lizard-with-text.svg)

</div>

***

This is a list of awesome [application software](https://en.wikipedia.org/wiki/Application_software) built with Common Lisp.

We want to keep the 'master' list curated. If you want to uncurated list, see [complete list branch](https://github.com/azzamsa/awesome-cl-software/tree/complete-list) ⭐ 396 | 🐛 2 | 📅 2026-06-20.

See also:

<div align="center">
  <a href="https://www.lisp-screenshots.org/" target="_blank">
    <img src="lisp-screenshots-banner-thin.png">
  </a>
</div>

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->

**Table of Contents**

* [Applications](#applications)
  * [Audio](#audio)
  * [Blogging](#blogging)
    * [Static Blog Generator](#static-blog-generator)
  * [Chat](#chat)
    * [Chat Bot](#chat-bot)
  * [Development Tools](#development-tools)
    * [Databases](#databases)
    * [Editors](#editors)
    * [Others](#others)
  * [Desktop Environment](#desktop-environment)
  * [Education](#education)
  * [File Manager](#file-manager)
  * [Games](#games)
  * [Graphics](#graphics)
    * [Image Creation](#image-creation)
    * [Image Viewer](#image-viewer)
  * [Internet](#internet)
    * [Browser](#browser)
    * [Chat](#chat-1)
    * [Torrent](#torrent)
  * [Operating System](#operating-system)
  * [Productivity](#productivity)
  * [Publishing](#publishing)
  * [Social news](#social-news)
  * [Utilities](#utilities)
  * [Video Player](#video-player)
  * [Wiki software](#wiki-software)
  * [Window Manager](#window-manager)
  * [Other](#other)
    * [Historical Purposes](#historical-purposes)
* [Mobile Applications](#mobile-applications)
* [Other Lists](#other-lists)
* [Contributors](#contributors)
* [Guidelines to contribute](#guidelines-to-contribute)
* [Unsure how to contribute?](#unsure-how-to-contribute)
* [Note](#note)
* [License](#license)

<!-- markdown-toc end -->

## Applications

### Audio

* ⭐ [OpenMusic](https://github.com/openmusic-project/openmusic/) ⭐ 415 | 🐛 6 | 🌐 Common Lisp | 📅 2026-08-19 visual programming / computer-aided composition environment. \[GPL3]\[2].
  * developped at [IRCAM](https://www.stms-lab.fr/team/representations-musicales/), France. The base of other research projects and software, such as [MusiqueLab2](https://www.stms-lab.fr/shop/product/musique-lab-2/), distributed by France's ministry of education to all music teachers.
* ⭐ [OM7](https://github.com/openmusic-project/om7) ⭐ 176 | 🐛 31 | 🌐 Common Lisp | 📅 2022-09-14 - a new implementation of the OpenMusic visual programming and computer-aided composition environment including a number of improvements on graphical interface, computational mode, and connection to external software libraries. \[GPL3]\[2].
* [Incudine](https://github.com/titola/incudine) ⭐ 60 | 🐛 1 | 🌐 Common Lisp | 📅 2026-07-23 -  Music/DSP programming environment for Common Lisp. Useful to design software synthesizers or sound plugins from scratch. It is also a compositional tool that allows to produce high quality sounds controllable at the sample level, defining and redefining the digital signal processors and the musical structures on-the-fly.
* [Common Music](https://github.com/ormf/cm) ⚠️ Archived - the repository of an ancient version of Common Music (version 2.12.0), the presumably last version which ran on Common Lisp dating from around 2007-09, before work on Common Music shifted to (scheme-based) cm3.
* [Ernestine](https://github.com/nlamirault/ernestine) ⭐ 6 | 🐛 1 | 🌐 Common Lisp | 📅 2022-01-14 - Ernestine is a music management application in McClim. [MIT].
* ⭐ [OpusModus](http://opusmodus.com/) - a comprehensive computer-aided environment for the whole work of music composition. [Proprietary].
* ⭐ [ScoreCloud](https://scorecloud.com/) - A web and mobile application to automatically create music notation from music performance or recordings. Built with LispWorks.
* 👍 [MusicEase](https://www.musicease.com) - Music notation software, developed for over 35 years. Proprietary.
  * "MusicEase is a constraint-based system with a large amount of knowledge of music notation. This allows it to intelligently handle many of the details of scoring automatically."
  * a [LispWorks success story](http://www.lispworks.com/success-stories/musicease.html).
  * includes a fully functional demo, free for 30 days (printouts are watermarked). Available on Windows and MacOS.
* [CLM](https://ccrma.stanford.edu/software/clm/) - Common Lisp Music is a music synthesis and signal processing package in the Music V family. It provides much the same functionality as Stk, Csound, SuperCollider, PD, CMix, cmusic, and Arctic — a collection of functions that create and manipulate sounds, aimed primarily at composers (in CLM's case anyway).
* [PWGL](http://www2.siba.fi/PWGL/) - A Visual Programming Language for Music and Sound.

Terminal applications:

* [oscl](https://github.com/ogrew/oscl) ⭐ 9 | 🐛 0 | 🌐 Common Lisp | 📅 2025-06-04 - a minimal CLI tool that lets you send and receive OSC messages from the terminal, making it useful for scripting, testing, and quick integration with OSC-enabled systems.
* [Benben](https://chiselapp.com/user/MistressRemilia/repository/benben/dir?ci=tip) - a fast and efficient command line audio player and audio converter for Linux and other Unix-like systems with an oldschool-inspired interface. It supports multiple formats, and is especially suited to people who organize their music in folders.
  * with AppImages (for Linux x86-64)
  * project goals:
    * High-performance playback of the most common music formats (audio decoding written in Common Lisp, relies on as few bindings as possible)
    * A TUI program designed for people who keep their music organized in folders. The overall design should be similar to tools like mpg123 or flac123, where you select the files to play from the command line, but with a much nicer interface.
    * Fast rendering of multiple files to WAV and Au in parallel.
    * An optional set of high-quality effects, such as an equalizer and reverb.
    * project non-goal: a file browser to add files while Benben is running. This would directly contradict project goal #2.

![](benben.png "benben music player and audio converter")

*stalling*:

* [Shuffletron](https://github.com/ahefner/shuffletron) ⭐ 52 | 🐛 2 | 🌐 Common Lisp | 📅 2024-10-23 - a search-based music player for the terminal. MIT-style licence. *stalling*

### Blogging

* [Ext-blog](https://github.com/kevinlynx/ext-blog) ⭐ 44 | 🐛 2 | 🌐 Common Lisp | 📅 2013-01-30 - blog engine. It supports custom theme and you can port a WordPress theme for it. \[No License Specified].
* [HSSG](https://gitlab.com/HiPhish/cl-hssg) - the Hackable Static Site generator. [AGPL3]
* [Cliki2](https://github.com/vsedach/cliki2) - The wiki software behind cliki.net [AGPL3]

See also:

* [Klipse](https://github.com/viebel/klipse) ⭐ 3,134 | 🐛 83 | 🌐 HTML | 📅 2024-10-01 - written in ClojureScript, allows to include run-able code snippets, including Common Lisp.

#### Static Blog Generator

* [Coleslaw](https://github.com/kingcons/coleslaw) ⭐ 584 | 🐛 31 | 🌐 Common Lisp | 📅 2024-12-12 - Flexible Lisp Blogware.
* [Collards](https://collards.kingcons.io/) - A static site generator for those who love Markdown and parens.
  * markdown blog posts, custom pages, local preview with hot reloading,
  * deployment via rsync, CLI app
  * RSS feeds, tag and year indexes.

### Chat

* [Lisp-chat](https://github.com/ryukinix/lisp-chat) ⭐ 206 | 🐛 2 | 🌐 Common Lisp | 📅 2026-07-22 - An experimental minimal chat. [MIT].
* [Collen](https://github.com/Shinmera/colleen) ⚠️ Archived - Common Lisp IRC bot with a modular framework.
* [Lichat](https://shirakumo.github.io/maiden/clients/lichat/) - Lichat client for Maiden. [Artistic License 2.0]

See also:

* [Potato](https://github.com/cicakhq/potato) ⚠️ Archived - Delicious conversations platform in Common Lisp and ClojureScript. \[stalling]

#### Chat Bot

* [Lisp-bots](https://github.com/stassats/lisp-bots) ⭐ 20 | 🐛 4 | 🌐 Common Lisp | 📅 2023-11-25 - Bots from #lisp. [MIT].
* [Alice](https://github.com/TeMPOraL/alice) ⭐ 18 | 🐛 146 | 🌐 Common Lisp | 📅 2017-11-04 - Alice Margatroid, a dollmaster that pretends not to be a doll itself. \[No license Specified].
* [Magitek](https://github.com/sjl/magitek) ⭐ 5 | 🐛 0 | 🌐 Common Lisp | 📅 2022-08-28 - Whimsical robots infused with just a hint of magic. No license specified.

### Development Tools

* [Cepl](https://github.com/cbaggers/cepl) ⭐ 886 | 🐛 99 | 🌐 Common Lisp | 📅 2026-07-09 - Code Evaluate Play Loop. [2-clause BSD].
* [Seed](https://github.com/phantomics/seed) ⭐ 139 | 🐛 2 | 🌐 Common Lisp | 📅 2026-08-05 - Interactive software environment based on Common Lisp. [GPL3].
* [barf](https://github.com/ebzzry/barf) - A simple Nixpkgs and NixOS helper. [CC0].

Terminal applications:

* [gitwatch](https://github.com/garlic0x1/gitwatch) ⭐ 1 | 🐛 0 | 🌐 Common Lisp | 📅 2023-11-03 - Notify a Discord channel when repos are updated.

#### Databases

* ⭐ [Pgloader](https://github.com/dimitri/pgloader/) ⭐ 6,498 | 🐛 27 | 🌐 Common Lisp | 📅 2026-07-24 - Migrate to PostgreSQL in a single command!. [PostgreSQL License]
* ⭐ [Pgchart](https://github.com/dimitri/pgcharts) ⭐ 402 | 🐛 13 | 🌐 Common Lisp | 📅 2020-06-01 - A self-contained web application that takes as input an SQL query text and outputs its data as a chart. \[No License Specified]
* ⭐ [AllegroGraph](https://franz.com/agraph/allegrograph/) - A modern, high-performance, persistent graph database.

#### Editors

* [Lem](https://github.com/cxxxr/lem) ⭐ 3,029 | 🐛 89 | 🌐 Common Lisp | 📅 2026-08-12 - Common Lisp editor/IDE with high expansibility. [MIT].
  * works out of the box for many languages. Has a Language Server Protocol (LSP) client.
  * Git interface
* [Neomacs](https://github.com/neomacs-project/neomacs) ⭐ 285 | 🐛 14 | 🌐 Common Lisp | 📅 2025-02-17 - Neomacs is a computing environment based on structural editing. Neomacs aims to become the Emacs of trees. Currently, Neomacs is a usable Lisp IDE and keyboard-driven browser. GPL3.

![](https://github.com/neomacs-project/neomacs/raw/master/matrix.png "Neomacs")

and also:

* [Second Climacs](https://github.com/robert-strandh/Second-Climacs) ⭐ 294 | 🐛 8 | 🌐 Common Lisp | 📅 2026-07-17 - Version 2 of the Climacs text editor.
* [Hemlock](https://github.com/bluelisp/hemlock) ⭐ 48 | 🐛 8 | 🌐 Common Lisp | 📅 2018-10-30 -  Portable version of the Hemlock editor. \[No Licence Specified].
* [Med](https://github.com/burtonsamograd/med) ⭐ 14 | 🐛 1 | 🌐 Common Lisp | 📅 2015-03-18 - Emacs-like text editor for the Mezzano operating system. [MIT].

Classical CL tools (Emacs front-end (Slime), CL back-end (Swank)):

* [SLIME](https://github.com/slime/slime) ⭐ 2,078 | 🐛 286 | 🌐 Common Lisp | 📅 2026-08-20 - The Superior Lisp Interaction Mode for Emacs.
* [Sly](https://github.com/joaotavora/sly) ⭐ 1,431 | 🐛 190 | 🌐 Common Lisp | 📅 2026-08-01 - Sylvester the Cat's Common Lisp IDE (slime's fork)

Third-party:

* [Judge0 IDE](https://ide.judge0.com/?lUpj) is an online editor which supports Common Lisp (SBCL). \[MIT]\[200].

For more lisp development libraries, see [Awesome-cl](https://github.com/CodyReichert/awesome-cl) ⭐ 2,970 | 🐛 47 | 🌐 Makefile | 📅 2026-08-17.

#### Others

* [gilt](https://github.com/parenworks/gilt) ⭐ 9 | 🐛 0 | 🌐 Common Lisp | 📅 2026-08-20 -  LazyGit-inspired TUI for Git.
* [Regex-coach](http://weitz.de/regex-coach/) - a graphical application for Windows which can be used to experiment with (Perl-compatible) regular expressions interactively. Freeware.

<img src="https://raw.githubusercontent.com/parenworks/gilt/master/images/gilt1.png" title="gitl TUI" alt="gilt TUI for git." style="max-width: 100%"/>

### Desktop Environment

* [mold-desktop](https://codeberg.org/mmontone/mold-desktop) - a programmable, in-browser desktop. \[AGPL]
* [Barista](https://40ants.com/barista/) - a macOS menu-bar application framework in Common Lisp.
  * built-in plugins: pomodoro, clipboard, currency, system monitor.

<img src="https://40ants.com/barista/docs/images/pomodoro.gif" title="" alt="Barista: macOS menu-bar application." style="max-width: 100%"/>

For inspiration:

* [Mcclim-desktop](https://github.com/gas2serra/mcclim-desktop) ⭐ 30 | 🐛 1 | 🌐 Common Lisp | 📅 2021-11-16 - a launcher of McClim applications. (stalled)
  * [console](https://github.com/gas2serra/mcclim-desktop/blob/master/Apps/console/README.org) ⭐ 30 | 🐛 1 | 🌐 Common Lisp | 📅 2021-11-16, [threads manager](https://github.com/gas2serra/mcclim-desktop/blob/master/Apps/task-manager/README.org) ⭐ 30 | 🐛 1 | 🌐 Common Lisp | 📅 2021-11-16, [image editor](https://github.com/slyrus/spectacle) ⭐ 7 | 🐛 0 | 🌐 Common Lisp | 📅 2017-08-25…
  * a clim-desktop clone. [GPL3].

### Education

* [Axiom](https://github.com/daly/axiom) ⭐ 395 | 🐛 16 | 🌐 PostScript | 📅 2023-08-02 -  Axiom is a free, open source computer algebra system. It is developed in its Spad language that compiles to Common Lisp.
  * [FriCAS](https://github.com/fricas/fricas) ⭐ 394 | 🐛 36 | 📅 2026-08-21 is a fork, more maintained and easier to build. «The FriCAS algebra library is the largest and most advanced free general purpose computer algebra system».
  - FriCAS is written in its own strongly (but not statically) typed language and compiles to over half a million lines of Common Lisp code.
  - It comes with a fine print manual over 800 pages.
  - Example [blog post using FriCAS](https://www.stylewarning.com/posts/beating-bellard/)
* [MathB](https://github.com/susam/mathb) ⭐ 372 | 🐛 0 | 🌐 Common Lisp | 📅 2025-03-16 - a math pastebin.
* [Maxima](https://sourceforge.net/projects/maxima/files/) - Computer Algebra System written in Common Lisp. [GPL2].

### File Manager

* [Filer](https://github.com/froggey/Mezzano) ⭐ 3,886 | 🐛 14 | 🌐 Common Lisp | 📅 2026-08-16 - Mezzano File Manager.

See also:

* cl-tuition library's [file manager example](https://github.com/atgreen/cl-tuition/tree/master?tab=readme-ov-file#gallery) ⭐ 144 | 🐛 3 | 🌐 Common Lisp | 📅 2026-08-09.
* [Lem's directory-mode](https://lem-project.github.io/modes/directory/).

![The Lem editor's directory mode](https://github-production-user-asset-6210df.s3.amazonaws.com/13656378/239887331-8c790229-1f7c-4581-b093-9c56d4d85420.png "Lem's directory mode")

### Games

* [Kandria](https://github.com/Shirakumo/kandria) ⚠️ Archived - a post-apocalyptic exploratory 2D platformer game and hack and slack action RPG. \[zlib License]
  * Uses the [Trial](https://github.com/shirakumo/trial) ⚠️ Archived game engine.
  * entirely made in Common Lisp. Published on Steam.
* [sucle](https://github.com/terminal625/sucle) ⭐ 309 | 🐛 11 | 🌐 Common Lisp | 📅 2022-07-31 - A Minecraft clone (voxel game engine). [MIT].
* [Capture the Flag engine](https://github.com/atgreen/ctfg) ⭐ 12 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-14 - challenges with a live scoreboard.
  * alternative to the open source python-based game engine (CTFd): "It's mostly OK, but we had serious performance problems (UI locking up) when we approached any kind of interesting scale."
  * "a style of game that's popular in cybersecurity circles, where you are presented with a series of challenges that, when solved, provides text "flags". The flags gives you points. It's a competition, which is why ctfg has a live scoreboard. I would run this as a live, in-person event, and have the live scoreboard up on the big screen to make it exciting. I don't run it as a cybersecurity event. It's more of a fun kubernetes training experience."
  * [reddit announce](https://www.reddit.com/r/Common_Lisp/comments/1m4twe9/ctfg_a_capturetheflag_game_engine_in_common_lisp/)
* [ChessLab](https://tomscii.sig7.se/chesslab/) - a desktop application for chess players and chess enthusiasts. [blog post](https://tomscii.sig7.se/2025/11/ChessLab-A-program-for-chess-players) (2025). GPL3.
  * browse through game collections and replay games;
  * keep a record of your own games;
  * maintain an opening repertoire;
  * evaluate and analyse positions;
  * play chess against the computer (UCI interface, Stockfish, Fairy-Stockfish);
  * solve puzzles;
  * look at a (virtual) 3D chessboard.
* [Jettatura](https://store.steampowered.com/app/2023440/Jettatura/) - a challenging first-person dungeon-crawler (DRPG) with round-based combat.
  * Published on Steam on October, 2022. Proprietary.

Those appeared in game jams (the list is not exhaustive):

* [Asteroids](https://github.com/andyhd/asteroids) ⭐ 119 | 🐛 1 | 🌐 Common Lisp | 📅 2018-07-27 - Asteroids game in Common Lisp. \[No License Specified].
* [CotD](https://github.com/gwathlobal/CotD) ⭐ 82 | 🐛 0 | 🌐 Common Lisp | 📅 2024-03-05 - A roguelike battle of Angels and Demons in the streets of a Human city. [GPL3].
* [The-invaders](https://github.com/sebity/the-invaders) ⭐ 43 | 🐛 0 | 🌐 Common Lisp | 📅 2015-08-08 - A remake of the classic game Space Invader. [GPL2].
* [Option-9](https://github.com/psilord/option-9) ⭐ 35 | 🐛 0 | 🌐 Common Lisp | 📅 2022-12-11 -  A Shoot'em Up Game. No license specified.
* [Starwar](https://github.com/xzpeter/starwar) ⭐ 30 | 🐛 1 | 🌐 Common Lisp | 📅 2012-06-06 - Starwar. \[No License Specified].
* [Perfectstorm](https://github.com/lispgames/perfectstorm) ⭐ 28 | 🐛 0 | 🌐 Common Lisp | 📅 2017-12-03 - Perfectstorm is a real time strategy game study. [MIT](https://opensource.org/licenses/MIT).
* [Notalone](https://github.com/borodust/notalone) ⭐ 23 | 🐛 1 | 🌐 Common Lisp | 📅 2020-09-29 - You wake up nowhere in the night. Hungry zombies around, but your ol' pal "BOOMSTICK" is with you. [GPL3]
* [Ninja-sphere](https://github.com/rpav/ninja-sphere) ⭐ 7 | 🐛 0 | 🌐 Common Lisp | 📅 2017-04-25 - Ninja Sphere. No license specified.
* [nano-towers](https://bohonghuang.itch.io/nano-towers) - a simple tower defense game written in Common Lisp with the EON framework based on Raylib, submitted for the Spring Lisp Game Jam 2024.
* [dmomd](https://codeberg.org/artchad/dmomd) - a rogue-like RPG with turn based movement and combat.
* [Orb](https://baggers.itch.io/orb) - you control a spaceship and you must protect the Orb, and yourself.
* [the price of a cup of coffee](https://goofist.itch.io/the-price-of-a-cup-of-coffee)

A Chrome Dinosaur robot:

* [Cl-dino](https://github.com/VitoVan/cl-dino) ⭐ 217 | 🐛 0 | 🌐 Common Lisp | 📅 2023-02-23 - A Chrome Dinosaur Robot. [GPL3].

See also:

* [Jak and Daxter](https://en.wikipedia.org/wiki/Jak_and_Daxter) - Jak and Daxter. [Proprietary].

![ChessLab](https://tomscii.sig7.se/images/chesslab/analysis.png "Chesslab, built with the new Barium Lisp GUI toolkit")

### Graphics

* [charapainter](https://github.com/apr3vau/charapainter) ⭐ 38 | 🐛 0 | 🌐 Common Lisp | 📅 2025-09-14 - Drawing & converting images with colorful characters. Export to image, HTML and terminal. Desktop application.
  * LispWorks. Also available in the AppStore.

<img src="https://raw.githubusercontent.com/apr3vau/charapainter/main/res/0.2preview1.png" alt="Charapainter screenshot: drawing images with colorful characters" style="max-width: 100%"/>

* [cl-pkr](https://github.com/VitoVan/cl-pkr) ⭐ 49 | 🐛 3 | 🌐 Common Lisp | 📅 2022-09-30 - a cross-platform color picker. [GPL3].
  * GUI built with the Tk framework.

#### Image Creation

* ⭐ [Sketch](https://github.com/vydd/sketch) ⭐ 1,497 | 🐛 39 | 🌐 Common Lisp | 📅 2026-01-18 -A Common Lisp framework for the creation of electronic art, visual design, game prototyping, game making, computer graphics, exploration of human-computer interaction, and more.
* ⭐ [Kons-9](https://github.com/kaveh808/kons-9) ⭐ 651 | 🐛 33 | 🌐 Common Lisp | 📅 2023-11-13 - A 3D content creation tool. [MIT]
  * <https://www.youtube.com/watch?v=THMzaVDaZP8>
* [Weir](https://github.com/inconvergent/weir) ⚠️ Archived - An experimental system for writing generative systems.
* [PTC's 3D designer "Creo Elements" CAD software](https://www.ptc.com/en/products/cad/3d-design) - 3D Design Software. [Proprietary].
  * "Creo Elements/Direct is a comprehensive system for mechanical engineers and designers who create products using the direct modeling approach to 3D CAD."
  * example use: the Eterna brand usee it to [develop its watches](https://www.youtube.com/watch?v=mJGytRaNvec).
  * "7+ million lines of Common Lisp code" ([source: ELS 2009 slides](http://www.clausbrod.de/cgi-bin/view.pl/Blog/DefinePrivatePublic20090620CommonLispInCoCreateModeling))
  * they offer a [free version to download](https://www.ptc.com/en/products/creo/elements-direct/modeling-express) for Microsoft Windows x64.
* [Flow](https://codeberg.org/shinmera/flow) - Tools for the representation of graphs and flowcharts.

Terminal applications:

* [visp](https://github.com/ogrew/visp) ⭐ 19 | 🐛 0 | 🌐 Common Lisp | 📅 2025-06-25 - ffmpeg wrapper CLI tool. MIT.
  * It simplifies repetitive ffmpeg operations like resolution conversion, audio stripping, codec switching, and more — all while auto-generating output filenames.

![Creo Elements CAD software](https://ptc-p-001.sitecorecontenthub.cloud/api/public/content/4dbbdeacc96b4863962e3ddde262b95b "Creo Elements CAD software")

#### Image Viewer

* [Halftone](https://github.com/Shinmera/halftone) ⚠️ Archived - A simple image viewer in Common Lisp.
* [pixel-diff](https://github.com/screenshotbot/pixel-diff) ⭐ 29 | 🐛 0 | 🌐 Common Lisp | 📅 2025-09-02 - a desktop and command line tool to visualize differences between images, designed for use with screenshot tests. MPL-2.0.
  * built with LispWorks' CAPI, by [ScreenShotBot](https://screenshotbot.io/).
  * new as of August, 2025.
* [Spectacle](https://github.com/slyrus/spectacle) ⭐ 7 | 🐛 0 | 🌐 Common Lisp | 📅 2017-08-25 - A CLIM application for viewing opticl images. [2-clause BSD](https://directory.fsf.org/wiki/License:BSD_2Clause).

### Internet

* [mx-proxy](https://github.com/garlic0x1/mx-proxy) ⭐ 21 | 🐛 0 | 🌐 Common Lisp | 📅 2024-05-23 - a Web debugging proxy - with an Electron, GTK4 or Tcl/Tk GUI.
* [Happening](https://github.com/atgreen/happening) ⭐ 11 | 🐛 0 | 🌐 Common Lisp | 📅 2026-04-18 - A privacy-focused, self-hosted web analytics platform.
  * self-hosted
  * No cookies, no personal data collection
  * built-in TLS certificates
  * built-in IP-to-country lookup
  * single binary
  * interactive setup wizard
  * self-update support
* [crafterbin](https://github.com/parenworks/crafterbin) ⭐ 3 | 🐛 0 | 🌐 Common Lisp | 📅 2026-07-12 - a temporary file sharing service written in Common Lisp.

#### Browser

* [Nyxt](https://github.com/atlas-engineer/nyxt/) ⭐ 11,005 | 🐛 145 | 🌐 Common Lisp | 📅 2026-02-26 - The fastest productivity web-browser.

Deprecated:

* [Lispkit](https://github.com/AeroNotix/lispkit) ⭐ 243 | 🐛 21 | 🌐 Common Lisp | 📅 2016-05-19 - A lisp web browser using WebKit

#### Chat

* [lisp-chat](https://github.com/ryukinix/lisp-chat/) ⭐ 206 | 🐛 2 | 🌐 Common Lisp | 📅 2026-07-22 - An experimental chat irc-like written in Lisp.
  * terminal and web interfaces
  * alternative clients: Emacs, Flutter GUI for MacOS, Android, iOS and web.
* [CLatter](https://github.com/parenworks/CLatter) ⭐ 12 | 🐛 0 | 🌐 Common Lisp | 📅 2026-02-20 - A terminal-based IRC client written in Common Lisp using the croatoan ncurses library.

<img src="https://raw.githubusercontent.com/ryukinix/lisp-chat/master/lisp-chat-web.png" alt="lisp-chat web interface" style="max-width: 100%"/>

#### Torrent

* [cl-torrents](https://github.com/vindarel/cl-torrents) ⭐ 118 | 🐛 0 | 🌐 Common Lisp | 📅 2025-01-14 - a library and app with a command line and readline interface to search for torrents on popular trackers.

### Operating System

* [Mezzano](https://github.com/froggey/Mezzano) ⭐ 3,886 | 🐛 14 | 🌐 Common Lisp | 📅 2026-08-16 - An operating system written in Common Lisp
* [Yalo](https://github.com/whily/yalo) ⭐ 592 | 🐛 1 | 🌐 Common Lisp | 📅 2022-05-11 - Lisp OS running on bare metal x86-64 hardware (WIP)

### Productivity

* [Ichiran](https://github.com/tshatrov/ichiran) ⭐ 406 | 🐛 13 | 🌐 Common Lisp | 📅 2026-07-04 - Linguistic tools for texts in Japanese language. [MIT].
* [Projectured](https://github.com/projectured/projectured) ⚠️ Archived -  ProjecturEd is a generic purpose projectional editor. \[No License Specified].
* [Deftask](https://github.com/deftask/deftask-cli) ⭐ 18 | 🐛 1 | 🌐 Common Lisp | 📅 2019-01-30 - Painless task management for teams. \[Partly Open Source].
* [Grammarly](https://www.grammarly.com/) - Grammar checking. [Proprietary].
* 🚀 [Ballish](https://ballish.margaine.com/) - A pretty fast code search tool. [GPL2].
* [Screenshotbot](https://screenshotbot.io)
  * Visual Testing as a service. Get notified on Pull Requests when your code changes your UI, mobile or web. Built with LispWorks.

See also:

* [Turtl](https://github.com/turtl/api) ⭐ 238 | 🐛 22 | 🌐 Common Lisp | 📅 2018-12-02 - a secure note taking, bookmarking and document storage app. \[AGPL].
  * however, while you can still find the [Common Lisp components](https://github.com/turtl/core-cl) ⭐ 51 | 🐛 0 | 🌐 Common Lisp | 📅 2015-11-23 of Turtl, it was migrated to JavaScript. Read more: <http://lisp-journey.gitlab.io/blog/why-turtl-switched-from-lisp-to-js/>

### Publishing

* [etap](https://github.com/didierverna/etap) ⭐ 35 | 🐛 0 | 🌐 Common Lisp | 📅 2026-07-15 -  Experimental Typesetting Algorithms Platform.
* [ABStock](https://github.com/vindarel/ABStock) ⭐ 29 | 🐛 0 | 🌐 Common Lisp | 📅 2025-12-05 - allows to publish an online catalogue of products. Primarily made for books.
  * used in production since 2021.

### Social news

* 🚀[Reddit v1 source code](https://github.com/tamurashingo/reddit1.0/) ⭐ 64 | 🐛 3 | 🌐 Common Lisp | 📅 2025-07-11 ([reddit](https://www.reddit.com/r/programming/comments/883vzs/old_reddit_source_code/)). [Proprietary].

### Utilities

* [cl-ledger](https://github.com/ledger/cl-ledger) ⭐ 111 | 🐛 2 | 🌐 Common Lisp | 📅 2025-08-28 - a port of the double-entry accounting system. [3-clause BSD].
* [Mediaimport](https://github.com/fourier/mediaimport) ⚠️ Archived - Import media files (jpgs/movies) from cameras. \[No License Specified].
* [Hju](https://github.com/TeMPOraL/hju) ⭐ 1 | 🐛 6 | 🌐 Common Lisp | 📅 2017-08-30 -  Simple command line (CLI) controller for Hue lights. [MIT].

### Video Player

* [Terentino](https://github.com/froggey/Mezzano) ⭐ 3,886 | 🐛 14 | 🌐 Common Lisp | 📅 2026-08-16 - Mezzano Video Player. [MIT].

### Wiki software

* [Aliw](https://github.com/vy/aliw) ⚠️ Archived - A Lisp in Wonderland (aka. ALIW) is a wiki software. [2-clause BSD].

### Window Manager

* [Stumpwm](https://github.com/stumpwm/stumpwm) ⭐ 2,023 | 🐛 90 | 🌐 Common Lisp | 📅 2026-05-30 - The Stump Window Manager.
* [Paulownia](https://github.com/stumpwm/paulownia) ⚠️ Archived - A modern re-write of stumpwm. [GPL2].

### Other

* [Kindista](https://github.com/kindista/kindista) ⭐ 60 | 🐛 2 | 🌐 Common Lisp | 📅 2026-01-04 - A social network for local sharing. [AGPL3]
* [Denso](https://github.com/start-jsk/denso) ⭐ 20 | 🐛 12 | 🌐 Common Lisp | 📅 2018-04-24 - A controller package suite for robots from Densowave based on open-industrial-ros-controllers. \[No License Specified].
* [Pocket Change](https://www.pocket-change.jp/en/) - Converts leftover coins and bills to electronic money, gift codes, and coupons of your choice. [Proprietary].
* [Cyc](http://www.cyc.com/) - Build a database of heuristics. [Proprietary].
* [Zen](https://github.com/pyb/zen) - The zen X server in Common Lisp. [GPL3].

#### Historical Purposes

* Endless list. See [complete list branch](https://github.com/azzamsa/awesome-cl-software/tree/complete-list) ⭐ 396 | 🐛 2 | 📅 2026-06-20.
* [DART](https://en.wikipedia.org/wiki/Dynamic_Analysis_and_Replanning_Tool) - Application to optimize and schedule the transportation of supplies or personnel and solve other logistical problems.
* [ICAD](https://en.wikipedia.org/wiki/ICAD_\(software\)) - A knowledge-based CAD system.
* [Interleaf Publisher](https://en.wikipedia.org/wiki/Interleaf) - A document processor.
* [Itasca database][Expat] - Database.
* [Metal](https://en.wikipedia.org/wiki/METAL_MT) - Siemens machine translation system.
* [Mirai](http://www.izware.com/mirai) - A venerable 3D editor built on the winged-edge data structure. [Proprietary].
* [Sk8](https://en.wikipedia.org/wiki/SK8) - A multimedia authoring environment.
* [Action!][Expat] - Expertelligence' Interface Designer.
* [PRISM](http://www.radonc.washington.edu/medinfo/prism/) - The Prism project is a long term project to build software tools for radiation therapy planning, including artificial intelligence tools as well as manual simulation systems.

## Mobile Applications

* [ScoreCloud Express](https://apps.apple.com/us/app/scorecloud-express/id566535238) - An iPhone and iPad application that automatically creates music notation from music performance or recordings.
* [CL REPLay](https://gitlab.com/eql/EQL5-Android/tree/master/examples/REPL) - A REPL with simple editor. No license specified.
* [Sokoban](https://gitlab.com/eql/EQL5-Android/tree/master/examples/sokoban) - Sokoban game. No license specified.
* [Maxima on Android](https://play.google.com/store/apps/details?id=jp.yhonda), built with ECL.

- [CodePlayground](https://codeplayground.app/) - an iPhone and iPad app with Lisp support via CCL.

## Other Lists

* [awesome-cl](https://github.com/CodyReichert/awesome-cl) ⭐ 2,970 | 🐛 47 | 🌐 Makefile | 📅 2026-08-17
* [Awesome Lisp Company](https://github.com/azzamsa/awesome-lisp-companies) ⭐ 649 | 🐛 7 | 📅 2026-06-12
* [Common Lisp games](https://github.com/lispgames/lispgames.github.io/wiki/Common-Lisp) ⭐ 257 | 🐛 2 | 🌐 HTML | 📅 2025-06-20
  * [Lisp Game Jams](https://github.com/lispgames/lispgames.github.io/wiki/Lisp-Game-Jams) ⭐ 257 | 🐛 2 | 🌐 HTML | 📅 2025-06-20
* [Allegro Common Lisp Success Stories ](https://franz.com/success/) - by Franc Inc
  * [Customer Application List](https://franz.com/success/all_customer_apps.lhtml)
* [Cliki](http://cliki.net/) -  CLiki the common lisp wiki
  * [Application](http://cliki.net/application) - Stand-alone applications written in Common Lisp
* [Lisp Companies](http://pchristensen.com/blog/lisp-companies/) - by Peter Christensen.
* [Lisp-lang Success Stories](http://lisp-lang.org/success/)
* [LispWorks Success Stories  ](http://www.lispworks.com/success-stories/index.html)
* [Paul Graham - Applications](http://www.paulgraham.com/apps.html)
* [Wikipedia Common Lisp Software](https://en.wikipedia.org/wiki/Category:Common_Lisp_software)

## Contributors

Thanks to All of Github contributors and Everyone @ reddit.com/r/lisp ad r/Common\_Lisp/ for many suggestions and compliments.

## Guidelines to contribute

Please follow this format of the list  `[Appname](#link) - description. [License].`
if you want to make a contribution.

* Put the name of the **application** and **link** to its **homepage** in the list.
* Write a **short description** for the application.
* Add a **license** in the end of the list. *see the list format above*
* Make sure it is put under the **appropriate topic**.
* If the application doesn't fit in any **existing topic**, make a **new one** for it.
* Sort the item by its **popularity**.
  * we come up with this approach since alphabetically sorted make people unnoticed which app has more active development and which app unmaintained or abandoned.

## Unsure how to contribute?

* [How to Use Github](https://guides.github.com/activities/forking/)
* [How to Git from the Command Line](https://rogerdudler.github.io/git-guide/)
* [What is Markdown?](https://github.com/LewisVo/Markdown-Tutorial) ⚠️ Archived - Markdown is the writing method used to create this list, if you want to know how to format properly, it's best that you learn how to use Github Markdown.
* [Alternative Markdown Guide:](https://guides.github.com/features/mastering-markdown/)

## Note

* You can learn about licenses in [tl;drLegal](https://tldrlegal.com/)
* There are so many Applications buit with Lisp, but most of them are more than 20 years old, this [list will be endless](https://www.reddit.com/r/lisp/comments/77tgpl/awesome_common_lisp_application_software/doprwez/) as Rainer Joswig said, so here I wil only include the relevant application.

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

[Expat]: http://directory.fsf.org/wiki/License:Expat

[Artistic License 2.0]: http://directory.fsf.org/wiki/License:ArtisticLicense2.0

[GPL3]: http://www.gnu.org/copyleft/gpl.html

[GPL2]: https://www.gnu.org/licenses/gpl-2.0.html

[LGPL]: http://opensource.franz.com/preamble.html

[AGPL3]: https://www.gnu.org/licenses/agpl.html

[3-clause BSD]: http://directory.fsf.org/wiki/License:BSD_3Clause

[2-clause BSD]: https://opensource.org/licenses/bsd-license.php

[MIT]: https://opensource.org/licenses/MIT

[Proprietary]: https://en.wikipedia.org/wiki/Proprietary_software

[PostgreSQL License]: https://www.postgresql.org/about/licence/

[LLGPL]: https://tldrlegal.com/license/lisp-lesser-general-public-license

[CC0]: https://creativecommons.org/publicdomain/zero/1.0/

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
