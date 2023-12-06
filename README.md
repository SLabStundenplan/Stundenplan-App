# Stundenplan-App
ios app für den Stundenplan

# Building
- zum Bauen benötigt man **MacOS**
- man muss **XCode** und **Rust** installieren
- für Rust muss man die ios-targets hinzufügen:
  - führe ```rustup target add aarch64-apple-ios x86_64-apple-ios aarch64-apple-ios-sim``` in der console aus
- führe ```cargo tauri ios init``` in der console aus

# Debugging
führe ```cargo tauri ios dev``` in der console aus
