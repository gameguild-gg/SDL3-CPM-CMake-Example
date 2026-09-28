# SDL3-CPM-CMake-Example

## Summary
Example on how to import SDL3 via CPM (CMake Package Manager) into a CMake project.

It downloads and imports CPM if not present, then fetches SDL3, SDL3_image, Dear ImGui and GLEW. Small tricks on CMakeLists.txt link SDL3 into your executable correctly.

The emscripten (WebAssembly) build is built and deployed to GitHub Pages automatically via GitHub Actions — no manual Settings -> Pages configuration needed.

- SDL Renderer https://infinibrains.github.io/SDL2-CPM-CMake-Example/
- OPENGL Renderer https://infinibrains.github.io/SDL2-CPM-CMake-Example/opengl.html

ToDo: support https://github.com/bkaradzic/bgfx
