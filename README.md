# Stylish Multi-Unit Converter

A clean, modern, and lightweight unit converter built with **Vanilla HTML, CSS, and JavaScript**. No external frameworks or libraries required.

## ✨ Features
- **Multi-Category Support**: Convert Distance, Liquid Volume, Area, Weight, and Digital Storage.
- **Smart Logic**: Uses a base-unit calculation system for high accuracy and clean code.
- **Responsive Design**: Works perfectly on mobile, tablet, and desktop.
- **Instant Results**: Conversion happens in real-time as you type.
- **Swap Feature**: Quickly switch "From" and "To" units with a single click.
- **Stylish UI**: Modern gradient background, soft shadows, and clean typography.

## 🚀 Quick Start
1. Clone the repository or download the `index.html` file.
2. Open `index.html` in any modern web browser.
3. Start converting!

## 🛠️ How to Add New Units
To add a new category (like Temperature or Time), simply update the `data` object in the `<script>` tag:

```javascript
data: {
  time: { 
    base: 'seconds', 
    units: { seconds: 1, minutes: 0.0166, hours: 0.000277 } 
  }
}
```

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
