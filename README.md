# Search Your YouTube Playlists

A privacy-focused web app to search across all your YouTube playlists. No server needed - everything runs in your browser.

**Live App:** _(GitHub Pages URL will be here after deployment)_

## Features

- 🔍 Search across all your playlists instantly
- 🔒 Your data never leaves your browser
- 📱 Works on desktop and mobile
- 📲 Install as an app (PWA)
- 🔄 Works offline with cached data

## Setup Your Own

1. Fork this repository
2. Enable GitHub Pages (Settings → Pages → Deploy from main branch)
3. Create OAuth credentials in [Google Cloud Console](https://console.cloud.google.com/):
   - Enable YouTube Data API v3
   - Create OAuth 2.0 Client ID (Web application)
   - Add your GitHub Pages URL to authorized redirects
4. Update `CLIENT_ID` in `index.html`
5. Visit your GitHub Pages URL and sign in

## Privacy

- No backend server
- No analytics or tracking  
- OAuth tokens stay in your browser
- All data stored locally in IndexedDB

## License

MIT - Use freely for personal or commercial projects.