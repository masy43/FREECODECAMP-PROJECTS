# freeCodeCamp Projects

A collection of my **freeCodeCamp** coursework projects and practice exercises.

This repo is organized by certification track:

- **Responsive Web Design** (HTML/CSS)
- **JavaScript Algorithms and Data Structures** (JS projects)
- **Relational Database** (SQL/PostgreSQL)

## Requirements

- For the browser-based projects: any modern browser (Chrome/Edge/Firefox).
- For the Node/CLI projects: **Node.js + npm**.
- For the SQL project: **PostgreSQL** (or a compatible environment).

## How to run

### Browser projects (HTML/CSS/JS)

Most folders contain an `index.html`.

Option A (simple):

- Open the project’s `index.html` in your browser.

Option B (recommended):

- Use VS Code’s **Live Server** extension and click **“Go Live”**.

### Node/CLI projects (with `package.json`)

Some JavaScript projects are small Node scripts that use `nodemon`.

From the project folder:

```bash
npm install
npm run app
```

### PostgreSQL project

The database project lives in `Relational Database/universe.sql`.

Typical setup (psql):

```bash
createdb universe
psql -d universe -f "Relational Database/universe.sql"
```

## Projects

### JavaScript Algorithms and Data Structures

- **Background Color Changer** — changes page background via JS.
- **Calorie Counter** — basic calorie tracking UI.
- **GradeBook App** — Node script (run with `npm run app`).
- **Music Player** — simple music player UI.
- **Palindrome Checker** — checks whether input is a palindrome.
- **Pyramid Generator** — Node script (run with `npm run app`).
- **Rock, Paper, Scissors Game** — interactive game.
- **Role Playing Game** — simple RPG-style browser game.

### Responsive Web Design

- **Accessibility Quiz**
- **Balance Sheet**
- **Cafe**
- **Cat Painting**
- **Cats**
- **Color Markers**
- **Nutrition Label**
- **Photo Gallery**
- **Piano**
- **Registration Form**
- **Rothko Painting**
- **Survey Form**
- **Technical Documentation Page**
- **Tribute Page**

### Relational Database

- **universe.sql** — schema and tables for the “Celestial Bodies Database” style project.

## Notes

- Folder names match the freeCodeCamp curriculum/project titles.
- If you find a typo in a folder name (e.g., “Palindorme Checker”), it’s kept as-is to match my original project folder.
