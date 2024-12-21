# Expo CLI Android Build Failure: Android SDK Build Tools Version Mismatch

This repository demonstrates a common bug encountered when building Android APKs using Expo CLI. The issue stems from a version mismatch between the Android SDK build tools version required by Expo and the version installed on your system.

## Problem

The Expo CLI build process fails, producing an error message indicating that the installed Android SDK build tools version is incompatible.  This usually occurs after updating either the Android SDK or the Expo CLI itself.

## Solution

The solution involves ensuring that the Android SDK build tools version meets Expo's requirements. This might involve updating the build tools to a compatible version or, in some cases, downgrading them.