# Third-Party Notices

The Open Image Debugger plugin for JetBrains IDEs embeds the following
third-party components.

## Embedded viewer (JavaScript/WebAssembly)

The plugin's viewer is built from the open-source OpenImageDebugger engine
and embeds:

- **OpenImageDebugger** viewer core — MIT License. Full licence text below.
- **Dear ImGui** — MIT License (https://github.com/ocornut/imgui).
- **Eigen** — Mozilla Public License 2.0. Source code for Eigen is
  available at https://eigen.tuxfamily.org. Per MPL-2.0, modifications to
  Eigen files (none are made) would be made available under the same licence.
- **stb** (image writer) — MIT License / public domain
  (https://github.com/nothings/stb).
- **nanosvg** — zlib License (https://github.com/memononen/nanosvg).
- **nlohmann/json** — MIT License (https://github.com/nlohmann/json).
- **Khronos headers** — Apache 2.0 / MIT (https://github.com/KhronosGroup).
- **Emscripten runtime & GLFW shim** — MIT / University of Illinois-NCSA
  (https://github.com/emscripten-core/emscripten). The compiled viewer
  embeds the Emscripten JavaScript runtime that loads and drives the
  WebAssembly module.

## Debugger-side Python

To resolve buffer types, the plugin loads a Python package (`oidscripts`)
into the debugger's own interpreter (LLDB or GDB). Licensed under the MIT
License — see the OpenImageDebugger notice below.

## OpenImageDebugger

The MIT License (MIT)

Copyright (c) 2015-2026 Open Image Debugger contributors (github.com/OpenImageDebugger/OpenImageDebugger)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
