# Second Brain Capture

A Progressive Web App (PWA) for capturing content from YouTube and web articles into your Second Brain knowledge management system.

## What it does

1. **Paste a URL** — YouTube video or any web article
2. **Content is extracted automatically** — full transcript or article text via Claude
3. **Save to Google Drive** — drops into your SecondBrain/Capture/ folder
4. **Second Brain processes it** — Cowork pipeline extracts knowledge atoms

## Install on iPhone

1. Open this page in **Safari** on your iPhone
2. Tap the **Share** button (square with arrow)
3. Tap **"Add to Home Screen"**
4. Open the app and tap ⚙️ to add your API key

## Setup

You need one API key:

- **Anthropic API** — Get a key at [console.anthropic.com](https://console.anthropic.com)

This single key handles everything — YouTube transcripts and article extraction. Enter it in the app's Settings (⚙️ icon).

## How it works

| Content type | What happens | What you get |
|---|---|---|
| YouTube videos | Claude fetches the page and extracts captions | Full video transcript |
| Web articles | Claude fetches and cleans the page content | Clean article text |

Output files include metadata (source URL, title, date, word count) formatted for the Second Brain pipeline.

## Cost

Each capture uses a small amount of Anthropic API credits — typically a few cents per URL. No other subscriptions or API keys needed.

## Part of Second Brain

This app is the mobile capture component of the Second Brain knowledge management system built on Claude Cowork.
