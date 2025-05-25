# Musically Yours

A music-centric dating platform where users connect through shared musical tastes. Built with the MERN stack (MongoDB, Express, React, Node.js).

## Features

- User profiles with relationship status and favorite songs
- Dynamic connections list with tags (soulmate, crush, etc.)
- Smart matching algorithm based on music preferences
- Real-time chat with text, voice, and song sharing
- Shared listening sessions for virtual dates
- Public relationship highlights and dedications
- Spotify integration for music playback and analysis

## Tech Stack

- **Frontend**: React, Socket.IO Client, WebRTC
- **Backend**: Node.js, Express, Socket.IO
- **Database**: MongoDB Atlas
- **Authentication**: JWT, Spotify OAuth
- **Real-time Communication**: Socket.IO, WebRTC
- **Music Integration**: Spotify Web API, Spotify Web Playback SDK

## Prerequisites

- Node.js (v16 or higher)
- MongoDB Atlas account
- Spotify Developer account
- npm or yarn

## Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   npm run install:all
   ```
3. Create a `.env` file in the server directory with the following variables:
   ```
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   SPOTIFY_CLIENT_ID=your_spotify_client_id
   SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
   ```
4. Create a `.env` file in the client directory:
   ```
   REACT_APP_API_URL=http://localhost:5000
   REACT_APP_SPOTIFY_CLIENT_ID=your_spotify_client_id
   ```

## Development

To start the development servers:

```bash
npm start
```

This will start both the client (port 3000) and server (port 5000).

## Project Structure

```
musically-yours/
├── client/                 # React frontend
├── server/                 # Node.js backend
├── package.json           # Root package.json
└── README.md             # Project documentation
```

## License

MIT 