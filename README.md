### 🎯 **CanvasScrollPlayer**

**CanvasScrollPlayer** ek lightweight JavaScript library hai jo scroll-based frame-by-frame canvas animation ko asaan banati hai. Aap bas apne image frames provide karein, aur yeh library scroll ke saath animation handle karti hai.

---

### 🚀 **Live Demo**

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>CanvasScrollPlayer Demo</title>

  <!-- CanvasScrollPlayer CSS -->
  <link rel="stylesheet" href="CanvasScrollPlayer.min.css">

  <!-- GSAP CDN -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>
</head>
<body>
  <div class="parent">
    <canvas id="frame"></canvas>
  </div>

  <!-- Your CanvasScrollPlayer JS -->
  <script src="CanvasScrollPlayer.min.js"></script>

  <script>
    // Initialize CanvasScrollPlayer
    new CanvasScrollPlayer({
      canvasId: 'frame',
      framePath: './assets/frame_',
      totalFrames: 381
    });
  </script>
</body>
</html>
```
---

### 🛠️ **Installation via CDN**

```html
<!-- GSAP aur ScrollTrigger CDN -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>

<!-- CanvasScrollPlayer CSS -->
<link rel="stylesheet" href="CanvasScrollPlayer.min.css">

<!-- CanvasScrollPlayer JS -->
<script src="canvasScrollPlayer.min.js"></script>
```

---

### 📦 **Folder Structure**

```
canvas-scroll-player/
├── index.html
├── canvasScrollPlayer.min.js
├── CanvasScrollPlayer.min.css
└── assets/
    ├── frame_0001.jpeg
    ├── frame_0002.jpeg
    └── ... up to frame_0381.jpeg
```

> **Note:** `assets` folder mein aapke saare frames hone chahiye, named as `frame_0001.jpeg` to `frame_0381.jpeg`.

---

### 🧾 **Usage**

```html
<div class="parent">
  <canvas id="frame"></canvas>
</div>

<script>
  new CanvasScrollPlayer({
    canvasId: 'frame',
    framePath: './assets/frame_',
    totalFrames: 381
  });
</script>
```

---

### 📋 **Features**

* ✅ Scroll-based frame control
* ✅ Responsive canvas scaling
* ✅ Easy integration with GSAP ScrollTrigger
* ✅ Lightweight and fast

---

### 🤝 **Contributing**

Pull requests welcome! Agar aap koi feature add karna chahte hain ya bug fix karna chahte hain, toh please ek issue open karein ya direct PR bhejein.

---

### 📄 **License**

MIT License

---

Agar aap chahte hain ki main aapke liye ek **GitHub Pages** live demo bhi setup kar doon, toh please batayein. Main aapke liye `gh-pages` branch create karke live demo link provide kar dunga.
