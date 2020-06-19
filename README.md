- [cpp-travis-ci](#cpp-travis-ci)
- [Test List](#test-list)
  - [CMake Command](#cmake-command)

# cpp-travis-ci
Demo Travis CI

# Test List

- C++ Build
- C++ Break Build
- Install specific gcc version
- Integrate with CMake
- Add Test Framework
- On Branches

## CMake Command

```bash
/usr/bin/cmake --no-warn-unused-cli -DCMAKE_EXPORT_COMPILE_COMMANDS:BOOL=TRUE -DCMAKE_BUILD_TYPE:STRING=Debug -DCMAKE_C_COMPILER:FILEPATH=/usr/bin/gcc-9 -DCMAKE_CXX_COMPILER:FILEPATH=/usr/bin/g++-9 -H/home/niketnaidu/repository/cpp-travis-ci -B/home/niketnaidu/repository/cpp-travis-ci/build -G Ninja
```