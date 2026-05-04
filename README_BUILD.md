# Build notes

Repository root must contain this CMakeLists.txt file. Do not replace it with build_local.sh.

GitHub Actions command:

```bash
cmake -S . -B build -G Ninja -DPICO_BOARD=pico
cmake --build build --verbose
```
