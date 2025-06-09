# Oregon Trail Free

A free, modern implementation of the classic Oregon Trail game for Android, built with Kotlin and Jetpack Compose.

## Features
- Resource management (food, bullets, clothing, wagon parts, medical supplies, cash)
- Decision making (profession, pace, river crossings, trading)
- Random events and challenges
- Enhanced hunting mini-game with touch controls and animations
- Interactive map with zoom, pan, and landmarks
- Detailed party management with health status and customization
- Dynamic weather system with visual effects
- Trading and bartering system
- Achievements and leaderboards
- Tutorial and help system
- Event log/journal
- Game state persistence with Room database
- Polished animations and transitions

## Building with Android Studio

1. **Prerequisites**
   - Android Studio Hedgehog (2023.1.1) or newer
   - JDK 17 or newer
   - Android SDK with minimum API level 21

2. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/oregon-trail-free.git
   ```

3. **Open in Android Studio**
   - Launch Android Studio
   - Select "Open an Existing Project"
   - Navigate to and select the cloned repository folder

4. **Sync Project**
   - Wait for the initial Gradle sync to complete
   - If prompted, install any missing SDK components

5. **Build and Run**
   - Connect an Android device or start an emulator
   - Click the "Run" button (green play icon) or press Shift+F10
   - Select your target device and click "OK"

## Project Structure
- `app/src/main/java/com/example/oregontrail/`
  - `data/` - Room database, repositories, and data models
  - `game/` - Game logic and view models
  - `ui/` - Jetpack Compose UI components and screens
  - `MainActivity.kt` - Entry point and navigation setup

## Technical Details
- Minimum SDK: API 21 (Android 5.0)
- Target SDK: API 34 (Android 14)
- Language: Kotlin
- Architecture: MVVM with Clean Architecture principles
- UI Framework: Jetpack Compose
- Database: Room
- Dependency Injection: Hilt (optional)
- Navigation: Compose Navigation

## Contributing
Contributions are welcome! Please feel free to submit pull requests.

## License
This project is open source and available under the MIT License.
