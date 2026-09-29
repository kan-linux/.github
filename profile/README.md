## Overview

The kan-linux on Github develops and supports the kan-linux and related projects.

- [https://huggingface.co/kan-linux](https://huggingface.co/kan-linux)  - kan-linux at Hugging Face

- [kan](https://github.com/kan-linux/kan): an Agent-First, Agent-Friendly modern Linux desktop built from scratch

- [ggml-hexagon](https://github.com/kan-linux/ggml-hexagon/discussions/84): Original FastRPC-based ggml-hexagon, Alternative llama.cpp backend for Qualcomm Hexagon NPU (Android / WoS(Windows on Snapdragon) / Linux)
  

```mermaid

graph TD;
iso --> kan
iso --> installer
kan --> ggml-hexagon
kan --> linux
kan --> ffmpeg



iso[<a href="https://github.com/kan-linux/kan"                       style="text-decoration:none;">iso</a>            <br><span style="font-size:10px;">KanLinux images & Live ISO</span>];
kan[<a href="https://github.com/kan-linux/kan"         style="text-decoration:none;">kan</a>     <br><span style="font-size:10px;">Monorepo of KanLinux</span>];

installer[<a href="https://github.com/kan-linux/installer"         style="text-decoration:none;">installer</a>     <br><span style="font-size:10px;">Installer of KanLinux</span>];


ggml-hexagon[<a href="https://github.com/kan-linux/ggml-hexagon/discussions/84"         style="text-decoration:none;">ggml-hexagon</a>     <br><span style="font-size:10px;">Original FastRPC-based ggml-hexagon, Alternative llama.cpp backend for Qualcomm Hexagon NPU </span>];

```

