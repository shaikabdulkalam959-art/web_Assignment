# HTML, CSS & JavaScript – Practical Programs

**Student Name:** Shaik Abdulkalam
**Register Number:** _(fill in)_
**Class / Section:** B.Tech CSE - AI/ML, Sai University, Chennai
**Subject:** Web Technology / HTML, CSS & JavaScript Practicals
**Assignment:** HTML, CSS & JavaScript – Practical Assignment

## Total Programs Completed: 157

- **HTML Programs:** 15
- **CSS Programs:** 75
- **JavaScript Programs:** 67
  - Mini Projects: 18
  - DOM Manipulation: 5
  - JavaScript Events: 6
  - Forms and Validation: 3
  - Browser Objects & Browser Features: 7
  - Web Storage: 4
  - Array Methods: 5
  - String & Object Methods: 3
  - ES6+ Features: 5
  - Functions & Closures: 4
  - Asynchronous JavaScript: 4
  - Error Handling, JSON & Regex: 3

## How to Run

1. Open `index.html` in any modern web browser (double-click the file, or right-click → Open with → Browser).
2. Use the three dashboard cards to navigate to HTML, CSS or JavaScript program lists.
3. Each list page has a **search box** at the top — start typing a program name to filter the list instantly.
4. Click any program link to open that individual program page.
5. Every program page has **Home** and **Back to [Category] Programs** links at the bottom — no need to type file names manually.

## Project Structure

```
project/
├── index.html                   → Main dashboard (links to all 3 categories)
├── html/
│   ├── index.html                → HTML program list (15 programs, searchable)
│   └── html-basic-structure.html ... 15 program files total
├── css/
│   ├── index.html                → CSS program list (75 programs, searchable)
│   └── css-universal-element-selectors.html ... 75 program files total
├── javascript/
│   ├── index.html                → JavaScript program list (67 programs, grouped by topic + searchable)
│   └── digital-calculator.html ... 67 program files total
├── assets/
│   ├── style.css                 → Shared stylesheet used by all 161 pages
│   ├── images/                   → Place any images here
│   └── icons/                    → Place any icons here
└── README.md
```

## Notes on Code Quality

- Every one of the 157 programs is a fully self-contained, separate HTML file, as required — none are combined.
- All internal navigation links were automatically verified to resolve correctly (0 broken links across 161 pages).
- Every inline JavaScript block (72 total across HTML/CSS/JS demo pages) was checked with `node --check` and has zero syntax errors.
- A shared `assets/style.css` keeps the visual design consistent and avoids duplicating the same CSS in every file; each program only adds a small `<style>` block for concepts unique to that demo.
- Meaningful file names, consistent indentation, and comments are used throughout.
- JavaScript program list page groups programs by sub-topic (Mini Projects, DOM, Events, etc.) matching the assignment's required categories, for easy grading.
