# 🎀✨ Tetris Dream – Pink Sparkle Edition ✨🎀

> **A fully playable Tetris game with a magical pastel theme, smooth animations, floating sparkles, and pure vanilla JavaScript.**  
> Just open the HTML file and start dropping blocks like cherry blossoms! 🌸

---

## 📱 What This App Does (In a Nutshell)

This is a **classic Tetris game** wrapped in a dreamy pink aesthetic.  
You control falling tetrominoes, arrange them to complete horizontal lines, and earn points.  
The game gets faster as you level up, and every score update triggers **sparkle explosions** ✨.  
It’s a single HTML file – no installation, no dependencies – just double‑click and play.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Page structure, canvas elements, semantic markup |
| **CSS3** | Animations, gradients, responsive layout, glowing effects, floating backgrounds |
| **JavaScript (ES6)** | Game logic, collision detection, rendering on canvas, event handling, animation frames |

No frameworks, no libraries – pure vanilla front‑end magic. 🍦

---

## 🎮 Features

- ✅ Classic Tetris mechanics (move, rotate, hard/soft drop)  
- 💖 Pastel pink UI with animated gradients and floating clouds  
- ✨ Sparkle effect on score increase and game over  
- 🧸 Next piece preview window  
- 📈 Level system – speed increases every 10 cleared lines  
- 🎯 Shadow preview – see where the piece will land  
- 🎀 Responsive design (works on desktop & tablets)  
- 🌈 Rainbow text & heartbeat animation on game over  
- 🔘 Fully interactive with keyboard controls  

---

## ⌨️ Controls (Keyboard)

| Action               | Key                  |
|----------------------|----------------------|
| Move Left            | `←` (Arrow Left)     |
| Move Right           | `→` (Arrow Right)    |
| Rotate Piece         | `↑` (Arrow Up)       |
| Soft Drop (faster)   | `↓` (Arrow Down)     |
| Hard Drop (instantly)| `Space`              |
| Pause / Resume       | `P`                  |

> 💡 **Tip:** Use the shadow outline to land pieces perfectly.

---

## 🧠 Process of Creation (How I Built It)

I started with a simple Tetris logic in plain JavaScript, but I wanted to make it **visually joyful**.  
So I added:

- **Gradient backgrounds** that shift over time (using CSS keyframes)  
- **Floating ellipses** that look like soft clouds or candy  
- **Canvas rendering** with custom gradient blocks + shiny highlights  
- **Shadow preview** to help players place pieces  
- **Sparkle system** – random emojis flying across the screen when you score  
- **Game over animation** with a bouncing, rainbow‑colored message  

The hardest part was **synchronising the line‑clear animation** with the board update without breaking the game loop. I used `setTimeout` with a fade‑out effect, then spliced the rows.  

I also spent time making the **collision detection** rock‑solid and the **drop interval** dynamic based on the level.  

The result? A Tetris game that feels both nostalgic and fresh – like playing on a magical girl’s desktop. 🌸✨

---

## 📚 What I Practiced While Creating This Project

- 🧩 **Game loop & state management** – using `requestAnimationFrame` for smooth updates  
- 💥 **Collision detection** – for moving, rotating, and stacking pieces  
- 🎨 **Canvas drawing** – custom blocks with gradients, strokes, and shadows  
- ⏱️ **Time‑based movement** – `dropCounter` with delta time for consistent speed  
- 🧼 **Line clearing logic** – removing full rows and shifting everything down  
- 🎭 **UI animations** – CSS keyframes, JavaScript‑triggered class toggles  
- ✨ **Dynamic visual feedback** – sparkles, updated numbers with bounce effects  
- 🎮 **Keyboard event handling** – preventing default actions, handling multiple keys  
- 📱 **Responsive design** – media queries, flexbox, and relative units  
- 🧪 **Debugging game timing** – ensuring `setTimeout` didn’t mess up the main loop  

This project was a **super fun way to practice full‑stack frontend skills** – even though it’s just one file, it covers layout, styling, logic, and real‑time animation.  

---

## 🚀 How to Run

1. Download `tetris.html`  
2. Double‑click it – opens in your browser  
3. Play immediately 🎉  

No server needed.

---

## 🤝 Contributing

Ideas, bug reports, and cute emoji suggestions are welcome!  
Open an issue or send a pull request. Let’s make Tetris even sparklier ✨

---

## 📄 License

MIT – free to use, modify, and share. Keep the credits or replace them with your own style. 💖

---

## 💬 Final Words

> *“Where every line clear feels like a celebration, and every fall is graceful.”* 🌸

If this little game made you smile, **⭐ star the repo** and share it with friends.  
Made with lots of ☕ and pink glitter by gerankamirovitch 


<img width="2550" height="1298" alt="image" src="https://github.com/user-attachments/assets/60be8e76-1046-4049-8bee-dedebc75ba1a" />
<img width="2555" height="1286" alt="image" src="https://github.com/user-attachments/assets/549dcc00-f2db-4fb6-802c-ab9caff2b3d2" />


