# Public Assets Directory

This folder contains static assets and modular JavaScript code for the video editing application.

## Directory Structure

- **`js/`** - JavaScript modules and utility functions
  - Place modular JavaScript code here to keep the main application organized
  - Examples: video processing utilities, UI components, data handlers

- **`ffmpeg/`** - FFmpeg-related files and WebAssembly
  - Place FFmpeg.wasm files here
  - FFmpeg configuration and preset files
  - Video processing workflows

- **`assets/`** - Static assets
  - Images, icons, fonts
  - CSS files
  - Other static resources

- **`workers/`** - Web Workers
  - Background processing scripts
  - Video processing workers
  - File handling workers

## Usage

All files in this directory are publicly accessible and can be referenced in your React application using relative paths from the public folder.

Example:
```javascript
// To reference a file in public/js/video-utils.js
import('/js/video-utils.js')

// To reference FFmpeg
const ffmpegPath = '/ffmpeg/ffmpeg-core.wasm'
```