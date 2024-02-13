# C++ VCPKG Template Project

1. Clone or download the repo
  * If cloned, remove remote reference: `git remote remove origin`
  * If download
    * create git repo: `git init`
    * remove vendor/vcpkg folder
    * recreate vcpkg submoduel (`git submodule add  https://github.com/microsoft/vcpkg .\vendor\vcpkg`)
2. Set up vcpkg submodule
  * `git submodule init`
  * `git submodule update`
  * `vendor/vcpkg/bootstrap-vcpkg`
3. Configure using appropriated preset
  * Windows: `cmake --preset msvc-debug`
  * Linux: `cmake --preset gcc-debug`

