# Expo Android Build Failure: Unhelpful Gradle Error

This repository demonstrates a bug encountered when building an Android APK using the Expo CLI. The build process fails with a generic "FAILURE: Build failed with an exception." message, providing limited debugging information.  The issue is specific to Android; iOS builds succeed without problems.

## Bug Description

The primary symptom is a failed Android build, with the error log from Gradle providing insufficient detail to pinpoint the root cause. This suggests a potential configuration issue within the Gradle build system or a conflict between project dependencies.

## Reproduction Steps

1. Clone this repository.
2. Navigate to the project directory.
3. Attempt to build the Android APK using `expo build:android`.
4. Observe the build failure with the unhelpful error message.

## Expected Behavior
A successful Android APK build.

## Actual Behavior
An Android build failure with a generic Gradle error message that is not conducive to debugging.

## Solution
See `bugSolution.js` for a potential solution (if found).  The solution may involve carefully reviewing the full Gradle error log and investigating potential conflicts between dependencies, or updating the expo-cli and related packages.