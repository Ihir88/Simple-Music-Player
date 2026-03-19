# Simple-Music-Player
# Music Player - Android Web App

A beautiful, feature-rich music player built with Next.js and React for mobile devices. Can be installed as a Progressive Web App (PWA) on Android devices.

## Features

- **🎵 Music Playback** - Play, pause, skip forward/backward through a curated playlist
- **🎚️ Volume Control** - Adjust volume with an interactive slider
- **🎛️ Equalizer** - Fine-tune audio with Bass, Mid, and Treble controls
- **🔀 Shuffle Mode** - Randomize playback order
- **🔁 Repeat Modes** - Repeat all songs or repeat single song
- **❤️ Favorites** - Save your favorite songs and quickly access them
- **🔍 Search & Filter** - Find songs by title or artist name
- **💾 Persistent Storage** - Your favorites and volume settings are saved locally
- **📱 PWA Ready** - Installable on Android as a standalone app
- **🎨 Glassmorphism Design** - Modern, responsive UI with smooth animations

## Installation on Android

### As a Web App (Recommended)
1. Open this link in your Android browser (Chrome, Firefox, etc.)
2. Tap the menu button (three dots)
3. Select "Install app" or "Add to Home screen"
4. The app will appear on your home screen like a native app

### Local Development
```bash
# Install dependencies
pnpm install

# Run development server
pnpm dev

# Build for production
pnpm build
```

## Controls

### Playback Controls
- **Play/Pause** - Center button to play or pause music
- **Next/Previous** - Skip to next or previous track
- **Progress Bar** - Tap anywhere on the progress bar to seek

### Features
- **Shuffle Button** - Top-left: Click to enable/disable shuffle mode (highlights when active)
- **Repeat Button** - Top-right: Cycle between off → repeat all → repeat one
- **Volume Slider** - Adjust volume between 0-100%
- **Search** - Click search icon to find songs by title or artist
- **Favorites** - Click heart icon to see only favorite songs
- **Equalizer** - Click settings icon to adjust Bass, Mid, and Treble

## Playlist

The app includes 12 pre-loaded songs. You can:
- **Click any song** to play it immediately
- **Heart icon** to add/remove from favorites
- **Search** to filter songs
- **View Favorites** for quick access to saved songs

## Keyboard Shortcuts (Desktop/Dev)
- **Space** - Play/Pause (if you add keyboard support)
- **→** - Next track
- **←** - Previous track

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14.1+
- Samsung Internet 14+

## Technical Stack

- **Next.js 16** - React framework with server components
- **React 19** - UI library
- **Tailwind CSS 4** - Styling
- **Lucide React** - Icons
- **Web Audio API** - Audio processing (ready for future enhancements)
- **Service Worker** - Offline support

## Settings Storage

The app saves your preferences locally:
- **Favorites** - Stored in localStorage as JSON
- **Volume** - Persisted between sessions

## Future Enhancements

- Actual Web Audio API integration for Equalizer
- Custom playlist creation
- Drag and drop queue reordering
- Dark/Light theme toggle
- Lyrics display
- Song recommendations

## License

MIT

## Support

For issues or feature requests, please open an issue in the repository.
