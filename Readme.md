# 🎬 EchoStream Media Player

EchoStream is a lightweight, browser-based media player inspired by VLC. It allows users to play local video files with essential playback, audio, and viewing controls—all built using pure HTML, CSS, and JavaScript.

---

## 🚀 Features

### 📂 File Management

* Open and play local video files
* Reload application
* Exit functionality (browser-dependent)

### ▶️ Playback Controls

* Play / Pause toggle
* Restart video
* Speed control (0.25x – 4x)

### 🔊 Audio Controls

* Volume Up / Down
* Mute / Unmute
* Visual feedback using toast notifications

### 🎥 Video Controls

* Fullscreen mode
* Exit fullscreen

### 💡 UI Highlights

* Clean VLC-inspired interface
* Dropdown menu navigation
* Toast notifications for actions (volume, speed, etc.)

---

## 🛠️ Tech Stack

* **HTML5** – Structure
* **CSS3** – Styling & layout
* **JavaScript (Vanilla)** – Functionality & interactivity

---

## 📁 Project Structure

```
EchoStream/
│── index.html      # Main UI structure
│── style.css       # Styling and layout
│── script.js       # Functionality
│── logo.png        # App logo
│── VLC_main.png    # Background image
```

---

## ⚙️ How It Works

1. Click **File → Open File**
2. Select any video from your system
3. Control playback using menu options

The app dynamically creates a `<video>` element and loads the selected file using `URL.createObjectURL()`.

---

## 📸 Key Concepts Used

* DOM Manipulation
* Event Handling
* HTML5 Video API
* Fullscreen API
* Dynamic UI Updates

---

## ⚠️ Limitations

* `window.close()` may not work in all browsers (security restrictions)
* Supports only video formats supported by your browser
* No playlist or subtitle support (yet)

---

## 🔮 Future Improvements

* Add playlist support
* Subtitle integration (.srt)
* Drag & drop file upload
* Keyboard shortcuts (like VLC)
* Progress bar enhancements

---

## 👨‍💻 Author

**Ajit Kumar Saini**
Made with ❤️ using JavaScript

---

## ⭐ Show Your Support

If you like this project:

* ⭐ Star this repository
* 🍴 Fork it
* 🧠 Contribute new features

---

## 📜 License

This project is open-source and available under the MIT License.
