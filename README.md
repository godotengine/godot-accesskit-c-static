This repo contains prebuilt versions of [AccessKit C](https://github.com/AccessKit/accesskit-c) library and CI build configs.

See [Releases page](https://github.com/godotengine/godot-accesskit-c-static/releases).

---

> [!IMPORTANT]
> AccessKit API is unstable, only the versions listed below can be used to build specific version of Godot:
> 
> - Godot [4.5](https://github.com/godotengine/godot/releases/tag/4.5-stable), [4.5.1](https://github.com/godotengine/godot/releases/tag/4.5.1-stable), [4.5.2](https://github.com/godotengine/godot/releases/tag/4.5.2-stable) - [AcceeKit 0.17.0](https://github.com/godotengine/godot-accesskit-c-static/releases/tag/0.17.0)
>
> - Godot [4.6](https://github.com/godotengine/godot/releases/tag/4.6-stable), [4.6.1](https://github.com/godotengine/godot/releases/tag/4.6.1-stable) - [AcceeKit 0.18.0](https://github.com/godotengine/godot-accesskit-c-static/releases/tag/0.18.0)
> 
> - Godot [4.6.2](https://github.com/godotengine/godot/releases/tag/4.6.2-stable), [4.6.3](https://github.com/godotengine/godot/releases/tag/4.6.3-stable), [4.7](https://github.com/godotengine/godot/releases/tag/4.7-stable), [4.7.1](https://github.com/godotengine/godot/releases/tag/4.7.1-stable),  - [AcceeKit 0.21.2](https://github.com/godotengine/godot-accesskit-c-static/releases/tag/0.21.2)
>
> - Godot [4.7.2](https://github.com/godotengine/godot/releases/tag/4.7.2-stable) - [AcceeKit 0.22.3](https://github.com/godotengine/godot-accesskit-c-static/releases/tag/0.22.3)

---

Patches:

- `patch_arm32.diff` - Adds target path for the 32-bit ARM Linux (`arm-unknown-linux-gnueabihf`) build.
- `patch_gnullvm.diff` - Updates Corrosion to the commit with MinGW/LLVM toolchain support (`*-pc-windows-gnullvm`).

There are no changes to the library code.
