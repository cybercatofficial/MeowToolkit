# Meow Toolkit

An Xposed module that keeps Android security testing working on a rooted device.

Android 8+ · arm64-v8a / x86_64

## Features

| Feature | What it does |
|---|---|
| Root Bypass | Presents the device as unrooted |
| Emulator Bypass | Presents a real device instead of an emulator |
| SSL Pinning Bypass | Lets your proxy read TLS traffic |
| CA Injection | Installs your CA into the target app |
| Disable Secure Flag | Allows screenshots and screen recording of protected screens |
| Play Integrity Bypass | Improves integrity attestation results |
| PairIP / Anti-tamper Bypass | Reduces anti-tamper triggers |
| Process Table Masking | Keeps the hooking process out of process lists |
| Package Visibility Masking | Keeps the module and root apps out of package lists |
| Debugger Bypass | Hides attached debuggers |
| Developer Settings Bypass | Hides developer options and ADB state |
| Frida Bypass | Hides Frida instrumentation |
| Flutter Pinning Bypass | Bypasses pinning in Flutter apps |
| Deep Detection Bypass | Removes hooking traces from deep checks |

Every feature is an independent toggle.

## Install

1. Install **Vector** on your rooted device.
2. Open Vector → **Modules** → **Add module** → pick `MeowToolkit-1.0.0.apk`.
3. Enable the module and select the apps you want to hook.
4. Force-stop the target app, or reboot.

