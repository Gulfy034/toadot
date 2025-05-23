# toadot

toadot, based on [Godot Engine 4.3 Branch](https://github.com/godotengine/godot/tree/4.3).

my changes of godot.

## why this name?

toad. --> toad + dot --> toadot

## Todos

### Modifications:

1. remove GDScript support;
2. change pack/repack/build methods;
3. remove OpenGL-ES support;
4. minimal windows API;
5. remove web support;

### Customizations:

#### Assets and File System:

1. blob package files (all_in_one.pck -> separate_1.blob, separate_2.blob);
2. AES multiple-assets encryption;
3. blob files hot update;

#### Graphic & UI:

1. customized graphic pipeline;
2. windows native DWM api port;
3. arm embedded devices & mobile devices enhancement with powerVR sdk;

#### Audio:

1. tracker music support;
2. encoded binary audio format (*.bia);
3. real-time audio synthesizer support;
4. minimal and fine-grained TTS;

#### meta-game specifics

1. characters' habit analyzer;
2. characters' intent info;

#### Safety

1. thread detection;
2. sandboxed process;

## Licence

toadot: MIT