# 🚀 Bootstrap 101 - Introduction Lecture

Welcome to your first Bootstrap lecture! 🎉  
In this session, you’ll learn how to build beautiful, responsive websites **faster and easier** using Bootstrap.

---

## 📌 What is Bootstrap?

Bootstrap is a **free and open-source CSS framework** that helps you build responsive and mobile-first websites quickly. It comes with:
- Pre-styled components (buttons, navbars, cards, etc.)
- A grid layout system
- Utility classes for spacing, colors, and more

---

## ⚙️ Getting Started with Bootstrap

You can include Bootstrap in your project using a **CDN**:

```html
<!-- Add this in the <head> of your HTML -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
```

👉 This gives you access to all Bootstrap features instantly without downloading anything.

---

## 🧱 Grid System Basics

Bootstrap uses a **12-column grid** to build responsive layouts.

```html
<div class="container">
  <div class="row">
    <div class="col-md-6">Left Side</div>
    <div class="col-md-6">Right Side</div>
  </div>
</div>
```

You can change the number based on screen size using:
- `col-sm-` for small devices
- `col-md-` for medium
- `col-lg-` for large
- `col-xl-` for extra large

---

## 🎨 Common Bootstrap Components

### ✅ Buttons

```html
<button class="btn btn-primary">Primary Button</button>
<button class="btn btn-danger">Danger Button</button>
```

---

### ✅ Alerts

```html
<div class="alert alert-success">Success! You did it!</div>
<div class="alert alert-warning">Be careful!</div>
```

---

### ✅ Navbar

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">MySite</a>
</nav>
```

---

### ✅ Cards

```html
<div class="card" style="width: 18rem;">
  <img src="https://via.placeholder.com/150" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Card Title</h5>
    <p class="card-text">Some quick content.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>
```

---

### ✅ Forms

```html
<form>
  <div class="mb-3">
    <label for="email" class="form-label">Email address</label>
    <input type="email" class="form-control" id="email" placeholder="name@example.com">
  </div>
</form>
```

---

## 📱 Responsive Design

Bootstrap is mobile-first. Try resizing your browser after adding this:

```html
<div class="row">
  <div class="col-12 col-md-4">Left</div>
  <div class="col-12 col-md-8">Right</div>
</div>
```

---

## 🛠️ Utility Classes

Make changes easily using helper classes.

- **Spacing:** `m-3` (margin), `p-2` (padding)
- **Colors:** `bg-primary`, `text-white`
- **Text Alignment:** `text-center`
- **Display:** `d-flex`, `d-none`

```html
<p class="text-center text-success m-4">Centered and green text with margin</p>
```

---

## 📚 Extra Resources

- [📘 Bootstrap Docs](https://getbootstrap.com/)
- [🎯 Bootstrap Cheat Sheet](https://bootstrap-cheatsheet.themeselection.com/)
- [🌐 CodePen Bootstrap](https://codepen.io/search/pens?q=bootstrap)

---

Feel free to ask questions and experiment. Bootstrap is like having a CSS superpower! 🦸‍♀️
```