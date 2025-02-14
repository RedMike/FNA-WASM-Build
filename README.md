# FNA-WASM-Build

![WASM Build (FNA)](https://github.com/clarvalon/FNA-WASM-Build/workflows/WASM%20Build%20(FNA)/badge.svg)

IMPORTANT: This repo is currently set up to build only FNA 25.01 as that is the last SDL2-using version of FNA. The workflow needs fixing to work with SDL3, which I will try to get to.

This repo is for automating the build of WebAssembly (WASM) native libraries for [FNA](https://fna-xna.github.io/), including:

* [FNA3D.a](https://github.com/FNA-XNA/FNA3D) - 3D graphics library for FNA.
* [FAudio.a](https://github.com/FNA-XNA/FAudio) - XAudio reimplementation for FNA.
* [SDL2.a](https://github.com/libsdl-org/SDL) - Simple DirectMedia Layer.
* ~[libtheorafile.a](https://github.com/FNA-XNA/Theorafile) - Ogg Theora videos decoder library.~ (not yet implemented)

There is currently just one workflow:

1.  **WASM Build (FNA)**.  

# Usage

Go to the Actions tab and download the .zip artifact from the latest workflow run.  
See for further details:  https://gist.github.com/TheSpydog/e94c8c23c01615a5a3b2cc1a0857415c
