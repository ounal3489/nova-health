# Nova - Claude Code Project Configuration

## Project Overview
Nova (formerly FemBoard) is a comprehensive women's health tracking iOS app (SwiftUI, MVVM, iOS 17+).
Language: Turkish (tr_TR), global expansion planned. Bundle ID: com.nova.app.

## Tech Stack
- Swift 5.9 / SwiftUI / Swift Charts
- MVVM architecture
- UserDefaults for local storage (SwiftData migration planned)
- StoreKit 2 for premium subscriptions
- HealthKit integration
- XcodeGen for project generation

## Project Structure
- `FemBoard/App/` - App entry point and state management
- `FemBoard/Models/` - Data models
- `FemBoard/ViewModels/` - Stores + InsightEngine
- `FemBoard/Views/` - SwiftUI views organized by feature
- `FemBoard/Services/` - NotificationService, HealthKit, PDF, Premium
- `FemBoard/Utils/` - Theme, colors, extensions

## Build
```bash
xcodegen generate
open Nova.xcodeproj
```

## Conventions
- All UI text in Turkish (localization planned)
- 5 themes: PinkPurple, Dark, Pastel, Ocean, Sunset
- Phase colors: Menstrual #D94D59, Follicular #66BF8C, Ovulation #F2993F, Luteal #8C73CC

## Permissions
- Full read/write access to all project files
- Can create, edit, delete any file in the project
- Can run build commands and scripts
