# Minimal Jetpack Compose App

A minimal Android app built with Kotlin and Jetpack Compose.

## Build

Install JDK 21 and Android SDK Platform 36. Set the SDK location in the ignored
`local.properties` file:

```properties
sdk.dir=/path/to/Android/Sdk
```

Build the debug APK with:

```shell
./gradlew :app:assembleDebug
```

In VS Code, install the recommended Kotlin and Gradle extensions and reload the
window after the Gradle project import completes.
