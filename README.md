# OVAN Camera 4.3.0

OVAN Camera Android project.

## GitHub Actions

The project includes a GitHub Actions workflow at:

`.github/workflows/ovan-camera-apk.yml`

The workflow:

- Uses Ubuntu 24.04
- Uses JDK 17
- Uses `android-actions/setup-android@v4`
- Installs Android API 35 and Build Tools 35.0.0
- Uses Gradle 8.9
- Builds `app-debug.apk`
- Uploads the APK as the `OVAN-Camera-debug-apk` artifact

### Build manually on GitHub

1. Upload/extract this project to a GitHub repository.
2. Make sure the default branch is `main`.
3. Open **Actions**.
4. Select **Build OVAN Camera APK**.
5. Click **Run workflow**.
6. After a successful build, open the workflow run and download **OVAN-Camera-debug-apk** from **Artifacts**.

## Project configuration

- Application ID: `com.ovan.camera`
- Version: `4.3.0`
- Minimum SDK: 21
- Target SDK: 35
- Compile SDK: 35
- Android Gradle Plugin: 8.7.3
- Gradle: 8.9
- Java: 17
