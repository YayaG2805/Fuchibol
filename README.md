# Fuchibol – Interactive Story (HTML Only)

## Description

Fuchibol is an interactive narrative project built entirely with HTML.  
The story follows José Contreras, also known as “El Moyo”, a 15-year-old Guatemalan football prodigy who must decide the direction of his career.

The user plays as José and makes decisions that affect his future.  
Each choice leads to different story branches and ultimately one of three possible endings.

This version of the project focuses only on structure and navigation using pure HTML.

---

## How It Works

The project is structured as a branching narrative:

- The user starts on the main page.
- Each decision is represented by an `<a>` link.
- Every link leads to a different HTML page.
- All paths eventually end in one of three endings:
  - Positive Ending
  - Neutral Ending
  - Negative Ending

There is no JavaScript used in this project.  
Navigation is handled exclusively through HTML links.

---

## Project Structure


LAB2/Fuchibol
│├── index.html
├── paginas/
│ ├── index.html
│ ├── guastatoya.html
│ ├── betis.html
│ ├── final_bueno.html
│ ├── final_neutro.html
│ └── final_malo.html
│ ├── and the others
└── assets/
└── imagenes/


---

## Technologies Used

- HTML5
- Relative file paths for navigation
- Basic semantic structure (`section`, `header`, `footer`)

No CSS or JavaScript was used in this version.

---

## How to Run

If running locally:
1. Open `index.html` in a browser.

If deployed on NGINX:
1. Access the project through:

http://chicharronconpelos.shop/24128/LAB2/


---

## Author

Diego Guevara  
Universidad del Valle de Guatemala  
Sistemas y Tecnologías Web – 2026
