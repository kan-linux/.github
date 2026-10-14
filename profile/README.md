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



ffmpeg_src[<a href="https://github.com/kan-linux/ffmpeg"         style="text-decoration:none;">src</a>     <br><span style="font-size:10px;"> FFmpeg source</span>];
ffmpeg_deps[<a href="https://github.com/kan-linux/ffmpeg"         style="text-decoration:none;">deps</a>     <br><span style="font-size:10px;"> FFmpeg deps</span>];

x264[<a href="https://github.com/kan-linux/x264"         style="text-decoration:none;">x264</a>     <br><span style="font-size:10px;"> x264 Git mirror </span>];
x265[<a href="https://github.com/kan-linux/x265"         style="text-decoration:none;">x265</a>     <br><span style="font-size:10px;"> x265 Git mirror </span>];

Hyprland[<a href="https://github.com/kan-linux/Hyprland"         style="text-decoration:none;">Hyprland</a>    </span>];

omarchy_desktop_shell[<a href="https://github.com/kan-linux/omarchy"         style="text-decoration:none;">Omarchy-desktop-shell</a>    </span>];

strata[<a href="https://github.com/kan-linux/strata"         style="text-decoration:none;">strata</a> <br><span style="font-size:10px;"> File Manager </span>];

qtbase[<a href="https://github.com/kan-linux/qtbase"         style="text-decoration:none;">qtbase</a>     <br><span style="font-size:10px;"> Qt Base </span>];

qtwayland[<a href="https://github.com/kan-linux/qtwayland"         style="text-decoration:none;">qtwayland</a>     <br><span style="font-size:10px;"> A toolbox for making Qt based Wayland compositors </span>];

qtdeclarative[<a href="https://github.com/kan-linux/qtdeclarative"         style="text-decoration:none;">qtdeclarative</a>     <br><span style="font-size:10px;"> Qt Declarative </span>];

quickshell[<a href="https://github.com/kan-linux/quickshell"         style="text-decoration:none;">quickshell</a>     <br><span style="font-size:10px;"> QuickShell Git mirror</span>];

```


### News
- `[2026 Oct 10]` [Kan-Linux v0.2.7 released](https://github.com/kan-linux/kan/releases/tag/v0.2.7)
- `[2026 Oct 01]` [Kan-Linux v0.2.6 released](https://github.com/kan-linux/kan/releases/tag/v0.2.6)

