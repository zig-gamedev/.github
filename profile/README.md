# zig-gamedev

Originally spawned in July 2021 by [Michal Ziulek](https://github.com/michal-z). We build a game development ecosystem for the [Zig programming language and toolchain](https://ziglang.org/)

* [Cross-platform and composable libraries](https://github.com/zig-gamedev/zig-gamedev#Libraries)
* [Cross-platform sample applications](https://github.com/zig-gamedev/zig-gamedev#sample-applications-native-wgpu)
* [DirectX 12 sample applications](https://github.com/zig-gamedev/zig-gamedev#sample-applications-directx-12)

Zero the Ziguana is an official mascot of the Zig programming language and toolchain. Licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) https://github.com/ziglang/logo


## Vision
* Very modular toolbox of libraries
* Zig is the only prerequisit to build on Windows, macOS and Linux; no platform specific libraries or build tools need to be installed
* Libraries are written from scratch in Zig *or* provide bindings for carefully selected C/C++ libraries


## Libraries
Note: Libraries are currently located in [the monorepo](https://github.com/zig-gamedev/zig-gamedev) and are each being migrated to there own repository.
| Library                       | Description                                                                                                                |
|-------------------------------|----------------------------------------------------------------------------------------------------------------------------|
| **[system-sdk](https://github.com/zig-gamedev/system-sdk)**     | System libraries and headers for cross-compiling [zig-gamedev libs](https://github.com/zig-gamedev/zig-gamedev#libraries)   
| **[zaudio](https://github.com/zig-gamedev/zaudio)**     | Cross-platform audio using [miniaudio](https://github.com/mackron/miniaudio)                                                                         |
| **[zbullet](https://github.com/zig-gamedev/zbullet)**   | Build package, [C API](https://github.com/zig-gamedev/zig-gamedev/tree/main/libs/zbullet/libs/cbullet) and bindings for [Bullet physics](https://github.com/bulletphysics/bullet3)                                                                           |
| **[zd3d12](https://github.com/zig-gamedev/zd3d12)**     | Helper library for DirectX 12                                                                                 |
| **[zflecs](https://github.com/zig-gamedev/zflecs)**     | Build package and bindings for [flecs](https://github.com/SanderMertens/flecs) ECS                                                         |
| **[zglfw](https://github.com/zig-gamedev/zglfw)**       | Build package & bindings for [GLFW](https://github.com/glfw/glfw)                                                                          |
| **[zgpu](https://github.com/zig-gamedev/zgpu)**         | Small helper library built on top of [Dawn](https://github.com/zig-gamedev/dawn) native WebGPU implementation                              |
| **[zgui](https://github.com/zig-gamedev/zgui)**         | Build package and bindings for [Dear Imgui](https://github.com/ocornut/imgui) (includes [ImPlot](https://github.com/epezent/implot))       |
| **[zjobs](https://github.com/zig-gamedev/zjobs)**       | Generic job queue implementation                                                                                                           |
| **[zmath](https://github.com/zig-gamedev/zmath)**       | SIMD math library for game developers                                                                                                      |
| **[zmesh](https://github.com/zig-gamedev/zmesh)**       | Loading, generating, processing and optimizing triangle meshes                                                                             |
| **[znoise](https://github.com/zig-gamedev/znoise)**     | Build package & bindings for [FastNoiseLite](https://github.com/Auburn/FastNoiseLite)                                                      |
| **[zopengl](https://github.com/zig-gamedev/zopengl)**   | OpenGL loader (supports 4.2 Core Profile and ES 2.0 Profile)                                                                               |
| **[zopenvr](https://github.com/zig-gamedev/zopenvr)**   | Bindings for [OpenVR](https://github.com/ValveSoftware/openvr)                                                                             |
| **[zphysics](https://github.com/zig-gamedev/zphysics)** | Build package, [C API](libs/zphysics/libs/JoltC) and bindings for [Jolt Physics](https://github.com/jrouwe/JoltPhysics)                    |
| **[zpix](https://github.com/zig-gamedev/zpix)**         | Support for GPU profiling with PIX for Windows                                                           |
| **[zpool](https://github.com/zig-gamedev/zpool)**       | Generic pool & handle implementation                                                                     |
| **[zsdl](https://github.com/zig-gamedev/zsdl)**         | Bindings for SDL2 and SDL3                                                                               |
| **[zstbi](https://github.com/zig-gamedev/zstbi)**       | Image reading, writing and resizing with [stb](https://github.com/nothings/stb) libraries                |
| **[ztracy](https://github.com/zig-gamedev/ztracy)**     | Support for CPU profiling with [Tracy](https://github.com/wolfpld/tracy)                                                                   |
| **[zwin32](https://github.com/zig-gamedev/zwin32)**     | Bindings for Win32 API (d3d12, d3d11, xaudio2, directml, wasapi and more)                                                                  |
| **[zxaudio2](https://github.com/zig-gamedev/zxaudio2)** | Helper library for XAudio2                                                                               |    


## Public projects using zig-gamedev

* [Tides of Revival](https://github.com/Srekel/tides-of-revival) - First-person, open-world, fantasy RPG being developed in the open
* [Simulations](https://github.com/ckrowland/simulations) - GPU Accelerated agent-based modeling to visualize and simulate complex systems
* [krateroid](https://github.com/kussakaa/krateroid) - 3D strategy game
* [blokens](https://github.com/btipling/blockens) - Voxel game
* [Delve Framework](https://github.com/Interrupt/delve-framework) - Simple game framework for making games with Lua
* [jok](https://github.com/jack-ji/jok) - A minimal 2D/3D game framework for Zig
* [Aftersun](https://github.com/foxnne/aftersun) - Top-down 2D RPG
* [Pixi](https://github.com/foxnne/pixi) - Pixel art editor made with Zig
