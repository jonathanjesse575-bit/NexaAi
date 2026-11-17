# NEXA AI — Android starter project

A native Kotlin + Jetpack Compose starter for the NEXA AI assistant.

## Included in this first build
- Branded chat interface (white, navy and bright blue)
- Text input and chat bubbles
- Android speech-recognition prompt (requires microphone permission and a speech recognition service)
- Android text-to-speech replies
- Safe demo `call <number>` command that opens the dialler; the user reviews and places the call
- Basic greeting/help demo responses

## Not connected yet
- Live AI model/backend (no API key or server configured)
- Wake phrase / always-on listening
- Contacts lookup, direct calling, app/media control, reminders
- WhatsApp notification access
- Login, cloud memory, production privacy controls

These features require additional implementation, explicit Android permissions/consent, and in some cases a backend. Never put a private AI API key in the Android app.

## Build an APK
Open this folder in Android Studio on Windows, macOS or Linux. Install Android SDK Platform 35 and a compatible JDK (17). Let Gradle sync, then choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**. The debug APK is normally at `app/build/outputs/apk/debug/app-debug.apk`.

This workspace did not have Android SDK/Gradle installed, so an APK has not been compiled or tested here. This is project source, not an installable APK yet.
