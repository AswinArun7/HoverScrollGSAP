# Hoverscroll

A visually rich, GSAP-powered split-screen scroll animation demo with interactive tilt and flip effects, built using HTML, CSS, and JavaScript. This project demonstrates advanced scroll-based animations, mirrored panels, and a stylish overlay menu.

## Features
- Split-screen layout with mirrored scrolling panels
- GSAP and ScrollTrigger for smooth, snappy scroll animations
- Interactive tilt and flip card effects on images
- Animated overlay menu with curtain transitions
- Responsive design for modern browsers

## Demo
Open `src/views/animation.html` in your browser to see the animation in action.

## Project Structure
```
hoverscroll/
├── src/
│   └── views/
│       ├── animation.html
│       └── images/
│           ├── bottlecropback.png
│           ├── bottlecropfront.png
│           ├── E.png
│           ├── slide1.png
│           └── slide3.png
├── package.json
├── README.md
└── ...
```

## Getting Started
This project is a static HTML/CSS/JS demo. No build step is required.

### Prerequisites
- Modern web browser (Chrome, Firefox, Edge, Safari)
- [GSAP](https://greensock.com/gsap/) and [ScrollTrigger](https://greensock.com/scrolltrigger/) are loaded via CDN in the HTML file

### Running Locally
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/hoverscroll.git
   cd hoverscroll
   ```
2. Open `src/views/animation.html` directly in your browser.
   - For best results, use a local server (e.g. VSCode Live Server, Python's `http.server`, or Node's `http-server`) to avoid CORS issues with images.

   Example using Python 3:
   ```sh
   cd src/views
   python -m http.server 8000
   # Then visit http://localhost:8000/animation.html
   ```

## Customization
- Edit `src/views/animation.html` to change slides, images, or animation parameters.
- Place your own images in `src/views/images/` and update the HTML accordingly.

## License
MIT License

---
Feel free to fork and adapt for your own creative scroll-based web projects!
