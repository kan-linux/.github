## Overview

The kan-linux on Github develops and supports the kan-linux and related projects.

- [https://huggingface.co/kan-linux](https://huggingface.co/kan-linux)  - kan-linux at Hugging Face

- [https://kan-linux.com](https://kan-linux.com) - kan-linux 's official website

  

```mermaid

graph TD;
iso --> kan
iso --> installer

kan --> kernel
kan --> ggml-hexagon
kan --> ffmpeg
kan --> qt


qt --> qtbase
qt --> qtwayland
qt --> qtdeclarative

qtdeclarative --> quickshell


iso[<a href="https://github.com/kan-linux/iso"                       style="text-decoration:none;">iso</a>            <br><span style="font-size:10px;">KanLinux images & Live ISO</span>];
kan[<a href="https://github.com/kan-linux/kan"         style="text-decoration:none;">kan</a>     <br><span style="font-size:10px;">Monorepo of KanLinux</span>];

installer[<a href="https://github.com/kan-linux/installer"         style="text-decoration:none;">installer</a>     <br><span style="font-size:10px;">Installer of KanLinux</span>];



kernel[<a href="https://github.com/kan-linux/kernel"         style="text-decoration:none;">kernel</a>     <br><span style="font-size:10px;"> customized Linux kernel source tree of KanLinux</span>];


ggml-hexagon[<a href="https://github.com/kan-linux/ggml-hexagon/discussions/84"         style="text-decoration:none;">ggml-hexagon</a>     <br><span style="font-size:10px;">Original FastRPC-based ggml-hexagon, Alternative llama.cpp backend for Qualcomm Hexagon NPU </span>];



ffmpeg[<a href="https://github.com/kan-linux/ffmpeg"         style="text-decoration:none;">FFmpeg</a>     <br><span style="font-size:10px;"> customized FFmpeg source tree of KanLinux</span>];


qtbase[<a href="https://github.com/kan-linux/qtbase"         style="text-decoration:none;">qtbase</a>     <br><span style="font-size:10px;"> Qt Base </span>];



qtwayland[<a href="https://github.com/kan-linux/qtwayland"         style="text-decoration:none;">qtwayland</a>     <br><span style="font-size:10px;"> A toolbox for making Qt based Wayland compositors </span>];

qtdeclarative[<a href="https://github.com/kan-linux/qtdeclarative"         style="text-decoration:none;">qtdeclarative</a>     <br><span style="font-size:10px;"> Qt Declarative </span>];



quickshell[<a href="https://github.com/kan-linux/quickshell"         style="text-decoration:none;">quickshell</a>     <br><span style="font-size:10px;"> Flexible toolkit for making desktop shells with QtQuick </span>];

```

