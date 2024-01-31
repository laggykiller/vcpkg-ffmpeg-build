This repo is for building ffmpeg with different version of vcpkg, 
allowing for bisecting vcpkg.

Build action would be triggered on push, and result is available in artifact

Remember to change commit hash for vcpkg in both `build.yml` and `vcpkg.json`