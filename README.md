# C++ Ray Tracer

A simple path/ray tracer based on *Ray Tracing in One Weekend* implemented in modern C++17.

## Features

- Ray-sphere intersection testing
- Camera system with configurable aspect ratio and image width
- Surface normal visualization and background gradient shading
- Hittable object list abstraction

## Requirements

- C++17 compatible compiler (Clang, GCC, MSVC)
- CMake 3.12+

## Building and Running

### Build with CMake

```bash
# Configure build directory
cmake -B build

# Compile project
cmake --build build
```

### Run and Generate Image

```bash
# Run the executable and pipe PPM output to a file
./build/raytracer > render.ppm
```

The output file `render.ppm` can be viewed with tools like Photoshop, GIMP, Preview (macOS), or converted using `convert render.ppm render.png` (ImageMagick).
