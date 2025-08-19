# IT‑20: URL Shortener React App

A React-based application for shortening URLs and viewing usage statistics.

---

##  Features
- Shortens long URLs into a compact, shareable form.
- Provides usage stats for each shortened URL (e.g., number of clicks).
- Intuitive single-page interface (under `App.js`).
- Organized for scalability—separate components and services:
  - `UrlShortener.js` (URL input & generation)
  - `UrlStatisticsPage.js` (viewer for stats)
  - `urlService.js` (handles API interactions)
  - `loggingMiddleware.js` (for analytics or monitoring)
- App styling managed via `App.css`, with supporting styles in `index.css`.
- Includes unit tests (`App.test.js` and `setupTests.js`) and performance metrics (`reportWebVitals.js`).

---

##  Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/RishavLaha3/IT-20.git
   cd IT-20
