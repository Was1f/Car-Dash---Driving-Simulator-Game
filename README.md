
# 🚗 Car Racer - OpenGL Game using Midpoint Algorithms

Car Racer is a visually appealing 2D car racing game developed using Python and OpenGL. The game features custom vehicle drawing (car, bike, and truck) using only `GL_POINTS`, with all shapes created through the Midpoint Line and Circle Drawing algorithms.

---

## 🎮 Features

- 🚗 Play as a **car** or **bike**
- 🛻 Avoid randomly spawning **vehicles** (cars, bikes, trucks)
- 💥 Collision detection system with limited lives
- ❤️ Health power-up spawns after a time interval
- ⚡ Dynamic difficulty scaling with score
- 🖱️ In-game GUI elements: Pause, Restart, Exit, Change Vehicle
- 🟢 Drawn entirely with **GL_POINTS**, no sprites or textures

---

## 🧱 Built With

- Python 3.x
- [PyOpenGL](http://pyopengl.sourceforge.net/)
- GLUT

---

## 🖥️ Installation & Run

1. Make sure Python is installed on your system.
2. Install required libraries:

```bash
pip install PyOpenGL PyOpenGL_accelerate
```

3. Run the game:

```bash
python car_racer.py
```

---

## 🎮 Controls

### Keyboard

| Key | Action          |
|-----|------------------|
| `W` | Move Up         |
| `S` | Move Down       |
| `A` | Move Left       |
| `D` | Move Right      |

### Mouse

- 🎮 Click **Pause/Play** icon to pause or resume
- 🔁 Click **Restart** icon to reset the game
- ❌ Click **X** icon to exit
- 🚘 Click **Change Vehicle** to switch between car and bike

---

## 📊 Gameplay

- Vehicles move downward, and the player's goal is to avoid collisions.
- Score increases for every successfully dodged vehicle.
- If the player collides with a vehicle, a life is lost.
- Health power-up appears after a while; collecting it adds a life.
- Game Over triggers after all lives are lost.
- Highscore is tracked during the session.

---

## 🧮 Graphics Engine

This game uses:
- **Midpoint Line Drawing Algorithm** for lines (vehicle bodies, UI icons)
- **Midpoint Circle Drawing Algorithm** for wheels, heads, and UI buttons
- Entire rendering is done using **GL_POINTS**, mimicking low-level raster displays

---


---

## 🧠 Credits

Developed by Wasif Khan  
Built as an OpenGL graphics project using algorithmic drawing techniques.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

Happy Racing! 🏁
