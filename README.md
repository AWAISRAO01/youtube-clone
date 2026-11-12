# YouTube.com Clone

A static, responsive front-end clone of the YouTube homepage built using pure HTML5 and CSS3. This project replicates YouTube's core layout, navigation bars, video grid, and interactive hover tooltips.

## 🚀 Features

- **Fixed Top Navigation Header:**
  - Hamburger menu icon and YouTube logo on the left.
  - Functional-looking search bar with Search and Voice Search buttons (including hover tooltips).
  - Action icons on the right: Create/Upload, YouTube Apps, Notifications (with a badge counter), and current user profile avatar.
- **Fixed Left Sidebar Navigation:**
  - Quick navigation links with icons for **Home**, **Explore**, **Subscriptions**, **Originals**, **YouTube Music**, and **Library**.
- **Responsive Video Feed Grid:**
  - Displays a curated 12-video grid featuring popular creators (MKBHD, Markiplier, Veritasium, MrBeast, TED-Ed, etc.).
  - Video thumbnails with duration badges overlaid in the bottom-right corner.
  - Direct clickable links to the actual YouTube videos and creator channels.
  - Clean metadata layout displaying channel profile pictures, video titles, channel names, view counts, and upload dates.
- **Typography:** Styled with Google Fonts (`Roboto`) to match YouTube's authentic UI look and feel.

## 🛠️ Tech Stack

- **HTML5:** Semantic structure (`<header>`, `<nav>`, `<main>`, `<section>`).
- **CSS3:** Modular stylesheets utilizing CSS Grid, Flexbox, positioning, and hover transitions.
- **Google Fonts:** Roboto (`400`, `500`, `700` weights).

## 📁 Project Structure

```text
youtube-clone/
├── youtube.html              # Main HTML structure
├── styles/
│   ├── general.css           # Global resets, typography, and body styles
│   ├── header.css            # Top navigation bar and tooltip styling
│   ├── sidebar.css           # Left fixed sidebar styling
│   └── video.css             # Video grid, thumbnail, and metadata styling
├── icons/                    # Header UI SVG icons
├── side-bar icons/           # Sidebar navigation SVG icons
├── thumbnails/               # Video preview thumbnail images (.webp)
└── channel-pictures/         # Creator and user profile pictures

Clone the repository:
git clone [https://github.com/AWAISRAO01/youtube-clone.git](https://github.com/AWAISRAO01/youtube-clone.git)

Navigate to the project directory:
cd youtube-clone

Run the project:
Open youtube.html directly in any web browser, or use a local development server (like VS Code's Live Server extension).

👤 Author
Muhammad Awais Zafar – @AWAISRAO01

