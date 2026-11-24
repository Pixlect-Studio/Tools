# Pixlect Tools

A browser-based creative workspace by Pixlect Studio, hosted on GitHub Pages.

## Pages

- `index.html` — Pixlect homepage and app launcher.
- `main.html` — the complete workspace, including TXT, presentations, video, PDF, utilities, Pixlect AI and Studio Updates.

## Studio Updates

The Updates page is a public, read-only news feed. It fetches announcements from:

1. `https://pixlect-studio.github.io/News/`
2. `https://news-67-default-rtdb.firebaseio.com/.json`

The page refreshes when opened and periodically while visible. It merges duplicate titles, sorts dated posts newest-first, and excludes entries marked as member-only/private. If neither source allows browser access (for example, due to network or CORS restrictions), the page shows an unavailable message and links to the official News page rather than displaying invented stories.

## Deployment

Upload `index.html` and `main.html` to the `Tools/` directory in the GitHub Pages repository. The expected address is:

`https://pixlect-studio.github.io/Tools/`

Keep both files in the same directory. No login, account server, or chat service is required.

## Local data

Workspace files and preferences are stored in the current browser using local storage. They do not automatically sync between browsers or devices. Groq API keys saved in browser storage are accessible to scripts running on the same site; a server-side proxy is safer for public deployments.

## Ownership

Pixlect Tools is proprietary Pixlect Studio work. See [`SECURITY.md`](./SECURITY.md) for security reporting and ownership restrictions. No open-source licence is granted by this README.
