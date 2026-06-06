<div align="center">

```
 ██████╗ ██████╗  ██████╗ ██████╗  ██████╗ ███████╗ █████╗ ██╗     
 ██╔══██╗██╔══██╗██╔═══██╗██╔══██╗██╔═══██╗██╔════╝██╔══██╗██║     
 ██████╔╝██████╔╝██║   ██║██████╔╝██║   ██║███████╗███████║██║     
 ██╔═══╝ ██╔══██╗██║   ██║██╔═══╝ ██║   ██║╚════██║██╔══██║██║     
 ██║     ██║  ██║╚██████╔╝██║     ╚██████╔╝███████║██║  ██║███████╗
 ╚═╝     ╚═╝  ╚═╝ ╚═════╝ ╚═╝      ╚═════╝ ╚══════╝╚═╝  ╚═╝╚══════╝
```

# 💍 Will You Marry Me?

### *একটি বিশেষ মুহূর্তের জন্য তৈরি — A Special Moment*

**[💖 Live Demo](https://akrakib.github.io/marry-me/)** &nbsp;•&nbsp; **[👨‍💻 Developer](https://rosterkabir.wordpress.com/)** &nbsp;•&nbsp; **[📘 Facebook](https://web.facebook.com/YoutuberKabir)** &nbsp;•&nbsp; **[🐙 GitHub](https://github.com/akrakib)**

<br/>

![Made with Love](https://img.shields.io/badge/Made%20with-Love%20❤️-ff2d6b?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML-Only-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/Animated-CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![No Framework](https://img.shields.io/badge/No%20Framework-Pure%20JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bangladesh](https://img.shields.io/badge/Made%20in-Bangladesh%20🇧🇩-006a4e?style=for-the-badge)

</div>

---

## 💖 এটা কী?

> একটি **Interactive Proposal Page** — যেখানে "Yes" চাপলে আনন্দ আসে,  
> আর "No" চাপতে গেলে... বাটন পালিয়ে যায়! 😄

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
      │    🧸 Dolls appear & jump
      │    💬 Sweet message shows
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
| 🌌 **Aurora Background** | Animated glowing orbs on dark background |
| 💍 **Floating Ring** | Golden glow + rotate animation |
| 😜 **Runaway No Button** | Moves on hover, touch & click — never clickable |
| 💖 **Heart Burst** | 40 hearts on Yes click + continuous rain |
| 🪟 **Glassmorphism** | Blur backdrop card with pulse border |
| ⭐ **Twinkling Stars** | 80 randomly placed animated stars |
| 📱 **Mobile Safe** | Touch events properly handled |
| 🔗 **Dev Link** | "A Kabir" links to personal blog |

---

## 🛠️ Tech Stack

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3_Animations-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Google Fonts](https://img.shields.io/badge/Playfair_Display-4285F4?style=for-the-badge&logo=google&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222?style=for-the-badge&logo=github)

</div>

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

## 👨‍💻 Developer

<div align="center">

<img src="https://github.com/akrakib.png" width="90" style="border-radius:50%"/>

### MD. Ahasanul Kabir Rakib

*Web Developer & Digital Creator — Bangladesh 🇧🇩*

[![Blog](https://img.shields.io/badge/Blog-rosterkabir.wordpress.com-21759B?style=for-the-badge&logo=wordpress)](https://rosterkabir.wordpress.com/)
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

Made with ❤️ by **[A Kabir](https://rosterkabir.wordpress.com/)** — Bangladesh 🇧🇩

</div>
