VibeCanvas - AI-Based Music Moodboard Generator

Feel Every Mood, in Every Language

VibeCanvas is a full-stack AI-powered web application that generates personalized music playlists, visual moodboards, and custom cover art based on the user's mood and preferences.

Live Demo: https://vibecanvas.vercel.app

<img width="469" height="630" alt="Screenshot 2026-04-27 110808" src="https://github.com/user-attachments/assets/2002ef1c-7db7-40f8-8b05-47402266fde1" />

Features
Mood-based playlist generation — select your mood and get curated Spotify playlists
AI moodboards — OpenAI generates visual and textual content matching your vibe
Multi-language support — generate moodboards in English, Spanish, Korean, and more
Custom cover art — AI-generated album art based on mood and genre
Spotify OAuth 2.0 — secure login and real-time music data access
Save and share — save moodboards and share playlists with friends

| Layer           | Technology                |
| --------------- | ------------------------- |
| Frontend        | React.js, TailwindCSS     |
| Backend         | Node.js, Express.js       |
| AI              | OpenAI API (GPT + DALL·E) |
| Music           | Spotify Web API           |
| Auth            | Spotify OAuth 2.0         |
| Deployment      | Vercel                    |
| Version Control | Git, GitHub               |

# Getting Started

Prerequisites:

Node.js v18+
Spotify Developer Account
OpenAI API Key

# Installation

# Clone the repo
git clone https://github.com/YOUR_USERNAME/vibecanvas.git
cd vibecanvas

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env

# Environment Variables

SPOTIFY_CLIENT_ID=your_spotify_client_id

SPOTIFY_CLIENT_SECRET=your_spotify_client_secret

OPENAI_API_KEY=your_openai_api_key

# Run locally

npm run dev

## How It Works

1. User selects mood and language  
2. App fetches music via Spotify API  
3. OpenAI generates mood description and visuals  
4. Results are displayed as playlist + moodboard
   
## Known Issues

- Moodboard images may not render in deployed version  
- OAuth callback flow may fail in local environment
  
# Team
Meghana K C   
Romita Sarkar                                                                                                                 
Trisha Dev

Guided by: Dr. Srinivasa N & Mr. Pavan Kumar S P

Institution: Nitte Meenakshi Institute of Technology, Bengaluru

# Future Enhancements

Emotion detection via facial or voice recognition
Apple Music and YouTube Music integration
React Native mobile application
GAN-based advanced artwork generation
Voice assistant integration
Cloud storage with Firebase or AWS

License:

This project was developed as a course project for Full Stack Development (22CSG73) at NMIT, Bengaluru.
