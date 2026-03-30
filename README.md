# StudyLoop

StudyLoop is a minimal voice-loop tool designed for memorization, language learning, and spaced repetition through audio playback.

Record a phrase, sentence, or concept and let it loop continuously so you can passively reinforce memory while studying.

## Features

• Record audio directly in the browser
• Instant loop playback
• Minimal distraction-free interface
• Circular progress timer
• Installable as a mobile web app (PWA)
• Works on iPhone when added to the home screen

## How It Works

1. Press **Record**
2. Speak the phrase you want to memorize
3. Press **Stop**
4. Press **Play**

The audio will loop continuously.

## Installation (Local Development)

Clone the repository:

```
git clone https://github.com/YOURUSERNAME/studyloop.git
```

Open the project folder:

```
cd studyloop
```

Open `index.html` in a browser.

Note: Microphone access requires HTTPS in most browsers.

## Deploying with GitHub Pages

1. Push the project to GitHub
2. Go to **Repository → Settings → Pages**
3. Select:

```
Branch: main
Folder: /root
```

Your site will be available at:

```
https://YOURUSERNAME.github.io/studyloop/
```

## Install as an App (iPhone)

Open the site in Safari, then:

Share → Add to Home Screen

StudyLoop will launch in full screen like a native app.

## Tech

HTML
CSS
Vanilla JavaScript
Web Audio API
MediaRecorder API
Progressive Web App (PWA)

## License

MIT License
