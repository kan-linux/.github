## Overview

The kan-linux organization on Github develops and supports the kan-linux and related projects.

```mermaid

graph TD;
LiveISO --> kan
LiveISO --> installer

kan --> build
kan --> toolchain
kan --> system
kan --> vendor
kan --> kernel
kan --> frameworks
kan --> external

frameworks --> mesa
frameworks --> ffmpeg
frameworks --> llama.cpp
frameworks --> gtk4
frameworks --> qt

mesa --> wayland

wayland   --> Hyprland
wayland   --> quickshell

ffmpeg  --> ffmpeg_src
ffmpeg  --> ffmpeg_deps

ffmpeg_deps --> x264
ffmpeg_deps --> x265

llama.cpp --> agents

external --> shell
external --> apps

shell --> omarchy_desktop_shell
shell --> noctalia

qt --> qtbase
qt --> qtwayland
qt --> qtdeclarative

apps --> strata
apps --> firefox
apps --> wireshark
apps --> gimp

LiveISO[<span style="font-size:20px;">LiveISO</span>];
kan[<a href="https://github.com/kan-linux/kan"         style="text-decoration:none;">kan</a>     <br><span style="font-size:10px;">Monorepo of Kan-Linux</span>];

installer[<a href="https://github.com/kan-linux/installer"         style="text-decoration:none;">installer</a>     <br><span style="font-size:10px;">Installer of KanLinux</span>];

kernel[<a href="https://github.com/kan-linux/kernel"         style="text-decoration:none;">kernel</a> ];


llama.cpp[<a href="https://github.com/kan-linux/ggml-hexagon/discussions/84"         style="text-decoration:none;">llama.cpp</a>     <br><span style="font-size:10px;"> customized llama.cpp for Kan-Linux</span>];


Hyprland[<a href="https://github.com/kan-linux/Hyprland"         style="text-decoration:none;">Hyprland</a>    </span>];

omarchy_desktop_shell[<a href="https://github.com/kan-linux/omarchy"         style="text-decoration:none;">Omarchy-desktop-shell</a>    </span>];

noctalia[<a href="https://github.com/kan-linux/noctalia"         style="text-decoration:none;">noctalia</a>    </span>];

strata[<a href="https://github.com/kan-linux/strata"         style="text-decoration:none;">strata</a> <br><span style="font-size:10px;"> File Manager </span>];



quickshell[<a href="https://github.com/kan-linux/quickshell"         style="text-decoration:none;">quickshell</a>     <br><span style="font-size:10px;"> QuickShell Git mirror</span>];

```


### News
- `[2026 Oct 17]` [Kan-Linux v0.2.8 released](https://github.com/kan-linux/kan/releases/tag/v0.2.8)
- `[2026 Oct 10]` [Kan-Linux v0.2.7 released](https://github.com/kan-linux/kan/releases/tag/v0.2.7)
- `[2026 Oct 01]` [Kan-Linux v0.2.6 released](https://github.com/kan-linux/kan/releases/tag/v0.2.6)

