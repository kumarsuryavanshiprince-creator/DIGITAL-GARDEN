# 🌌 Glass UI Dashboard Web App

A modern frontend web application with a glassmorphism design, demo login system, dashboard, and profile page.  
Background videos are hosted on an **external platform** to avoid large file size issues on GitHub.

---

## 🔐 Demo Login Credentials

- **User ID:** Prince  
- **Password:** 1234  

*(For demo/testing purposes only)*

---

## ✨ Features

- Glassmorphism UI
- Video-style background (externally hosted)
- Demo login flow
- Dashboard with sidebar
- Profile page with skills & social icons
- Responsive design
- Logout & page navigation

---

## 🖥️ Pages

- `index.html` → Login  
- `dashboard.html` → Dashboard  
- `profile.html` → Profile  

---

## 🎥 Video Hosting (Important)

Background videos are **NOT stored in this repository**.  
They are hosted on an **external service (CDN / cloud video hosting)** and loaded via direct video URLs inside the HTML.

This keeps the repository:
- Lightweight
- Fast to clone
- Within GitHub upload limits

Example:
```html
<video autoplay muted loop playsinline>
  <source src="https://external-video-link.mp4" type="video/mp4">
</video>
