# Build using CMake
### Clone repo
```
git clone https://github.com/n1sk4/SDL-template.git
cd SDL-template
```

### Configure CMake build
```
cmake -B build -DBUILD_SHARED_LIBS=OFF -DCMAKE_BUILD_TYPE=Release

// -DBUILD_SHARED_LIBS -> switch between static and dynamic library linking

cmake --build build --config Release
```