# shopify-testimonial-slider

A responsive and customizable testimonial slider section for Shopify themes, built using Liquid, CSS, and Splide.js.

---

## 🚀 Installation

### 1. Add Section File

Create a new file inside your theme:

```bash
/sections/shopify-testimonial-slider.liquid
```

Paste the provided code into this file.

---

### 2. Include Splide.js

Add the following in your `theme.liquid` file before `</head>`:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@splidejs/splide@4/dist/css/splide.min.css">
<script src="https://cdn.jsdelivr.net/npm/@splidejs/splide@4/dist/js/splide.min.js"></script>
```

---

### 3. Add Section in Theme

* Go to **Online Store → Customize**
* Click **Add Section**
* Select **Testimonial Slider**

---

## ⚙️ Features

* Fully responsive (desktop, tablet, mobile)
* Dynamic testimonials using Shopify blocks
* Star rating system
* Autoplay slider
* Custom navigation (arrows & dots)
* Avatar image support
* Background color or image option
* Custom spacing and layout controls

---

## 🧩 Configuration

### Slider Settings

```js
{
  type: "loop",
  perPage: 3,
  gap: "30px",
  autoplay: true,
  interval: 5000
}
```

### Breakpoints

* Desktop: 3 slides
* Tablet: 2 slides
* Mobile: 1 slide

---

## 🧱 Testimonial Block Fields

Each testimonial includes:

* Rating (1–5)
* Quote text
* Client image
* Name
* Designation

---

## 📌 Requirements

* Shopify Online Store 2.0
* Splide.js library included

---

## 📄 License

Free to use and modify.

---

## 👨‍💻 Author

GitHub: https://github.com/iamatif

---
