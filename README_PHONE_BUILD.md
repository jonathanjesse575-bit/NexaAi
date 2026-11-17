# Build NEXA AI APK using your Android phone

1. Extract this ZIP. The folder named `NexaAI` contains the Android project.
2. Sign in or create a GitHub account at https://github.com.
3. Create a repository named `NexaAI-Android`. A public repository is the simplest option for free GitHub Actions. Do not upload API keys, passwords, or private information.
4. Upload the *contents* of the extracted `NexaAI` folder to the repository root. Include the hidden `.github` folder. If needed, open GitHub in Chrome and enable **Desktop site** to upload hidden folders/files.
5. Open the repository's **Actions** tab. Choose **Build NEXA AI APK** and tap **Run workflow** if no build has started automatically.
6. When the run finishes successfully, open it, find **Artifacts**, and download `NEXA-AI-debug-apk`.
7. Extract that artifact ZIP and tap `app-debug.apk` to install it. Android may ask you to allow installs from your browser or file manager. Only allow this for a file you trust.

This creates a debug/test APK, not a Play Store release. The current app is an early prototype: the live AI backend is not connected, and future features such as wake-word activation and WhatsApp notification previews are not implemented. Never put an AI API key in the app or a public repository.
