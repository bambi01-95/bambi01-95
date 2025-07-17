## Hi there 👋 I'm SHIKADA HIROTO

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=bambi01-95)](https://github.com/anuraghazra/github-readme-stats)

---

# [<img src="shicalogo.png" width="60">](https://github.com/bambi01-95/SHICA) SHICA 
### (C/C++)

SHICA is my research project — a domain-specific language designed for multi-agent systems.

> 🚧 This language is under development. Please don’t use it yet 🥲

```shica
event touch = trigReadGPIO()
state default{ 
    entry(){
        print("Now I am default")
    }
    touch(int num) {
        print("Ouch, don't prod me!");
        state upset;
    }
}

state upset {
    entry() {
        print("Now I am upset.");
        init timer5Sec = timerSec(5);
    }
    touch(int num) {
        print("Really, stop clicking me, it hurts!");
        timer5Sec.reset();
    }
    timer5Sec(int s) {
        state default;
    }
}
````

---

# [<img src="tatalogo.png" width="60">](https://github.com/bambi01-95/mechatoro3app) Mechatoro3App

### (Swift)

An iOS controller app for an expandable two-wheeled rover.

Supports 3 input modes:
🕹️ Stick | 🔘 Buttons | 🧭 Gyroscope
And in some modes — enjoy VR-style camera streaming!

<p align="center">
<img src="tatahome.png" width="200">
<img src="tata1.png" width="200">
<img src="tata2.png" width="200">
<img src="tata3.png" width="200">
</p>

---

## [Mechatoro Rover Code](https://github.com/bambi01-95/mechatoro)

### (Python, C++)

This repository includes the rover's software and firmware.
Control and monitor the robot via web or GUI applications using `pygame`, `Django`, and more.

<p align="center">
<img src="mechatoroClose.jpeg" width="200">
<img src="mechatoroOpen.jpeg" width="200">
</p>

---

# [<img src="precaplogo.png" width="60">](https://github.com/bambi01-95/precap2022_22K13_Inspection) PreCap2022 Inspection System

### (Python \[TensorFlow, Django, OpenCV], SQLite, JS, HTML/CSS)

This web-based inspection system was developed in collaboration with a partner company.

> 🔒 The repository is private due to confidentiality.

📰 [Project Article (Japanese)](https://www2.deloitte.com/jp/ja/blog/group/2022/thesmartfactory-kyoto-news-01-capstone-project.html)

<p align="center">
<img src="precapUI1.png" width="300">
<img src="precapUI2.png" width="300">
</p>

---

# [<img src="dearlogo.jpeg" width="60">](https://github.com/bambi01-95/Dear) Dear

### (In Development — ETA: 2 months)

An SNS platform to enrich your university life.
Stay tuned for more updates!

<p align="center">
<img src="homepage-design.png" width="500">
</p>

---

# <img src="dronelogo1.jpg" width="60"> Drone Show System

### (Unity: C# & Python) + (C/C++)

A two-part drone show system:

* 🕹️ Unity-based visual simulator
* ⚙️ Embedded control with C/C++

(Currently in development)

---

## 🔭 I Want to Develop:

* SNS for cornerstone & capstone projects
* VR-integrated TENJI block experience for smart white canes
* Interactive applications for holographic displays

---
