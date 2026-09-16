# Twimba

A lightweight, responsive Twitter/X clone built with vanilla JavaScript, HTML5, and CSS3. Twimba simulates a microblogging feed where users can post tweets, interact with existing posts through likes and retweets, and expand replies.

---

## Features

- **Post New Tweets:** Add new tweets directly to the top of the feed with unique IDs.
- **Input Validation & UX:** Prevents empty tweets and automatically clears the input area after submission.
- **Like & Retweet Toggles:** Dynamic counter updates and visual state changes for likes and retweets without reloading the page.
- **Collapsible Thread Replies:** Expand and collapse reply threads for individual posts.
- **Data-Driven UI:** UI updates dynamically reflect state changes in the underlying data objects.

---

## Project Structure

```text
├── index.html       # Markup structure and app layout
├── index.css        # Styling and responsive design
├── index.js         # Core application logic and event handling
├── data.js          # Initial tweet dataset
└── images/          # User avatars, icons, and graphic assets
