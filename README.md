# toadot

toadot, based on [Godot Engine 4.3 Branch](https://github.com/godotengine/godot/tree/4.3).

my changes of godot, with retro style in modern ways.

not in any production, just a research for now.

## why this name?

toad. --> toad + dot --> toadot

## Goals

(Explicit Commits with [THIS] or [THIS][fix], e.g: [M][fix]this commit is related the Goals)

### Modifications:

- [ ] [RGDS] remove GDScript support(will loss some performance);
- [ ] [PRB] change pack/repack/build methods;
- [ ] [RES] remove OpenGL-ES support;
- [ ] [WINAPI] minimal windows API magics;
- [ ] [RWEB] remove web support;
- [ ] [RUCH] rust with c/cpp as script languages support, natively;
- [ ] [RPY] remove scons buildsystem support, ucrt_gcc + cmake is enough.

### Customizations:

#### Assets & File System:

- [ ] [BLOB] blob bundles (all_in_one.pck -> separate_1.blob, separate_2.blob);
- [ ] [AESM] AES blob encryption, multiple keychain;
- [ ] [BLOBH] blob bundles hot update.
- [ ] [GIG] minigame engine in a engine.

#### Graphic & UI:

- [ ] [GP] customized graphic pipeline;
- [ ] [ARMG] arm embedded devices compatibility (godot has own ktx/khr compression support with PowerVR for mobile nowadays).
- [ ] [CUT] real-time cutscenes support.

#### Audio & AI-TTS framework:

- [ ] [TKM] tracker music service;
- [ ] [BIA] encoded binary audio format (*.bia), as a sample bundle for tracker service;
- [ ] [RAS] real-time audio synthesizer service works with tracker service;
- [ ] [TTS] a **minimal** and fine-grained AI-TTS service framework (*.pts required).

#### meta-game specifics & game-AI:

- [ ] [ANA] characters' habit analyzer;
- [ ] [INTI] characters' intent info;
- [ ] [AIP] characters' AI status panel.
- [ ] [BAE] assets can be decrypted with some behaviors(signals);
- [ ] [Console] buildin game console panel;

#### Security & Analyzers for debugging:

- [ ] [TD] thread detection;
- [ ] [SBP] sandboxed process.

## Middlewares:

> [!IMPORTANT]
> necessary middlewares will be built in this engine, `godot addons / three-party sdk -> middlewares`.

1. blender;
2. FFmpeg;
3. stb;
4. tracker service [MUPU-core](https://github.com/Gulfy034/mupu-core);
5. [bia-format](https://github.com/Gulfy034/bis-format);
6. [tine](https://github.com/Gulfy034/tine);
7. upx;
8. everything;
9. sbiextra;
10. gdt-cpus

## Useful Links

1. [godot-docs: escn exporter](https://docs.godotengine.org/en/4.x/tutorials/assets_pipeline/escn_exporter/index.html)
2. [godot-docs: optimizing 3d performance](https://docs.godotengine.org/en/4.x/tutorials/performance/optimizing_3d_performance.html)
3. [godot-docs: binary serialization api](https://docs.godotengine.org/en/4.x/tutorials/io/binary_serialization_api.html)
4. [godot-docs: pck](https://docs.godotengine.org/en/4.x/tutorials/export/exporting_pcks.html#opening-pck-files-at-runtime)
5. [godot-rust binding](https://github.com/godot-rust/gdext)
6. [godot-docs: custom platform ports](https://docs.godotengine.org/en/4.x/contributing/development/core_and_modules/custom_platform_ports.html)
7. [gdt-cpus](https://github.com/WildPixelGames/gdt-cpus)
8. [Android Vulkan for godot](https://developer.android.google.cn/stories/games/godot-vulkan)
9. [godot-docs: buildsystem introduction](https://docs.godotengine.org/en/4.x/contributing/development/compiling/introduction_to_the_buildsystem.html)
10. [godot-docs: SCons building system](https://docs.godotengine.org/en/4.x/about/faq.html#why-does-godot-use-the-scons-build-system)

## Licence

toadot: MIT