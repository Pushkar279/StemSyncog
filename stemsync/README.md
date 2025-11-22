# StemSync Website

A lightweight, responsive website for **StemSync** digital marketing agency.

## Structure

```
stemsync/
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── images/
│       └── logo.png (add your logo here)
├── index.html
├── about.html
├── services.html
├── contact.html
└── README.md
```

## Color Palette

| Variable | Color |
|----------|-------|
| `--clr-dark` | `#2c2218` |
| `--clr-brown` | `#8b693c` |
| `--clr-light-brown` | `#b28c5d` |
| `--clr-bg` | `#ffffff` |
| `--clr-light` | `#f9f7f5` |

## Getting Started

1. Clone or download this repository.
2. Place your `logo.png` inside `assets/images/`.
3. Open `index.html` in your browser.
4. (Optional) Serve locally with a simple HTTP server:

```bash
# Using Python 3
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Contact Form
The contact form is configured for Formspree. Replace `{your-id}` in `contact.html` action with your unique Formspree endpoint.
