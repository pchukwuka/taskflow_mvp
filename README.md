# TASKFLOW — Mini Task Manager (MVP) ✅

A lightweight, responsive task management web app built with **HTML**, **CSS**, and **JavaScript**
 

##  Live Demo

 Live URL: https://taskflow-mvp-snowy.vercel.app/
 

##  Problem Statement & Idea

Startups need a fast, low-cost way to validate ideas. TASKFLOW is an MVP to quickly capture and track tasks in the browser and share a public prototype with users.

 

##  Features

- Add new tasks (title, project, priority, due date)
- Display tasks with priority and due date
- Mark tasks as completed
- Delete tasks
- Persistent tasks using `localStorage`
- Responsive design and accessible interactions

 

##  Technology Stack

- HTML (structure)
- CSS (styling, responsive design)
- JavaScript (logic, localStorage)
- Hosting: **Vercel** — static hosting

 

##  Run Locally

1. Clone the repo:

```bash
git clone https://github.com/pchukwuka/taskflow_mvp.git
cd taskflow_mvp
```

2. Quick options to run locally:

- Double-click `index.html` and open in browser
- Use VS Code Live Server (recommended)



##  Deployment (Summary)

This project is deployed on **Vercel** using static hosting (HTML/CSS/JS only). Other static platforms like Netlify or GitHub Pages would also work.
See `DEPLOYMENT.md` for step-by-step instructions (Vercel preferred for simplicity).

 

##  Web Infrastructure — Quick Explanation

- **Browser**: Requests your site, parses HTML, loads CSS/JS, and executes JavaScript.
- **DNS**: Translates your friendly domain to the hosting provider's IP addresses.
- **Web server / CDN (Vercel/Netlify)**: Serves the static `index.html`, `style.css`, and `script.js` files over HTTP(S).
- **Static files**: These files are delivered directly to browser and cached at the edge for speed.

A more detailed explanation and diagram are in `INFRASTRUCTURE.md`.


 


##  Design Choices

- No backend: persistence is via `localStorage` for simplicity and to satisfy the assignment's constraints (static hosting).
- Prioritized accessibility and clear UI for quick MVP validation.



##  Repository Structure


/taskflow_mvp
  ├── index.html
  ├── style.css
  ├── script.js
  ├── README.md
  ├── DEPLOYMENT.md
  └── INFRASTRUCTURE.md



