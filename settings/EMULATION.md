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
    - [X] RetroArch
    - [X] Dolphin
    - [X] WatermelonDS
    - [X] Azahar
    - [X] Mupen64Plus AE
    - [X] Eden Nightly
    - [ ] GameNative

- Set up RetroAchievements login
    - [X] RetroArch *via .cfg file*
    - [X] Dolphin
    - [X] WatermelonDS
    - [X] Mupen64Plus AE

- Set save file location
    - [?] RetroArch
    - [-] Dolphin
    - [X] WatermelonDS
    - [?] Azahar
    - [-] Mupen64Plus AE
    - [X] Eden Nightly
    - [ ] GameNative

#### Firmware
Most can be found at https://github.com/Abdess/retrobios/

- [ ] Gameboy
- [ ] Gameboy Color
- [ ] Gameboy Advanced
- [ ] Switch

### Emulator Specific

#### RetroArch
- *Settings* - *Drivers* - **Menu**: Ozone
- *Settings* - *Input* - *Menu Controls* - **Menu Swap OK and Cancel Buttons**: Off
- Download Gambatte and mGBA cores

#### Dolphin
- *Config* - *General* - **Change Discs Automatically**: Enabled
- *Config* - *GameCube* - **Slot A Device**: GCI Folder
- *Graphics* - **Video Backend**: Vulkan
- *Graphics* - **Compile Shaders Before Starting**: Enabled
- *Graphics* - **Aspect Ratio**: Force 16:9
- *Graphics* - *Enhancements* - **Internal Resolution**: 3x native
- *Graphics* - *Enhancements* - **Widescreen Hack**: Enabled

#### WatermelonDS
- *General* - **Fast-forward Max Speed**: 4x
- *General* - **Check for Updates**: Disabled
- *Save Files* - **Save Next to ROM File**: Disabled
- *System* - *Internal Firmware Settings*: Set up accordingly
- *Video* - **Renderer**: Vulkan
- *Video* - **Internal resolution**: 4x native
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
- **GPU Driver Manager**: Turnip Mr. Purple T23 Toasted

#### GameNative
- *Settings* - *Emulation* - **Auto-apply known config**: Enabled
- *Settings* - *Interface* - **Frontend Sync**: Set up ROM folder. Steam (/steam), Custom Games (/windows)
- *Settings* - *Downloads & Storage* - **Download Speed**: Blazing

### Game Specific