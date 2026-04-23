# ThreadTalk

ThreadTalk is a Spider-Man-inspired text-to-speech web app built with the browser Web Speech API.
It lets users type text, choose a voice, adjust speed and pitch, and play speech with live status feedback in a custom themed interface.

## Live Project Summary

- Project type: Frontend web app (HTML, CSS, JavaScript)
- Core API: Web Speech API (SpeechSynthesis)

## Features

- Text-to-speech playback using native browser voices
- Dynamic voice list loading from the browser
- Adjustable speech rate and pitch controls
- Real-time character counter
- Status indicator for ready, speaking, stopped, and error states
- Custom black/red/blue comic-inspired UI theme
- Responsive layout for desktop and mobile
- Spider visual glow effect during active speech playback

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Browser Web Speech API

## Project Structure

```text
app.js
index.html
spider.png
style.css
README.md
```

## Getting Started

### Option 1: Open directly

1. Clone or download this repository.
2. Navigate to the completed folder.
3. Open index.html in a modern browser.

### Option 2: Run with a local server (recommended)

Using VS Code Live Server or any static server:

1. Open the repository in VS Code.
2. Right-click completed/index.html.
3. Choose Open with Live Server.

## How to Use

1. Enter text in the Your Text box.
2. Select a voice from the Voice dropdown.
3. Adjust Speed and Pitch sliders.
4. Click Speak to start playback.
5. Click Stop to cancel playback.

## Browser Support

Best experience is on Chromium-based browsers:

- Google Chrome
- Microsoft Edge

Notes:

- Available voices vary by operating system and browser.
- Some browsers may delay voice loading until the voiceschanged event fires.

## Credits

- Built by Shrika Thota
- Inspired by Spider-Verse visual style

Check out the [deployed](https://threadtalk-text-to-speech.netlify.app/) version 
