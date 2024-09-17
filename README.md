# Video Segmentation Proof of Concept

This is a proof of concept application aimed at learning about video segmentation using FFmpeg. The application demonstrates how to divide videos into smaller chunks and serve them in HLS format (.m3u8).

## Features

- Upload videos to the server.
- Convert videos to HLS format using FFmpeg.
- Serve segmented video files for playback.

## Technologies Used

- **Frontend**: React, Vite, Video.js
- **Backend**: Node.js, Express, Multer, FFmpeg

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Install dependencies**:
   - For the client:
     ```bash
     cd client
     npm install
     ```
   - For the server:
     ```bash
     cd server
     npm install
     ```

3. **Run the server**:
   ```bash
   cd server
   npm start
   ```

4. **Run the client**:
   ```bash
   cd client
   npm run dev
   ```

5. **Access the application**:
   Open your browser and go to `http://localhost:3000` to view the application.

## Notes

- Ensure FFmpeg is installed and accessible in your system's PATH.
- The server runs on port 8000, and the client runs on port 3000 by default.

## Acknowledgments

- This project is a learning exercise to understand video processing and streaming technologies.
