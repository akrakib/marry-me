<img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:1a0010,50:5c0030,100:ff2d6b&text=%20Marry%20Me%20💍&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Interactive%20Proposal%20Page%20%7C%20Built%20by%20A%20Kabir&descAlignY=60&descAlign=50" width="100%" />

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Playfair+Display&color=FF2D6B&center=true&vCenter=true&size=22&pause=1000&lines=Will+You+Marry+Me%3F+💍;Yes+Button+%3D+Hearts+Burst+💖;No+Button+%3D+Runs+Away+😜;Aurora+Dark+Background+🌌;Fully+Mobile+Responsive+📱" />
</p>

<p align="center">
  <a href="https://akrakib.github.io/marry-me/">
    <img src="https://img.shields.io/badge/💖%20Live%20Demo-ff2d6b?style=for-the-badge&logoColor=white" />
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/Made%20with-Love%20❤️-ff2d6b?style=for-the-badge" />
  <img src="https://img.shields.io/badge/HTML-Only-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/No%20Framework-Pure%20JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Made%20in-Bangladesh%20🇧🇩-006a4e?style=for-the-badge" />
</p>

---

## 💖 এটা কী?

> একটি **Interactive Proposal Page** — যেখানে **"Yes"** চাপলে আনন্দ আসে,  
> আর **"No"** চাপতে গেলে... বাটন পালিয়ে যায়! 😄

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│   💍  Floating Ring Animation with Golden Glow          │
│   🌌  Aurora Dark Background — Deep Rose Theme          │
│   ⭐  80+ Twinkling Stars                               │
│   💖  Continuous Floating Hearts (8 types)              │
│   🪟  Glassmorphism Card Design                         │
│   ✨  Pulse Ring Animation                              │
│   😜  Runaway "No" Button — Mouse & Touch              │
│   📱  Fully Mobile Responsive                           │
│   🔗  Developer Link on Name                            │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 🎬 কিভাবে কাজ করে?

```
User visits page
      │
      ▼
 💍 Ring floats & ⭐ Stars twinkle
      │
      ├──► clicks "Yes 💖"
      │         │
      │         ▼
      │    ❤️ Hearts burst (40 pieces)
      │    🧸 Sweet message shows
      │    💬 "আমি জানতাম 😏💖"
      │
      └──► tries "No 😜"
                │
                ▼
           Button runs away! 😂
           (Mouse hover → moves)
           (Touch → moves instantly)
           (Click → still moves, never works)
```

---

## ✨ Features

| Feature | Description |
|---|---|
| 🌌 **Aurora Background** | Animated glowing orbs on dark rose background |
| 💍 **Floating Ring** | Golden glow + rotate animation |
| 😜 **Runaway No Button** | Moves on hover, touch & click — never clickable |
| 💖 **Heart Burst** | 40 hearts on Yes click + continuous rain |
| 🪟 **Glassmorphism** | Blur backdrop card with pulse pink border |
| ⭐ **Twinkling Stars** | 80 randomly placed animated stars |
| 📱 **Mobile Safe** | Touch events properly handled |
| 🔗 **Dev Link** | "A Kabir" links to personal blog |

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3_Animations-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Playfair_Display-FF2D6B?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Pages-222?style=for-the-badge&logo=github" />
</p>

```
📁 marry-me/
├── 📄 index.html     # সব কিছু এক ফাইলে (HTML + CSS + JS)
└── 📄 README.md      # এই ফাইল
```

> **কোনো library নেই। কোনো framework নেই। কোনো dependency নেই।**  
> শুধু একটি HTML ফাইল — যেকোনো browser-এ চলবে।

---

## 🚀 নিজের জন্য Customize করুন

`index.html` ফাইলে এই অংশটুকু পরিবর্তন করুন:

```javascript
// Yes বাটন চাপলে যে message দেখাবে
function sayYes() {
  document.getElementById('result').innerHTML =
    'আমি জানতাম 😏💖<br><em>Babur Ammu, তুমি শুধু আমারই ❤️</em>';
    //  ↑ এখানে নিজের message লিখুন
}
```

```html
<!-- Title পরিবর্তন করুন -->
<h1>Dear, Will You<br>Marry Me?</h1>
<!-- ↑ নিজের ভাষায় লিখুন -->
```

---

## 📱 Mobile-এ "No" Button কিভাবে কাজ করে?

```
touchstart  →  e.preventDefault()  →  Button moves away
                     ↓
              pointer-events: none (400ms)
                     ↓
              pointer-events: auto  ← আবার সরবে পরের touch-এ
```

> **click event ও cancel করা আছে** — যতভাবেই চাপুন, No কখনো কাজ করবে না! 😈

---

## 🚀 Getting Started

### Option 1 — Live Demo
👉 **[https://akrakib.github.io/marry-me/](https://akrakib.github.io/marry-me/)**

### Option 2 — Run Locally

**1. Clone the repository**
```bash
git clone https://github.com/akrakib/marry-me.git
```

**2. Open in browser**
```bash
cd marry-me
open index.html
```

---

## 👨‍💻 Developer

<div align="center">

<img src="https://github.com/akrakib.png" width="90" style="border-radius:50%"/>

### MD. Ahasanul Kabir Rakib

*Web Developer & Digital Creator — Bangladesh 🇧🇩*

[![Blog](https://img.shields.io/badge/Blog-rosterkabir.wordpress.com-FF2D6B?style=for-the-badge&logo=wordpress)](https://rosterkabir.wordpress.com/)
[![GitHub](https://img.shields.io/badge/GitHub-akrakib-181717?style=for-the-badge&logo=github)](https://github.com/akrakib)
[![Facebook](https://img.shields.io/badge/Facebook-YoutuberKabir-1877F2?style=for-the-badge&logo=facebook)](https://web.facebook.com/YoutuberKabir)
[![Gmail](https://img.shields.io/badge/Gmail-Contact-EA4335?style=for-the-badge&logo=gmail)](mailto:mdahasanulkabirrakib@gmail.com)

</div>

---

## ⭐ পছন্দ হলে

```
★  GitHub-এ Star দিন
★  বন্ধুদের পাঠান — হয়তো কেউ কাজে লাগাবে 😄
★  Fork করে নিজের মতো বানান
```

---

<div align="center">

**💍 Will You Marry Me? 💍**

*"No বাটন কখনো কাজ করবে না — Yes ছাড়া কোনো পথ নেই!"* 😏

**[🌐 Live Demo দেখুন](https://akrakib.github.io/marry-me/)**

---

Made with 💖 by **[A Kabir](https://rosterkabir.wordpress.com/)** — Bangladesh 🇧🇩

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:ff2d6b,100:1a0010&section=footer" width="100%" />
