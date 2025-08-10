# Breach Data Checker – Self-Hosted Retro Edition

A privacy-focused breach lookup tool with a **monochrome retro UI** inspired by early Macintosh and Windows 98 aesthetics.  
Upload or paste an email/username → instantly check it against your **own breach dataset** (CSV, JSON, TXT, etc.) without sending data to any external API.

---

## Features
- **Self-Hosted** – No external lookups, keep your breach list local.
- **Monochrome Retro UI** – Old-school Macintosh/Windows 98 look.
- **Responsive** – Fits any screen, scrollable when needed.
- **File Upload & Paste** – Supports drag-and-drop or manual input.
- **Instant Match Highlighting** – Results appear instantly with no reload.
- **Lightweight** – Pure HTML, CSS, and JavaScript.

---

## Why?
Most breach checkers send your email/username to a third-party API. This is **not private**.  
This app keeps your sensitive queries and breach database **offline and in your control**.

---

## Getting Started

### 1. Clone the Repository

git clone https://github.com/yourusername/self-hosted-database-info-leak-checker.git
cd breach-data-checker
### 2. Prepare Your Breach Data
Place your breach dataset in the /data folder. Supported formats:

.txt – One account per line

.csv – Comma-separated values

.json – Array of strings

Example data/breach-list.txt:

graphql
Copy
Edit
hacker@example.com
user123
test@domain.com

### 3. Open in Browser

Simply open index.html in your browser.
No build step, no server required — works entirely client-side.

## Usage
Select your breach file or paste a list in the input field.

Type or paste the email/username you want to check.

Matches will appear in the Results section.

Scroll to view all matches if the list is long.

## Recommended File Structure

breach-data-checker/
│
├── index.html        # Main UI
├── style.css         # Retro monochrome theme
├── script.js         # Logic for matching
├── /data             # Your breach data (not tracked by GitHub)
│   ├── breach-list.txt
│   ├── breach-list.csv
│   └── breach-list.json
└── /assets           # Icons, UI graphics

## Recommended GitHub Tabs

Code – Main repository.

Issues – Bug reports and feature requests.

Discussions – UI ideas, data management tips.

Wiki – Guides for setting up breach lists.

Projects – Feature roadmap & UI overhaul plans.

Releases – Stable tagged versions.

Security – Policy for vulnerability reports.

## Privacy Note
This app never sends any data to a server or third-party API.
All checks happen in your browser using your local breach dataset.

## License
MIT License – free to use, modify, and distribute.
