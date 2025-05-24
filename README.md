# Minecraft Dodge Game

A mobile-friendly web game where you control Steve and dodge lava chickens.

## How to Deploy and Play on iPhone

### Option 1: Using a Web Server

1. Upload all files to a web server:
   - game.html
   - manifest.json
   - sw.js
   - icon.png
   - bgm.MP3

2. Access the game via the web server URL on your iPhone.

3. To add to home screen:
   - Open the game in Safari
   - Tap the Share button (box with arrow)
   - Select "Add to Home Screen"
   - Name your app and tap "Add"

### Option 2: Using Local Network

1. Set up a local web server on your computer:
   - Using Python: `python -m http.server 8000` in the game directory
   - Or use tools like XAMPP, WAMP, or Live Server in VS Code

2. Make sure your iPhone is on the same WiFi network as your computer

3. Find your computer's local IP address (e.g., 192.168.1.x)

4. On your iPhone, open Safari and navigate to:
   `http://[your-computer-ip]:8000/game.html`

5. Add to home screen as described in Option 1

## Files Included

- `game.html` - The main game file
- `manifest.json` - Web app configuration
- `sw.js` - Service worker for offline functionality
- `icon.png` - App icon (replace with your own 192x192 PNG)
- `bgm.MP3` - Background music

## Game Controls on Mobile

- Tap to start the game
- Swipe left/right to move Steve
- Tap to restart after game over