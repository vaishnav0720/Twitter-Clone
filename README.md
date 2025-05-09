# Twitter Clone

## Description

This project is a simple Twitter/X clone built with HTML and Tailwind CSS.  
It demonstrates a modern, responsive layout with a sidebar, main feed, and right-side widgets.  
Users can see trending topics, suggested profiles, and a feed of posts with images and videos.  
The UI is designed to closely resemble the Twitter web interface, focusing on layout and style rather than backend functionality.
```
## Features

- Responsive Twitter-like UI built with Tailwind CSS
- Sidebar navigation with icons and labels
- "Post" button for creating new tweets
- User profile section with avatar and username
- "What's Happening" input box for posting updates
- Trending topics and "Who to Follow" suggestions
- Posts with images, videos, and interactive icons (like, comment, retweet, views)
- Sticky sidebar and trending sections for better UX
```
## Project Structure

- **css/**
  - `input.css` – Tailwind source CSS
  - `output.css` – Compiled Tailwind CSS
- **people/** – User and profile images
  - `1.png`, `2.png`, `3.png`, `b7.jpg`, `f2.png`, `f6.png`
- **Post/** – Post images and videos
  - `1.mp4`, `b1.jpg`, `b6.jpg`
- `index.html` – Main HTML file
- `package.json` – Project metadata and scripts
- `tailwind.config.js` – Tailwind CSS configuration
- `README.md` – Project documentation

## Demo

Open `index.html` in your browser to view the Twitter Clone UI.

---

**How to run Tailwind CSS build:**
```sh
npm install
npm run build
```

This will watch for changes and update `css/output.css` automatically.

---
**Live Demo:** [Click Here](https://vaishnav0720.github.io/Twitter-Clone/)
