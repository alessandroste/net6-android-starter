# Quickstart
1. Install dotnet SDK
1. Install `android` or `android-aot` workload
1. Open project in VS Code
1. Install recommended extensions
1. Run `Emulator` task
1. Run build task and select `Run`
1. Application is built and started on the emulator, a white screen will be shown
1. Attach the debugger to start the application

# Troubleshooting
- Build failing because no device is found: in the terminal run `adb devices` to start the ADB server. Then, in the emulator, disable and re-enable ADB setting from developer setting.