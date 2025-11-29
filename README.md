# 🚀 Animated Navbar Component

A modern, fully animated navbar built with pure HTML, CSS, and vanilla JavaScript. Perfect for web projects that need an engaging and professional interface.

![Preview](https://img.shields.io/badge/Status-Ready-success?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Features

- 🎨 **Modern Design** - Glassmorphism with blur effects and transparency
- ⚡ **Smooth Animations** - Fluid transitions on hover and interactions
- 📱 **Responsive** - Automatically adapts to desktop and mobile
- 🎯 **Animated Dropdowns** - Drop-down menus with wow effects
- 🔍 **Search Dropdown** - Integrated search with suggestions
- 🛒 **Animated Badges** - Pulsing notifications and badges
- 🌟 **Shine Effects** - Continuous glowing animations
- 💾 **Zero Dependencies** - Pure HTML/CSS/JS, no libraries required

## 🎯 Demo

Simply open the `index.html` file in your browser to see the navbar in action!

## 🚀 Quick Start

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/bitspear-lab/animated-navbar.git
   cd animated-navbar
   ```

2. **Open the file**
   ```bash
   # Option 1: Open directly in browser
   open index.html
   
   # Option 2: Use a local server (recommended)
   npx serve
   # or
   python -m http.server 8000
   ```

3. **Start customizing!**

### Basic Usage

Simply copy the navbar HTML code into your project:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Project</title>
    <!-- Include the navbar CSS -->
    <link rel="stylesheet" href="path/to/navbar-styles.css">
</head>
<body>
    <!-- Insert the navbar here -->
    <nav class="navbar">
        <!-- Navbar code -->
    </nav>
    
    <!-- Your content -->
    
    <!-- Include the script -->
    <script src="path/to/navbar-script.js"></script>
</body>
</html>
```

## 🎨 Customization

### Colors

Modify color variables in the CSS:

```css
/* Main colors */
background: #1A2332;          /* Page background */
background: #0F1726;          /* Navbar background */
background: #0EA5E9;          /* Primary color (blue) */
color: #cbd5e1;               /* Secondary text */
color: white;                 /* Primary text */
```

### Logo

Replace the logo symbol:

```html
<div class="logo-box">✦</div>  <!-- Change the symbol here -->
<span>Brandify</span>          <!-- Change the name here -->
```

### Menu Items

Add or remove menu items:

```html
<li class="menu-item">
    <a href="#" class="menu-link">New Item</a>
</li>
```

### Dropdown

Add a new dropdown:

```html
<li class="menu-item">
    <a href="#" class="menu-link">
        Menu
        <span class="dropdown-arrow">▼</span>
    </a>
    <div class="dropdown">
        <a href="#" class="dropdown-item">
            <span class="icon">✨</span>
            <span>Item 1</span>
        </a>
        <!-- Add more items -->
    </div>
</li>
```

## 📱 Responsive Design

The navbar is fully responsive and automatically adapts:

- **Desktop (> 768px)**: Full menu visible
- **Mobile (< 768px)**: Hidden menu, only essential actions

### Mobile/Desktop Simulator

Use the red button in the top-right corner to test the mobile version!

```javascript
// Toggle mobile view
document.body.classList.toggle('mobile-view');
```

## 🎭 Included Animations

### Logo
- ⚙️ 360° rotation on hover
- ✨ Continuous shine effect

### Menu Links
- 📏 Animated blue line on hover
- ⬆️ Upward movement
- 🎨 Smooth color change

### Dropdown
- 🎪 Fade in + scale
- 🎯 180° rotating arrow
- ➡️ Lateral slide of items

### Buttons
- 🔄 Scale and rotation
- 💫 Pulsing badges
- ⚡ Shine effects

### Sign Up Button
- ✨ Continuous shine
- 🌟 Rotating icon
- 📏 Scale on hover

## 🛠️ Browser Compatibility

| Browser | Minimum Version | Support |
|---------|----------------|---------|
| Chrome  | 90+            | ✅ Full  |
| Firefox | 88+            | ✅ Full  |
| Safari  | 14+            | ✅ Full  |
| Edge    | 90+            | ✅ Full  |

## 📦 File Structure

```
animated-navbar/
├── index.html              # Main file
├── README.md              # This file
├── LICENSE                # MIT License
└── .gitignore            # Files to ignore
```

## 🎓 Instagram Tutorial

This project was created as an Instagram tutorial! Follow [@bitspear](https://instagram.com/bitspear) for:

- 📹 Step-by-step video tutorials
- 💡 Web development tips & tricks
- 🎨 Design inspiration
- 🚀 New components every week

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 💬 Support

Questions or issues?

- 📧 Email: support@bitspear.dev
- 💬 Instagram: [@bitspear](https://instagram.com/bitspear)
- 🐛 Issues: [GitHub Issues](https://github.com/bitspear-lab/animated-navbar/issues)

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🌟 Credits

Created with ❤️ by [BitSpear Lab](https://github.com/bitspear-lab)

---

### ⭐ If you like it, leave a star!

If this project was useful to you, consider leaving a ⭐ on GitHub!

---

**Made with 💙 by BitSpear Lab** | [Instagram](https://instagram.com/bitspear) | [GitHub](https://github.com/bitspear-lab)
