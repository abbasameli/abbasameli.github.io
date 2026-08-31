# ReadOut

Free, instant text-to-speech in the browser. Paste a link or any text, pick a voice, and listen — no accounts, no paywall, no tracking.

Live at [narrately.net](https://narrately.net) (and at abbasameli.github.io while DNS propagates).

## What it is

A single-file static site (`index.html`) that turns articles and text into speech using the visitor's own browser speech engine (Web Speech API). Nothing is stored server-side.

## Features

- Fetch article text from any public URL (Jina Reader plus fallback proxies)
- Paste raw text directly
- Three voice options with preview
- Speed control (0.75×–2×)
- Play / pause / resume / stop with progress tracking
- Handles long reads (15+ minutes) via chunked playback

## Privacy

All speech synthesis happens on the user's device. Article fetching goes through public reader/proxy services; no data is logged or retained by this site.
