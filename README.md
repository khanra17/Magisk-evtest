# Magisk evtest
This Magisk module adds the evtest binary to your Android device. `evtest` is a simple command-line tool that allows you to monitor and test input devices such as touchscreens, keyboards, and mice.

### Installation
1. Download the [Magisk evtest module zip file](https://github.com/khanra17/Magisk-evtest/releases).
2. Open the Magisk Manager app.
3. Click on the menu icon in the top left corner and select "Modules".
4. Click on the "Install from storage" button.
5. Select the Magisk evtest module zip file and click on "Install".
6. Wait for the installation to complete and then reboot your device.

### Usage
Once the module is installed, you can use the `evtest` binary in a terminal emulator app or an adb shell session. For example, to monitor events from a specific device, run:
```bash
evtest /dev/input/eventX
```

Replace `eventX` with the actual input device you want to monitor.

Note: This Magisk module includes a limited version of the `evtest` binary compiled for aarch64 devices. If you need a full-featured version of `evtest`, you can compile it yourself from the [evtest source code](https://gitlab.freedesktop.org/libevdev/evtest).


### Disclaimer
Use this module at your own risk. The developer is not responsible for any damage that may occur to your device.

### Credits
- [evtest](https://gitlab.freedesktop.org/libevdev/evtest).
- The Android Community and everyone who has helped me learn through the years.
- John Wu (@topjohnwu) for all things Magisk.