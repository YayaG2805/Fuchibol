# Fuchibol – Interactive Story

## Description

**Fuchibol** is an interactive narrative built with pure HTML and CSS.  
The story follows **José Contreras**, also known as *"El Moyo"*, a 15-year-old Guatemalan football prodigy who must choose the direction of his career between two paths: debuting in Guatemala's national league with Guastatoya FC, or chasing the European dream at Real Betis' youth academy in Spain.

You play as José and every decision shapes his future — leading to one of three possible endings.

---

## How It Works

The project is a branching narrative built entirely without JavaScript:

- The user starts at the main page and picks a career path.
- Each choice links to a different HTML page.
- Pages are organized into thematic folders (`inicio`, `guastatoya`, `betis`, `finales`).
- All paths eventually end in one of three endings: **Positive**, **Neutral**, or **Negative**.

---

## Project Structure

```
fuchibol/
├── index.html              ← Redirect to pages/inicio/
├── .gitignore
├── README.md
├── css/
│   ├── story-theme.css     ← CSS variables and design tokens
│   ├── base.css            ← Reset and global styles
│   ├── components.css      ← Buttons, badges, dialogues
│   ├── layouts.css         ← Grid and Flexbox structure
│   └── animations.css      ← Keyframes and transitions
├── pages/
│   ├── inicio/
│   │   └── index.html      ← Main page
│   ├── guastatoya/         ← Guatemala path pages
│   │   ├── guastatoya.html
│   │   ├── disciplina_guasta.html
│   │   ├── fiesta_guasta.html
│   │   ├── mentir_guasta.html
│   │   ├── aceptar_guasta.html
│   │   ├── amistoso_guasta.html
│   │   └── cuidarme_guasta.html
│   ├── betis/              ← Spain path pages
│   │   ├── betis.html
│   │   ├── cantera_betis.html
│   │   ├── nostalgia_betis.html
│   │   ├── extra_betis.html
│   │   ├── agente_betis.html
│   │   ├── apoyo_betis.html
│   │   └── regreso_betis.html
│   └── finales/            ← Story endings
│       ├── final_bueno.html
│       ├── final_neutro.html
│       └── final_malo.html
└── assets/
    └── imagenes/           ← All story images
```

---

## Technologies Used

- **HTML5** — Semantic structure and navigation
- **CSS3** — Custom properties, Grid, Flexbox, Keyframe animations
- **Google Fonts** — Bebas Neue, Barlow Condensed, Barlow
- No JavaScript used anywhere in this project

---

## CSS Architecture

| File | Purpose |
|---|---|
| `story-theme.css` | Design tokens: colors, fonts, spacing, transitions |
| `base.css` | CSS reset, typography, global element styles |
| `layouts.css` | Grid/Flexbox page structure, responsive layout |
| `components.css` | Buttons, badges, dialogue blocks, ending states |
| `animations.css` | All `@keyframes` and animation application |

---

## How to Run

### Locally
1. Clone the repository.
2. Open `index.html` in any modern browser.

### On NGINX
Access via:
   ```
   http://chicharronconpelos.shop/24128/LAB2/
   ```

---

## Author

**Diego Guevara** — 24128  
Universidad del Valle de Guatemala  
Sistemas y Tecnologías Web – 2026
