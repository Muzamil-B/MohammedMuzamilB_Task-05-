# Laundry Service Web App — Hero Section

A responsive landing page for a laundry service, featuring a navigation bar and a full-viewport hero section. Built with plain HTML and CSS (no Flexbox/Grid — uses `display: inline` / `inline-block` and viewport units).

## 📋 Features

### Navbar
- Logo on the left, navigation links (Home, Services, About Us, Contact Us) in the center/left area, and the user's name on the right
- Built using `display: inline` / `inline-block` (no Flexbox)

### Hero Section
- Two-column layout using `inline-block` divs
- **Left div:** Heading, description text, and a "Book a Service Today" call-to-action button
- **Right div:** Laundry-related image
- Sized using viewport units (`vh` / `vw`) so the entire section fits within the screen with no scrolling

## 🗂️ Project Structure

```
laundry-service/
├── index.html      # Page markup (navbar + hero section)
├── style.css       # Styling (inline display, viewport units)
└── README.md       # Project documentation
```

## 🛠️ Tech Stack

- HTML5
- CSS3 (`display: inline` / `inline-block`, `vh`/`vw` units — no Flexbox/Grid)

