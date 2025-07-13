# TNEB Bill Calculator

A modern, responsive electricity bill calculator for Tamil Nadu Electricity Board (TNEB) tariff rates.

![TNEB Calculator Preview](assets/screenshots/calculator-preview.png)

## 🌟 Features

- **Accurate Calculations** - Based on latest TNEB tariff rates (effective July 1, 2024)
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Modern UI** - Clean, professional interface with smooth animations
- **Keyboard Support** - Full keyboard navigation and input support
- **Detailed Breakdown** - Shows unit-wise calculation breakdown
- **WordPress Ready** - Easy integration with WordPress websites
- **No Dependencies** - Pure HTML, CSS, and JavaScript

## 🚀 Live Demo

Visit the live calculator: [https://unifiedpensionschemes.com/tneb-bill-calculator/](https://unifiedpensionschemes.com/tneb-bill-calculator/)

## 📋 TNEB Tariff Structure (July 2024)

| Unit Range | Rate (₹/unit) | Description |
|------------|---------------|-------------|
| 0 - 100    | Free          | First 100 units free |
| 101 - 200  | ₹2.35         | Next 100 units |
| 201 - 400  | ₹4.70         | Next 200 units |
| 401 - 500  | ₹6.30         | Next 100 units |
| 501 - 600  | ₹8.40         | Next 100 units |
| 601 - 800  | ₹9.45         | Next 200 units |
| 801 - 1000 | ₹10.50        | Next 200 units |
| 1001+      | ₹11.55        | Above 1000 units |

## 🛠️ Installation

### Option 1: Direct HTML
1. Download or clone this repository
2. Open `index.html` in your web browser
3. Start calculating your TNEB bill!

### Option 2: WordPress Integration
See [WordPress Installation Guide](docs/installation.md) for detailed instructions.

### Option 3: Custom Integration
1. Include the CSS file: `<link rel="stylesheet" href="css/style.css">`
2. Include the JS file: `<script src="js/calculator.js"></script>`
3. Add the HTML structure from `index.html`

## 📖 Usage

1. **Enter Units**: Use the number pad or keyboard to enter consumed units
2. **Calculate**: Click "Calculate Bill" or press Enter
3. **View Results**: See detailed breakdown of your electricity bill
4. **Clear**: Use the clear button or Escape key to reset

### Keyboard Shortcuts
- **Numbers (0-9)**: Input digits
- **Decimal (.)**: Add decimal point
- **Enter**: Calculate bill
- **Escape**: Clear calculator
- **Backspace**: Delete last digit

## 🔧 Customization

### Colors
Edit the CSS variables in `css/style.css`:
```css
:root {
  --primary-color: #805ad5;
  --secondary-color: #38b2ac;
  --accent-color: #e53e3e;
  --background-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
