Build & Test.
```bash
cmake --install . --prefix "C:\Users\36142\Documents\learning\learn_cmake\CMake Tutorial\Step4\installdir" --config debug

ctest -c Debug -N
ctest -C Debug -VV
```