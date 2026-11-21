# APSORP RP Launcher (Android starter project)

Pink/black Android launcher for the SA-MP Mobile package `com.sampmobilerp.game`.

Configured server: `15.235.160.89:62121`

Features in this starter:
- Editable player-name field; last value is saved locally.
- APSORP RP server address shown in the launcher.
- Launches the installed SA-MP Mobile app.

Important limitation: this project does **not** yet pass the player name, IP, or port into SA-MP. The supplied client APK's supported external-connect interface has not been established. The user must select/connect to APSORP RP inside SA-MP after it opens. Do not describe this build as one-tap auto-connect.

## Build
Open this folder in Android Studio with Android SDK 35 installed, then Build > Build APK(s). It uses Android Gradle Plugin 8.6.1. The current work environment has no Android SDK/Gradle installation, so a compiled APK could not be produced here.
