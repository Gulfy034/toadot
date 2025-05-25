# toadot

toadot, based on [Godot Engine 4.3 Branch](https://github.com/godotengine/godot/tree/4.3).

my changes of godot, with retro style in modern ways.

not in any production, just a research for now.

## why this name?

toad. --> toad + dot --> toadot

## Goals

(Explicit Commits with [THIS] or [THIS][fix], e.g: [M][fix]this commit is related the Goals)

### Modifications:

- [ ] [RGDS] remove GDScript support(will loss);
- [ ] [PRB] change pack/repack/build methods;
- [ ] [RES] remove OpenGL-ES support;
- [ ] [WINAPI] minimal windows API;
- [ ] [RWEB] remove web support;

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
- [ ] [AIP] characters' AI panel.
- [ ] [BAE] assets can be decrypted with some behaviors(flags or message).

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

## Licence

toadot: MIT