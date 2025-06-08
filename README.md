# Chromium Embedded Framework sandbox build

## Build
1. Set up the environment. Follow only `System requirements`, `Setting up Windows` and `git installation` sections 
https://chromium.googlesource.com/chromium/src/+/HEAD/docs/windows_build_instructions.md#system-requirements
2. Run automated build commands:
```
./setup_build.bat
./ninja_build.bat
./distrib_bin.bat
```

## Refs for understanding the build proccess
* https://bitbucket.org/chromiumembedded/cef/wiki/AutomatedBuildSetup.md
* https://bitbucket.org/chromiumembedded/cef/wiki/BranchesAndBuilding.md#markdown-header-automated-method
* https://bitbucket.org/chromiumembedded/cef/wiki/MasterBuildQuickStart.md
* https://bitbucket.org/chromiumembedded/cef/wiki/SandboxSetup.md - not updated
* https://chromium.googlesource.com/chromium/src/+/HEAD/docs/windows_build_instructions.md