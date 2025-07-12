# BeatBreeze

BeatBreeze is a static, interactive web-based music player. It allows users to play songs from a curated list and provides a simple way to manage your own music library.

## Features

- Play songs directly from your browser
- Add or remove songs by updating the music file and configuring the song locations in the JavaScript code

## Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Edge, Safari, etc.)

### Setup Instructions

1. **Clone the repository**
    ```bash
    git clone https://github.com/hetrank/Beat-Breeze.git
    ```

2. **Add your songs**
    - Place your music files in the designated "music" directory.
    - Supported file formats: ".mp3".

3. **Configure song locations**
    - Open the relevant JavaScript file (e.g., "script.js" or as specified in your project).
    - Update the file paths for each song to match their location in the "music" folder.
    - Example:
      ```javascript
      const songs = [
        { name: "Song 1", artist: "abc", filepath:"Music/song1.mp3", coverpath: "cover/song1.jpg"},
        { name: "Song 2", artist: "def", filepath:"Music/song2.mp3", coverpath: "cover/song2.jpg"}
      ];
      ```

4. **Run the app**
    - Simply open the "index.html" file in your browser.

## Usage

- Select a song from the playlist to start playing.
- Use the player controls to pause, resume, or switch songs.
