# Windows 7–Style Web Desktop (Fun Project)

A small **pure HTML + CSS + JavaScript** experiment that recreates a **Windows 7–like desktop experience in the browser**.

This project was built purely for fun and nostalgia — no frameworks, no build step, just old-school DOM hacking and a lot of UI polish.

You can check it here: https://dynart.net/fun/win7

## ✨ Features

* 🪟 **Movable windows** (drag by title bar)
* 📐 **Resizable windows** (edges + corners)
* 🗖 **Minimize / Maximize / Close**
* 🧭 **Tabbed window content**
* 📺 **Responsive embedded video** (keeps aspect ratio while resizing)
* 🖼️ **Image tab with proper scaling**
* 🖱️ **Desktop icon**

  * Windows-style selection highlight
  * Keyboard focus support
  * Double-click to open app
* 🎨 **Windows 7 visual style** using [7.css](https://khang-nd.github.io/7.css/)
* 🖥️ Fullscreen “desktop” with background image

## 📂 Project Structure

```
.
├── index.html        # Everything lives here (HTML + CSS + JS)
├── bg.jpg            # Desktop background image
├── icon.png          # Desktop icon (48x48 recommended)
├── dog.jpg           # Example image for Dogs tab
└── README.md
```

## 🚀 Getting Started

1. Clone or download the project
2. Put your assets next to `index.html`:

   * `bg.jpg`
   * `icon.png`
   * `dog.jpg`
3. Open `index.html` in a browser
   *(no server required)*

That’s it.

## 🛠️ Tech Stack

* **HTML5**
* **CSS3**

  * Flexbox
  * `aspect-ratio`
  * pointer-events
* **Vanilla JavaScript**

  * Pointer Events
  * Manual drag / resize logic
* **7.css** for Windows 7 UI styling

No frameworks. No dependencies. Just vibes.

## 🎯 Why This Exists

* Nostalgia for Windows 7
* UI experimentation
* Learning pointer events, resizing, layout edge cases
* Proving that you *don’t* need React for everything 😄

## 🧠 Known Limitations

* Single-window demo (easy to extend to multiple)
* No taskbar (yet)
* No real window persistence
* Accessibility is “good enough”, not perfect

## 🧑‍💻 Credits

* **Project author:** You (the human who wanted this to exist)
* **Main implementation & UI logic:** **ChatGPT**

  * Window manager logic
  * Dragging & resizing
  * Tabs behavior
  * Desktop icon selection
  * CSS layout fixes
  * Debugging browser quirks
* **UI styling:** [7.css](https://khang-nd.github.io/7.css/) by Khang Nguyễn

> This project was built collaboratively with ChatGPT — and yes, it did most of the heavy lifting 😄

## 🧩 Ideas for Future Fun

* Taskbar with running apps
* Multiple windows + z-index focus
* Aero snap (drag to edges)
* Right-click desktop menu
* Fake “Explorer” window using your tab system
* Sound effects (Win7 click sounds 👀)
