Build the installer.
```bash
# Build a binary release
cpack -G ZIP -C Debug
# Build a source code distribution
cpack --config CPackSourceConfig.cmake
```