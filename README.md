# Second Brain Capture

A Progressive Web App (PWA) for capturing content from YouTube and web articles into your Second Brain knowledge management system.

## What it does

1. **Paste a URL** — YouTube video or any web article
2. **Content is extracted automatically** — full transcript or article text
3. **Save to Google Drive** — drops into your SecondBrain/Capture/ folder
4. **Second Brain processes it** — Cowork pipeline extracts knowledge atoms

## Install on iPhone

1. Open this page in **Safari** on your iPhone
2. Tap the **Share** button (square with arrow)
3. Tap **"Add to Home Screen"**
4. Open the app and tap ⚙️ to add your API keys

## Setup

You need two API keys:

- **YouTube Transcript API** — Get a free key at [youtube-transcript.io](https://youtube-transcript.io)
- **Anthropic API** — Get a key at [console.anthropic.com](https://console.anthropic.com)

Enter both keys in the app's Settings (⚙️ icon).

## How it works

| Content type | API used | What you get |
|---|---|---|
| YouTube videos | youtube-transcript.io | Full video transcript |
| Web articles | Anthropic API (Claude) | Clean article text |

Output files include metadata (source URL, title, date, word count) formatted for the Second Brain pipeline.

## Part of Second Brain

This app is the mobile capture component of the [Second Brain](https://github.com/YOUR_USERNAME/second-brain) knowledge management system built on Claude Cowork.
