# ⚡ LiveReader

**LiveReader** is a lightweight **Safari Web Extension** that converts webpage text into natural speech.
It injects a minimal floating widget into any webpage and allows users to listen to articles, blogs, and documentation hands-free.

Built using **Swift, JavaScript, and Safari Web Extension APIs**, LiveReader bridges native macOS development with modern web technologies.

---

## 🚀 Features

* 🔊 **Text-to-Speech for Any Webpage**
  Instantly read webpage content aloud.

* 🌐 **Works Across All Websites**
  Runs on any webpage using injected content scripts.

* 🧩 **Floating Reader Widget**
  Lightweight UI that allows easy control of speech playback.

* ⚡ **Minimal & Fast**
  Designed to run with very low overhead.

* 🌙 **System Theme Friendly**
  Adapts to light and dark mode automatically.

---

## 🧠 How It Works

LiveReader uses a **Safari Web Extension architecture**:

1. **Content Script**

   * Injects a floating widget into webpages
   * Extracts readable text from the DOM

2. **Background Script**

   * Handles extension lifecycle events

3. **Speech Engine**

   * Uses the browser’s **Speech Synthesis API** to convert text into speech

4. **Native Swift Wrapper**

   * Required by Safari to package and run the extension

---

## 🏗 Project Structure

```
LiveReader
│
├── LiveReader.xcodeproj        # Xcode project
│
├── LiveReader                  # Native macOS container app
│   ├── AppDelegate.swift
│   ├── ViewController.swift
│   └── Resources
│
└── LiveReader Extension        # Safari Web Extension
    ├── manifest.json
    ├── background.js
    ├── content.js
    ├── popup.html
    ├── popup.css
    ├── popup.js
    ├── images
    └── _locales
```

---

## 🛠 Technologies Used

* **Swift**
* **JavaScript**
* **Safari Web Extensions API**
* **Speech Synthesis API**
* **Xcode**
* **Git**

---

## 💻 Installation (Development)

1. Clone the repository

```
git clone https://github.com/MaheshJella7/LiveReader.git
```

2. Open the project

```
LiveReader.xcodeproj
```

3. Build and run the app using **Xcode**

4. Enable the extension in:

```
Safari → Settings → Extensions
```

5. Activate **LiveReader**

---

## 🎯 Use Cases

* Listening to long articles
* Accessibility for visually impaired users
* Hands-free browsing
* Multitasking while reading documentation

---

## 📌 Future Improvements

* Adjustable reading speed
* Voice selection
* Smart article extraction
* Pause / resume controls
* AI summarization mode
* Highlighting text while reading

---

## 👨‍💻 Author

**Mahesh Jella**

Computer Science student interested in
AI, Machine Learning, and intelligent software systems.

GitHub:
https://github.com/MaheshJella7

---

## 📜 License

This project is licensed under the **MIT License**.
