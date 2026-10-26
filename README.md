# FEST MDS408 Android Controller — Starter Project

This is a native Android (Kotlin + Jetpack Compose) starter UI for a FEST MDS408 4-input / 8-output loudspeaker management system.

## Included
- Professional dark DSP interface
- 4 input channels and 8 output channels
- Input/output gain controls
- Output limiter controls
- Parametric EQ (PEQ) controls
- Delay controls
- Crossover controls
- Local editable UI state (demo only)

## Important hardware limitation
This project is a UI prototype. It does **not** yet send commands to a real FEST MDS408. The available product information confirms PC programming/control and a rear USB connector, but the device's USB protocol/command format has not been verified. Do not connect this app to hardware expecting control until the protocol is documented or captured from the official PC software.

## Build
1. Open this folder in Android Studio (recent version).
2. Allow Gradle sync.
3. Run on an Android device or emulator (Android 8.0+).

If Android Studio asks to update Gradle/Android Gradle Plugin, accept compatible updates.
