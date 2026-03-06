# Web-Birthday
# 🎂 Interactive Birthday Website

A small interactive birthday website made with **HTML, CSS, and JavaScript** to deliver a heartfelt birthday message.
This project was created as a digital birthday surprise with animations, background music, and an interactive candle that can be blown out.

The design focuses on a **soft, warm, and emotional atmosphere**, making the experience feel personal and meaningful.

---

# ✨ Features

* 🎂 **Birthday intro screen** with animated cake
* ✨ **Floating particles animation** (stars and hearts)
* 💌 **Interactive letter** that reveals a birthday message
* 🔥 **Blowable candle feature** using microphone detection
* 🎵 **Background music** with smooth fade-in effect
* 🎁 **Surprise modal message**
* 📱 **Responsive design** for mobile and desktop

---

# 🖥️ Demo Flow

1. User opens the website.
2. A **birthday cake intro screen** appears.
3. User taps the cake to enter.
4. Background music starts playing.
5. User can **blow the candle using their microphone**.
6. A heartfelt **birthday letter appears**.
7. A **surprise message modal** is revealed.

---

# 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **Vanilla JavaScript**
* **Web Audio API** (for microphone blow detection)
* **Google Fonts**

---

# 📁 Project Structure

```
birthday-website/
│
├── index.html
├── river-flows.mp3
└── README.md
```

---

# 🎵 Music

The website includes a soft instrumental background music to enhance the emotional experience.

You can replace the music file with any `.mp3` by updating this line in the script:

```javascript
const audio = new Audio('river-flows.mp3');
```

---

# 🚀 How to Run

1. Clone this repository

```
git clone https://github.com/yourusername/birthday-website.git
```

2. Open the folder

3. Run the project using a local server (recommended)

Example with VSCode Live Server:

```
Right Click → Open with Live Server
```

4. Open in browser and enjoy the experience.

---

# ⚠️ Microphone Permission

The candle blowing feature requires **microphone access**.

When prompted by the browser:

```
Allow microphone access
```

Then blow toward the microphone to extinguish the candle.

---

# 💖 Message Behind This Project

This website was created as a **personal birthday surprise**, combining simple web technologies with emotional storytelling.

The goal is to show that even a small website can deliver a **memorable and meaningful moment**.

---

# 📄 License

This project is open for learning and inspiration.

Feel free to modify and use it for your own birthday surprises or creative web experiments.
