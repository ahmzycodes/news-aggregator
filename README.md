# News Aggregator

A minimal and responsive news aggregator built with HTML, CSS, and JavaScript. It fetches the latest political news from Nigeria, Poland, and around the world using the [NewsData.io API](https://newsdata.io/).

## Features
- Live news fetching from NewsData.io API
- Country-specific sections (Nigeria, Poland)
- Translation of Polish news headlines and descriptions to English
- Responsive layout for desktop and mobile
- Graceful fallback for articles without images

## Setup
No build tools needed — this is a static site.

### Steps to Deploy on GitHub Pages
1. Clone or upload this repository to GitHub.
2. Go to **Settings > Pages** in the repository.
3. Under **Source**, select the branch (usually `main`) and root folder.
4. Save and wait a few seconds.
5. Your site will be live at: `https://yourusername.github.io/your-repo-name/`

## Notes
- Replace the `apiKey` in the script with your own from NewsData.io if you fork or reuse this.
- This app uses a free Google Translate endpoint to auto-translate Polish news to English.

## License
This project is open source and free to use or modify.
