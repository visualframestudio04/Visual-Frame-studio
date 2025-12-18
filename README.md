Run the portfolio generator script to scan `Portfolio/` and inject entries into `portfolio.html`.

Usage:
  node scripts/generate_portfolio.js

Requirements:
  - Node.js installed (>= 14)
  - Run from project root (where `portfolio.html` is located)

Notes:
  - The script looks for MP4s in `Portfolio/Video Editing/Horizontal` and `.../Vertical` and uses thumbnails from `video/Horizontal/Thumbnail` when available.
  - After running, open `portfolio.html` in a local server to test playback (e.g. VS Code Live Server or `python -m http.server 8000`).