
```markdown
# 🌟 FAQ Accordion Card

---

## 📋 Project Description

This project is a solution to the **FAQ Accordion Card** challenge from Frontend Mentor. It features a list of frequently asked questions where clicking on each question toggles its answer with a smooth animation.

🔗 **Challenge Link:**  
[FAQ Accordion Card](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz)

---

## 📂 Folder Structure

```

├── assets/                  🎨 (images & static assets)
├── CSS/                     🎨 (styles)
│   └── styles.css
├── js/                      ⚙️ (scripts)
│   └── script.js
├── index.html               🚀 (entry point)
└── README.md                📘 (documentation)

````

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3** (Flexbox)
- **JavaScript (ES6)**

---

## 🚀 Installation & Usage

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/your-username/faq-accordion-card.git
````

2. **Open the project:**
   Navigate to the project folder and open `index.html` in your browser.
3. **Interact:**
   Click any question to expand or collapse the answer. 🤓

---

## ✨ Features

* 🔄 **Responsive design** for desktop and mobile still in progress.
* 🎨 **Smooth animations** for expanding and collapsing answers.
* 🔁 **Toggle div** indicating open/closed the state will change according with the CSS and JS.

---

## 💡 How It Works

In `js/script.js`, we implemented a `btn(id)` function that toggles the display of the answer element by its `id`. Each question button calls this function via an `onclick` attribute in the HTML:

```js
function btn(id) {
  const chechi = document.getElementById(id);
  if (chechi.style.display === "none") {
    chechi.style.display = "block";
  } else {
    chechi.style.display = "none";
  }
  console.log("toggle Worked");
}
```

### Usage in HTML

Below is an example that matches your structure, using a `div.toggle1`, an `img` icon, and `p` tags with IDs:

```html
<!-- Question container -->
<div class="toggle1">
  <p class="toggole1" onclick="btn('son2')">
    Is Frontend Mentor free?
  </p>
  <img
    src="assets/icons/icon-plus.svg"
    alt="icon-plus"
    class="btn0"
    id="bt2"
    onclick="btn('son2')"
  />
</div>

<!-- Answer container -->
<div class="info1">
  <p class="son" id="son2" style="display: none;">
    Yes, Frontend Mentor offers both free and premium coding challenges, with the free option providing access to a range of projects suitable for all skill levels.
  </p>
</div>
```

* The `onclick` attributes on both the `<p>` and `<img>` call `btn('son2')`.
* The `<p>` has `id="son2"` and is initially hidden via `style="display: none;"`.

---

## 🤝 Credits

* Original challenge by **Frontend Mentor**.
* Icons from **Frontend Mentor**.

---

## 📝 License

This project is licensed under **Frontend Mentor**. 

---

> Thanks for checking out this project! 🎉

```
```
