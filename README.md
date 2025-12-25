# Android UI Practice — View-based Project

A small learning repository for practicing Android UI development using Jetpack Compose. Created by a software engineering undergraduate to track progress and experiments; not a production application.

## Purpose

This repository documents step-by-step practice with Android UI patterns and Compose layouts. It is intended as a study journal and sandbox for experimenting with components and app structure.

## What I am practicing

- Jetpack Compose basics (Layouts, State, Theming)
- Composable architecture and component composition
- Material 3 components and theming
- Navigation and simple state management
- Building and testing UI on emulator and device

## Tech stack

- Kotlin
- Android SDK
- Gradle (Kotlin DSL)

## Project structure (brief)

- `app/` — Android application module (source, resources, manifest)
- `app/src/main/java/...` — Kotlin source (activities, composables)
- `app/src/main/res/` — layouts, drawables, values and themes
- Gradle files at project root configure build and dependencies

## How to run

1. Open the project in Android Studio (Arctic Fox or later recommended).
2. Let Android Studio sync Gradle and download dependencies.
3. Run on an emulator or connected device via Run ▶︎.

Alternatively, from the project root (Windows PowerShell):

```powershell
.\gradlew.bat assembleDebug
.\gradlew.bat installDebug
```

## Learning goals

- Build a set of small Compose screens demonstrating layout patterns
- Improve understanding of Compose state and lifecycle
- Learn basic navigation and theming best practices
- Gain confidence shipping simple, testable UI code

## Notes

- This is a learning repository. Code may be experimental, incomplete, or reorganized frequently. Issues and TODOs are expected.


