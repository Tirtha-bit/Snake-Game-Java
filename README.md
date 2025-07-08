# 🐍 Snake Game – Java GUI Version (Dockerized)

A modern version of the classic Snake Game written in Java using Swing and AWT.  
Originally created by [Hexadeciman](https://github.com/hexadeciman/Snake), this version has been improved and Dockerized by **Tirtha Deb** to enhance portability and learning experience.

---

## 🎮 Game Preview

![Snake Game Screenshot](https://i.imgur.com/RVxiGad.png)

---

## 🚀 Features

- GUI-based game using Java Swing
- Responsive snake movement with arrow keys
- Score tracking
- Game over & restart by reopening
- **Docker support** for platform-independent GUI execution
- Cross-platform compatibility via X Server (Linux/Windows/Mac)

---

## 🧠 What I Learned

- Java GUI (AWT + Swing)
- Event handling (`KeyListener`, `Timer`)
- Creating `.jar` files
- Building Docker containers with GUI support
- X Server configuration on Windows

---

## 🐳 Run with Docker

> Ensure Docker is installed and an X Server like **VcXsrv** is running (with "Disable Access Control" checked).

### Build the image:
```bash
docker build -t snake .
