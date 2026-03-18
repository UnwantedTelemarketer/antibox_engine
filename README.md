# Antibox Engine

A lightweight, cross-platform game engine built from scratch in C++ with a focus on learning, simplicity and straight code. It was made to bridge the gap between something lower level like raylib and something like Unity.

## Features

* OpenGL-based rendering
* GLFW window and input handling
* Basic audio support
* Custom logging system
* Cross-platform builds (Windows + Linux via WSL)

## Getting Started

### Prerequisites

* C++17 or newer
* CMake
* A compiler (MSVC / GCC / Clang)

### Build

```bash
git clone https://github.com/UnwantedTelemarketer/antibox_engine.git
cd antibox
mkdir build
cd build
cmake ..
cmake --build .
```

### Run

After building, run the executable from the `build\bin` directory.

## Project Structure

```
/res        - Engine Resources (if any)
/build      - Build output (ignored)
```

## Notes

* Release builds may require additional configuration depending on your environment.
* Performance under WSL may differ from native Linux.

## Roadmap

* Improved rendering pipeline
* Text Rendering
* Multiplayer Support
* Better audio system
* Crash handling + logging improvements

## License

MIT License (or your preferred license)

---
