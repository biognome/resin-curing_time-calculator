# Resin Curing Time Calculator

This project is a simple **standalone HTML + JavaScript application** that helps estimate optimal curing times for resin 3D prints. It is designed to be lightweight, portable, and usable directly in any modern web browser.

---

## Features
- **Resin type selection** with preloaded categories (standard, tough, flexible, clear, etc.).
- **Curing station selection** including popular machines (Formlabs Form Cure, Anycubic Wash & Cure, Elegoo Mercury, Phrozen Cure, DIY UV boxes, and more).
- **Size-based scaling** – accounts for the largest dimension of your print.
- **Estimated curing time** output in `hh:mm:ss` format.
- **Local storage support** – save your last-used resin, station, and size.
- **Responsive design** with TailwindCSS for desktop and mobile use.

---

## Usage
1. Clone this repository or download the HTML file.
2. Open the `index.html` file in any modern browser (Chrome, Edge, Firefox, Safari).
3. Select:
   - Resin type
   - Curing station
   - Approximate maximum dimension of your print (in mm)
4. Click **Enter** to calculate curing time.
5. (Optional) Click **Save settings** to store your preferences locally.

---

## Development
- Written in plain **HTML, CSS (Tailwind)**, and **vanilla JavaScript**.
- No build process, frameworks, or external dependencies (aside from Tailwind CDN).
- Easy to modify – just edit the `index.html` file.

---

## Disclaimers
- Times provided are **heuristic estimates**, not manufacturer specifications.
- Always consult your resin’s **technical data sheet** and perform test curing.
- Environmental factors (resin formulation, wall thickness, curing wavelength, temperature, station power) can significantly affect results.

---

## License
This project is released under the **MIT License**. You are free to use, modify, and distribute it with attribution.
