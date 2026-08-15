# Apna_Video_Call

A lightweight web-based video calling application built with JavaScript, HTML and CSS. Apna_Video_Call provides peer-to-peer video/audio calling and basic collaboration features for small group or one-to-one meetings.

## Features
- One-to-one and/or small-group video calls (WebRTC-based)
- Audio and video device selection
- Chat during calls
- Optional screen sharing (if implemented)
- Room creation / join by link or code (if implemented)

## Stack
- Language(s): JavaScript, HTML, CSS
- Framework / runtime: browser-front-end + Node.js server (if server exists)
- Notable libraries (examples — replace with actual dependencies from package.json):
  - Simple peer/WebRTC helper (e.g., simple-peer, peerjs) or native WebRTC API
  - Socket.IO or WebSocket for signaling (if used)
  - Express (Node.js) for a lightweight signaling server (if present)
  - Any UI library used (vanilla, or e.g., React / Vue / Svelte — replace accordingly)

## Quickstart — run locally
Prerequisites
- Node.js (v14+ recommended) and npm or yarn
- A modern browser (Chrome/Firefox/Edge)
- (Optional) Public STUN/TURN server credentials for reliable connectivity across NATs

Install and run
```bash
# clone
git clone https://github.com/Harman-Kour/Apna_Video_Call.git
cd Apna_Video_Call

# install
npm install

# run development server (replace with actual script name from package.json)
npm run dev

# or production start
npm start
