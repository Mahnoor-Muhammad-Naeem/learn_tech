# Tech Learning Portfolio

This repository collects practice projects and study notes across Node.js, Express, React, Bootstrap, and introductory Machine Learning. Each folder is self‑contained so you can open it independently, install dependencies, and run examples.

---

## Repository Structure
```
.
├─ Express_practice/        # Small APIs and middleware exercises with Express
├─ learn bootstrap/         # Responsive UI layouts and components using Bootstrap
├─ learn-node.js-2024/      # Modern Node.js features, modules, CLI utilities
├─ Machine Learning/        # Notebooks and scripts (pandas, numpy, scikit-learn)
├─ node_js_practice/        # Core Node.js (fs, http, events, streams) practice
├─ React/                   # Components, hooks, state management examples
├─ web_restaurant/          # Simple restaurant website/app (frontend + optional API)
├─ LICENSE                  # Project license
└─ README                   # You are here
```

---

## Prerequisites
- **Node.js** 18+ and **npm** or **yarn** for JavaScript projects.
- **Python** 3.9+ for Machine Learning notebooks/scripts.
- Optional: **Git**, **VS Code**, **Jupyter Lab/Notebook**.

---

## Quick Start
Clone the repo and open any folder you want to explore.
```bash
# clone once
git clone <your-repo-url>
cd <repo-root>

# open a specific project
cd Express_practice
```

---

## How to Run by Folder
### 1) Express_practice
```bash
cd Express_practice
npm install
npm run dev   # or: npm start
# open http://localhost:3000 (unless a different port is configured)
```

### 2) learn bootstrap
Open the HTML files directly in a browser or use a simple static server:
```bash
cd "learn bootstrap"
# Option A: VS Code Live Server extension
# Option B: quick static server
npx serve .   # or: python -m http.server 5500
```

### 3) learn-node.js-2024
```bash
cd learn-node.js-2024
npm install
npm run start    # or run individual scripts as documented in that folder
```

### 4) Machine Learning
```bash
cd "Machine Learning"
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

pip install -r requirements.txt  # if present
jupyter lab                      # or: jupyter notebook
```

### 5) node_js_practice
```bash
cd node_js_practice
npm install
node index.js        # or run the specific script for each exercise
```

### 6) React
```bash
cd React
npm install
npm run dev          # Vite-based projects
# or
npm start            # Create React App projects
```

### 7) web_restaurant
```bash
cd web_restaurant
npm install
npm run dev   # or: npm start
```

> Notes
> - Ports and scripts may vary per subproject; check each folder's README or package.json if available.
> - If a folder has no package.json, it may contain raw examples or static files only.

---

## Project Map
| Folder | Stack | What to expect |
|---|---|---|
| Express_practice | Node.js, Express | REST endpoints, routing, middleware, validation |
| learn bootstrap | HTML, CSS, Bootstrap | Grid, components, responsive layouts |
| learn-node.js-2024 | Node.js | ES Modules, filesystem, events, async patterns |
| Machine Learning | Python, pandas, scikit-learn | Data prep, models, evaluation notebooks |
| node_js_practice | Node.js | Core APIs, small utilities, patterns |
| React | React, JSX, Hooks | Components, state, effects, forms |
| web_restaurant | HTML/CSS/JS or React + optional Express | Menu pages, forms, basic CRUD |

---

## Conventions
- Commit messages follow a simple style: `type(scope): summary` (e.g., `feat(api): add courses endpoint`).
- Prefer small, focused commits and feature branches.
- Each folder should be independently runnable; add a short README if custom steps are needed.

---

## Troubleshooting
- **Port already in use:** change the port in `.env` or package.json scripts (e.g., `PORT=3001`).
- **Dependency errors:** delete `node_modules` and lock files, then reinstall (`npm ci` or `npm install`).
- **Python package issues:** ensure venv is active; pin versions in `requirements.txt`.

---

## License
See the `LICENSE` file for details.

