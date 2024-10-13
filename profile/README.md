# zig-gamedev

Originally spawned in July 2021 by [Michal Ziulek](https://github.com/michal-z). We build a game development ecosystem for the [Zig programming language and toolchain](https://ziglang.org/).

Zero the Ziguana is an official mascot of the Zig programming language and toolchain. Licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) https://github.com/ziglang/logo

## Vision
- A very modular toolbox of libraries.
- Libraries are written from scratch in Zig or provide Ziggified bindings and build systems for carefully selected C and C++ libraries.
- No system dependencies other than Zig required to build and run on popular target platforms.

## Development repo
What was the original monorepo, the [zig-gamedev dev repo](https://github.com/zig-gamedev/zig-gamedev) is the main development hub for the [zig-gamedev libraries](libraries).

NOTE: Libraries are currently being migrated to their own repositories.

## Libraries
| Library                       | Description                                                                                                                |
|-------------------------------|----------------------------------------------------------------------------------------------------------------------------|
| **[system-sdk](https://github.com/zig-gamedev/system-sdk)**     | System libraries and headers for cross-compiling [zig-gamedev libs](https://github.com/zig-gamedev/zig-gamedev#libraries)   
| **[zaudio](https://github.com/zig-gamedev/zaudio)**     | Cross-platform audio using [miniaudio](https://github.com/mackron/miniaudio)                                                                         |
| **[zbullet](https://github.com/zig-gamedev/zbullet)**   | Build package, [C API](https://github.com/zig-gamedev/zig-gamedev/tree/main/libs/zbullet/libs/cbullet) and bindings for [Bullet physics](https://github.com/bulletphysics/bullet3)                                                                           |
| **[zflecs](https://github.com/zig-gamedev/zflecs)**     | Build package and bindings for [flecs](https://github.com/SanderMertens/flecs) ECS                                                         |
| **[zemscripten](libs/zemscripten)**  | Build package and shims for [Emscripten](https://emscripten.org) emsdk |
| **[zglfw](https://github.com/zig-gamedev/zglfw)**       | Build package & bindings for [GLFW](https://github.com/glfw/glfw)                                                                          |
| **[zgpu](https://github.com/zig-gamedev/zgpu)**         | Small helper library built on top of [Dawn](https://github.com/zig-gamedev/dawn) native WebGPU implementation                              |
| **[zgui](libs/zgui)**         | Build package and bindings for [Dear Imgui](https://github.com/ocornut/imgui), [Test engine](https://github.com/ocornut/imgui_test_engine), [ImPlot](https://github.com/epezent/implot), [ImGuizmo](https://github.com/CedricGuillemet/ImGuizmo) and [imgui-node-editor](https://github.com/thedmd/imgui-node-editor)                       |
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
| **[zwindows](https://github.com/zig-gamedev/zwindows)** | Windows development SDK for Zig game developers.                                                               |


## Projects using zig-gamedev

* [Tides of Revival](https://github.com/Srekel/tides-of-revival) - First-person, open-world, fantasy RPG being developed in the open
* [Simulations](https://github.com/ckrowland/simulations) - GPU Accelerated agent-based modeling to visualize and simulate complex systems
* [krateroid](https://github.com/kussakaa/krateroid) - 3D strategy game
* [blokens](https://github.com/btipling/blockens) - Voxel game
* [Delve Framework](https://github.com/Interrupt/delve-framework) - Simple game framework for making games with Lua
* [jok](https://github.com/jack-ji/jok) - A minimal 2D/3D game framework for Zig
* [Aftersun](https://github.com/foxnne/aftersun) - Top-down 2D RPG
* [Pixi](https://github.com/foxnne/pixi) - Pixel art editor made with Zig


## Get Zig
Zig is still in development. We track are currently tracking **0.13.0-dev.351+64ef45eb0**.

[zigup](https://github.com/marler8997/zigup) is recommended for managing compiler versions. Alternatively, you can download and install manually using the links below:

| OS/Arch         | Download link               |
| --------------- | --------------------------- |
| Windows x86_64  | [zig-windows-x86_64-0.13.0-dev.351+64ef45eb0.zip](https://ziglang.org/builds/zig-windows-x86_64-0.13.0-dev.351+64ef45eb0.zip) |
| Linux x86_64    | [zig-linux-x86_64-0.13.0-dev.351+64ef45eb0.tar.xz](https://ziglang.org/builds/zig-linux-x86_64-0.13.0-dev.351+64ef45eb0.tar.xz) |
| macOS x86_64    | [zig-macos-x86_64-0.13.0-dev.351+64ef45eb0.tar.xz](https://ziglang.org/builds/zig-macos-x86_64-0.13.0-dev.351+64ef45eb0.tar.xz) |
| macOS aarch64   | [zig-macos-aarch64-0.13.0-dev.351+64ef45eb0.tar.xz](https://ziglang.org/builds/zig-macos-aarch64-0.13.0-dev.351+64ef45eb0.tar.xz) |


