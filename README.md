# rubiks-cube-solver# Rubik's Cube Solver 🧩

An object-oriented Rubik’s Cube simulator and solver built in pure **JavaScript, HTML, and CSS**.  
This project was developed as part of a technical assignment to demonstrate **OOP design, problem-solving, and algorithmic thinking**.

---

## 🎯 Features
- **Object-Oriented Cube Representation**  
  Encapsulates cube state and operations in a `Cube` class.
- **Manual Moves**  
  Apply standard Rubik’s cube notations (`R`, `R'`, `U`, `U2`, etc.).
- **Scramble Generator**  
  Randomly scrambles the cube with a sequence of valid moves.
- **Solver**  
  Reverses the scramble to restore the cube to the solved state.  
  *(Not optimized — focuses on correctness rather than shortest path.)*
- **Step-by-Step Visualization**  
  Uses a custom `getCubeSvg()` renderer to show the cube after every move.
- **No Backend Needed**  
  Fully client-side, runs in any modern browser.

---

## 🚀 Live Demo
Try it online via GitHub Pages:  
👉 [Rubik’s Cube Solver Demo](https://hiyanamdeo175-oss.github.io/rubiks-cube-solver/)

---

## 🛠️ How to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/hiyanamdeo175-oss/rubiks-cube-solver.git
