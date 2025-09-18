# Web-Based Projectile Motion Simulator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![CSS3](https://img.shields.io/badge/CSS3-Responsive-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/CSS)

An interactive web-based physics simulation tool for visualizing and analyzing projectile motion, developed as part of a Final Year Physics Project at Lagos State University.

## 🎯 Overview

This simulator demonstrates fundamental projectile motion principles through real-time visualization, allowing users to experiment with various launch parameters and observe their effects on trajectory, velocity components, and motion dynamics.

## ✨ Features

### Core Functionality
- **Real-time trajectory visualization** with parabolic path rendering
- **Dynamic velocity vector display** showing horizontal (vx), vertical (vy), and resultant components
- **Interactive parameter controls** for initial conditions
- **Multi-mode data display** (Position, Speed, Acceleration, Force, Energy)
- **Slow motion capability** for detailed analysis

### Technical Features
- **Responsive design** compatible with desktop, tablet, and mobile devices
- **Dynamic scaling** that automatically adjusts viewport based on trajectory bounds
- **Professional UI/UX** with modern gradient design and smooth animations
- **Cross-browser compatibility** (Chrome, Firefox, Safari, Edge)
- **No external dependencies** - runs entirely in the browser

## 🚀 Live Demo

[View Live Simulator](https://projectile-motion-simulations.vercel.app/)

## 📊 Physics Implementation

The simulator implements classical mechanics equations:

- **Horizontal Motion**: `x(t) = x₀ + v₀cos(θ)t`
- **Vertical Motion**: `y(t) = y₀ + v₀sin(θ)t - ½gt²`
- **Range**: `R = (v₀² sin(2θ))/g`
- **Maximum Height**: `H = (v₀² sin²(θ))/(2g)`
- **Time of Flight**: `T = (2v₀ sin(θ))/g`

## 🛠️ Installation & Usage

### Quick Start
1. Clone the repository:
```bash
git clone https://github.com/Obomhese-Raphael/projectile-motion-simulations.git
```

2. Navigate to project directory:
```bash
cd projectile-motion-simulator (optional)
```

3. Open `index.html` in a web browser or serve via HTTP server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have live-server installed)
live-server
```

### Parameters

| Parameter | Range | Unit | Description |
|-----------|-------|------|-------------|
| Initial Height | 0-50 | meters | Launch height above ground |
| Initial Speed | 0-50 | m/s | Launch velocity magnitude |
| Launch Angle | 0-90 | degrees | Angle above horizontal |
| Mass | 0.1-10 | kg | Projectile mass (affects force/energy calculations) |
| Gravity | 1-20 | m/s² | Gravitational acceleration |


## 🔧 Technical Specifications

### Technologies Used
- **HTML5 Canvas API** for 2D graphics rendering
- **Vanilla JavaScript (ES6+)** for physics calculations and interactivity
- **CSS3 with Grid/Flexbox** for responsive layout
- **Web Fonts (Inter)** for professional typography

### Browser Support
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

### Performance
- 60 FPS animation using `requestAnimationFrame`
- Optimized rendering with selective redrawing
- Minimal memory footprint (<2MB)

## 📚 Educational Use

This simulator is designed for:
- **Physics Education**: Visualizing projectile motion concepts
- **STEM Learning**: Interactive parameter exploration
- **Research**: Trajectory analysis and data collection
- **Demonstrations**: Classroom presentations and online learning

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

### Development Guidelines
- Follow existing code style and conventions
- Test across multiple browsers before submitting
- Update documentation for new features
- Ensure responsive design compatibility

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Obomhese Raphael Marvellous**
- Student ID: 210571052
- Institution: Lagos State University, Physics Department
- Project Type: Final Year Project (Bachelor of Science in Physics)
- Academic Session: 2024/2025

## 🏫 Academic Context

This web-based simulator was developed as part of a comprehensive final year project investigating interactive educational tools for physics education. The project explores the effectiveness of digital simulations in enhancing student understanding of classical mechanics concepts.

### Project Objectives
- Develop accessible physics simulation tools
- Bridge theoretical knowledge with practical visualization
- Enhance engagement through interactive learning
- Provide alternative educational resources for under-resourced environments

## 🐛 Known Issues

- Air resistance effects not implemented (intentional for educational focus)
- Vector display may overlap at extreme angles
- Mobile touch controls could be enhanced for better precision

## 🔮 Future Enhancements

- [ ] Air resistance modeling (advanced mode)
- [ ] Multiple projectile comparison
- [ ] Data export functionality (CSV/JSON)
- [ ] 3D trajectory visualization
- [ ] Multi-language support
- [ ] Offline progressive web app (PWA) capabilities

## 🙏 Acknowledgments

- Physics Department, Lagos State University
- Project Supervisors: Prof. Idowu Babatunde & Dr. Funmi Ometan
- Open source physics education community
- Web development resources and documentation

---

⭐ If you find this project useful for education or research, please consider giving it a star!

📧 For questions or collaboration inquiries, please open an issue or contact through the university or my personal mail - obomheser@gmail.com
