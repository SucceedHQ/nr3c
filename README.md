# NR3C

**Cross-platform mobile utility application.**

A Capacitor-powered mobile application that wraps web technologies into a native Android experience. Built with HTML, CSS, and JavaScript, packaged with Capacitor for platform-native access.

## Features

- Cross-platform compatibility (Android, iOS via Capacitor)
- Native device feature access (camera, storage, etc.)
- Lightweight and fast
- Web-first development with native deployment

## Tech Stack

- **Framework:** Capacitor 3+
- **Web Runtime:** HTML5, CSS3, JavaScript
- **Android:** Java bridge layer
- **Build:** npm + Capacitor CLI

## Getting Started

```bash
# Install dependencies
npm install

# Build the web assets
npm run build

# Sync with native platforms
npx cap sync

# Open in Android Studio
npx cap open android
```

## Project Structure

```
â”œâ”€â”€ android/          # Native Android project
â”œâ”€â”€ www/              # Web app build output
â”œâ”€â”€ resources/        # App icons and splash screens
â”œâ”€â”€ capacitor.config.json
â”œâ”€â”€ index.html        # Entry point
â””â”€â”€ package.json
```

## License

MIT
