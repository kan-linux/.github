## Overview

The kan-linux on Github develops and supports the kan-linux and related projects.

- [https://huggingface.co/kan-linux](https://huggingface.co/kan-linux)  - kan-linux at Hugging Face

- [https://kan-linux.com](https://kan-linux.com) - kan-linux 's official website

  

```mermaid

graph TD;
iso --> kan
iso --> installer

kan --> build
kan --> toolchain
kan --> system
kan --> vendor
kan --> framework

framework --> Hyprland

kan --> kernel
kan --> external

external --> llama.cpp
external --> ff

ff  --> FFmpeg
ff  --> ffmpeg_deps

ffmpeg_deps --> x264
ffmpeg_deps --> x265


external --> qt


qt --> qtbase
qt --> qtwayland
qt --> qtdeclarative

qtdeclarative --> quickshell


iso[<a href="https://github.com/kan-linux/iso"                       style="text-decoration:none;">iso</a>            <br><span style="font-size:10px;">KanLinux images & Live ISO</span>];
kan[<a href="https://github.com/kan-linux/kan"         style="text-decoration:none;">kan</a>     <br><span style="font-size:10px;">Monorepo of KanLinux</span>];

installer[<a href="https://github.com/kan-linux/installer"         style="text-decoration:none;">installer</a>     <br><span style="font-size:10px;">Installer of KanLinux</span>];



kernel[<a href="https://github.com/kan-linux/kernel"         style="text-decoration:none;">kernel</a>     <br><span style="font-size:10px;"> customized Linux kernel source tree for KanLinux</span>];


llama.cpp[<a href="https://github.com/kan-linux/ggml-hexagon/discussions/84"         style="text-decoration:none;">llama.cpp</a>     <br><span style="font-size:10px;"> customized llama.cpp for KanLinux</span>];



FFmpeg[<a href="https://github.com/kan-linux/ffmpeg"         style="text-decoration:none;">FFmpeg</a>     <br><span style="font-size:10px;"> customized FFmpeg source tree for KanLinux</span>];

x264[<a href="https://github.com/kan-linux/x264"         style="text-decoration:none;">x264</a>     <br><span style="font-size:10px;"> x264 Git mirror </span>];
x265[<a href="https://github.com/kan-linux/x265"         style="text-decoration:none;">x265</a>     <br><span style="font-size:10px;"> x265 Git mirror </span>];

Hyprland[<a href="https://github.com/kan-linux/Hyprland"         style="text-decoration:none;">Hyprland</a>     <br><span style="font-size:10px;"> Hyprland Git mirror </span>];


qtbase[<a href="https://github.com/kan-linux/qtbase"         style="text-decoration:none;">qtbase</a>     <br><span style="font-size:10px;"> Qt Base </span>];



qtwayland[<a href="https://github.com/kan-linux/qtwayland"         style="text-decoration:none;">qtwayland</a>     <br><span style="font-size:10px;"> A toolbox for making Qt based Wayland compositors </span>];

qtdeclarative[<a href="https://github.com/kan-linux/qtdeclarative"         style="text-decoration:none;">qtdeclarative</a>     <br><span style="font-size:10px;"> Qt Declarative </span>];



quickshell[<a href="https://github.com/kan-linux/quickshell"         style="text-decoration:none;">quickshell</a>     <br><span style="font-size:10px;"> QuickShell Git mirror</span>];

```

