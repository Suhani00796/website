#Preview
https://musichmm.netlify.app/music.html

# Multi-Media Lyrics Directory

A structured, client-side web application acting as a central directory for music tracking and visual lyric sheets. This project showcases media asset isolation, clean directory routing, and modular page design using semantic HTML5.

## Features

* **Centralized Hub Architecture**: Features a main landing menu providing direct routing to decoupled individual song directories.
* **Synchronized Media Controls**: Integrated customized HTML5 video and audio components featuring loop and muted properties for seamless background playback.
* **Responsive Asset Isolation**: Modular folder layout ensures that specific projects carry their respective graphical and auditory assets locally, minimizing cross-directory dependencies.

## Technical Stack

* **Markup**: HTML5 (Semantic elements, local media routing)
* **Styling**: Inline and presentational attributes for cross-browser visual scaling
* **Typography**: Formatted plain-text block containers (`<pre>`) to preserve structural integrity of text configurations

## Directory Architecture

The repository isolates project scopes inside dedicated subdirectories while maintaining global navigation assets at the root layer.

```text
WEBSITE/
│
├── dream_project/          # Isolated scope for "Dream On" assets
│   ├── dream.png           # Album artwork asset
│   ├── dreamon.html        # Track lyric representation page
│   ├── dreamon.mp3         # Background audio asset
│   ├── dreamon.mp4         # Background video loops
│   └── index.html          # Sub-menu and media display controller
│
├── wildfire_project/       # Isolated scope for "Wildfire" assets
│   ├── index1.html         # Sub-menu and media display controller
│   ├── wildfire.html       # Track lyric representation page
│   ├── wildfire.mp3        # Background audio asset
│   └── wildfire.png        # Album artwork asset
│
├── favicon.png             # Global cross-origin shortcut icon
└── music.html              # Core directory master entry point
