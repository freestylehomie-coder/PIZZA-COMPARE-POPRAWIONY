# PizzaCompare (minimal)

Minimalna apka Android (Kotlin), bez Compose i bez Material, tak żeby build w GitHub Actions przechodził.

## Jak uruchomić build w GitHub
1. Zrób repo i branch `main`.
2. Skopiuj cały katalog `.github/workflows/android.yml` do repo (jest już w tym ZIPie).
3. Commit & push na `main`. Workflow sam zbuduje APK i dołączy artefakt `app-debug.apk`.

## Lokalnie (opcjonalnie)
- Android Studio lub `gradle 8.7`: `gradle assembleDebug`
- APK: `app/build/outputs/apk/debug/app-debug.apk`
