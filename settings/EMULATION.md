# Emulation Setup

## Emulators
- **Nintendo Game Boy** - RetroArch Gambatte
- **Nintendo Game Boy Color** - RetroArch Gambatte
- **Nintendo Game Boy Advanced** - RetroArch mGBA
- **Nintendo GameCube** - Dolphin
- **Nintendo DS** - WatermelonDS (MelonDualDS)
- **Nintendo 3DS** - Azahar
- **Nintendo 64** - Mupen64Plus AE
- **Nintendo Wii** - Dolphin
- **Nintendo Switch** - Eden Nightly
- **Steam** - GameNative
- **Minecraft Java** - Zalith Launcher

## Settings

### General
- Set up controller profile
    - [ ] RetroArch
    - [ ] Dolphin
    - [ ] WatermelonDS
    - [ ] Azahar
    - [ ] Mupen64Plus AE
    - [ ] Eden Nightly
    - [ ] GameNative

- Set up RetroAchievements login
    - [ ] RetroArch *via .cfg file*
    - [ ] Dolphin
    - [ ] WatermelonDS
    - [ ] Mupen64Plus AE

- Set save file location
  "Internal Storage/saves/<platform>"
    - [ ] RetroArch Gambatte
    - [ ] RetroArch mGBA
    - [ ] Dolphin
    - [ ] WatermelonDS
    - [ ] Azahar
    - [ ] Mupen64Plus AE
    - [ ] Eden Nightly
    - [ ] GameNative

#### Firmware
Most can be found at https://github.com/Abdess/retrobios/tree/main/bios

- [ ] Switch

### Emulator Specific

#### RetroArch
- **Menu Driver:** Ozone
- Download Gambatte and mGBA cores

#### Dolphin
- *Config* - *General* - **Change Discs Automatically**: Enabled
- *Config* - *GameCube* - **Slot A Device**: GCI Folder
- *Graphics* - **Video Backend**: Vulkan
- *Graphics* - **Compile Shaders Before Starting**: Enabled
- *Graphics* - *Enhancements* - **Internal Resolution**: 3x native
- *Graphics* - *Enhancements* - **Widescreen Hack**: Enabled

#### WatermelonDS
- *General* - **Fast-forward Max Speed**: 4x
- *General* - **Check for Updates**: Disabled
- *Save Files* - **Save Next to ROM File**: Disabled
- *System* - *Internal Firmware Settings*: Set up accordingly
- *General* - **Fast-forward Max Speed**: 4x
- *Video* - **Renderer**: OpenGL
- *Audio* - **Microphone Source**: Device Microphone
- *Input* - **Soft Input Opacity**: ~20%

#### Azahar
- *Settings* - *General* - **Check For Updates**: Disabled
- *Settings* - *System*: Set up accordingly
- *Settings* - *Graphics* - **Async Shader Compilation**: Enabled
- *Settings* - *Graphics* - **Internal Resolution**: 4x Native
- *Settings* - *Graphics* - **Integer Scaling**: Disabled
- *Settings* - *Layout* - **Landscape Screen Layout**: Single Screen
- *Settings* - *Layout* - **Secondary Display Layout**: Bottom Screen

#### Mupen64Plus AE
- *Settings* - *Display* - **Rendered Resoltion**: 1440x1080
- *Profiles* **Emulation**: Software-Renderer

#### Eden Nightly
- *Advanced Settings* - *Graphics* - **Resolution**: 1.25x
- *Advanced Settings* - *Performance Overlay* - **Enable**: Disabled
- *Advanced Settings* - *Device Overlay* - **Enable**: Disabled
- *Advanced Settings* - *Input Overlay* - **Enable**: Disabled
- *Controls* - *Player 1* - **Controller Type**: Pro Controller
- **GPU Driver Manager**: Mr. Purple T23 Toasted

#### GameNative
- *Settings* - *Emulation* - **Auto-apply known config**: Enabled
- *Settings* - *Interface* - **Frontend Sync**: Set up ROM folder. Steam (/steam), Custom Games (/windows)
- *Settings* - *Downloads & Storage* - **Download Speed**: Blazing

### Game Specific