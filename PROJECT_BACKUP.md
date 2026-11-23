# ADAM MK CHAT PROJECT BACKUP

## Project Name
ADAM MK CHAT

## Description
Global social networking and messaging platform where users can connect, chat, share media, and stay updated.

## Design & Theme
- Primary Theme: Blue and White (with optional Dark Mode support)
- Responsive Mobile-First Layout

## Platforms
- Web App (Progressive Web App - PWA)
- Android App (APK via Capacitor)

## Authentication & Registration
- Email Registration & Verification
- Phone Number Registration & OTP Verification
- Secure Login & Logout

## Core Features
- User Profiles (Name, Username, Bio, Avatar, Stats)
- 24-Hour Status & Stories (Auto-expire after 24 hours)
- Private Chat & Group Chat
- Voice Messages
- Audio Calls & Video Calls
- Friends, Followers & Following
- Posts (Text, Photos, Videos, and Music Sharing)
- Likes, Comments, and Sharing
- Real-Time Notifications
- Block Users & Report Content/Users
- Privacy & Security Settings

## Supported Languages
- English
- Hausa
- French
- Arabic

## Technology Stack
- **Version Control & Hosting:** GitHub & GitHub Pages
- **Backend & Database:** Firebase (Authentication, Firestore/Realtime Database)
- **Media Storage:** Cloudinary (Images, Videos, Audio/Music, Voice Notes)
- **Mobile Packaging:** Capacitor (Web to Android APK)

## Recommended Project Structure
```text
adam-mk-chat/
├── index.html            # Main application UI & logic
├── manifest.json         # PWA configuration (icons, name, display mode)
├── sw.js                 # Service Worker for offline support & PWA install
├── firebase-config.js    # Firebase & Cloudinary configuration
├── capacitor.config.json # Capacitor config for Android APK build
├── README.md             # Project overview & setup guide
└── PROJECT_BACKUP.md     # Project backup & roadmap
