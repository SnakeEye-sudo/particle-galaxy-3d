# 🌌 Particle Galaxy 3D

> A stunning, interactive 3D particle galaxy with real-time physics simulation, mouse controls, and mesmerizing visual effects. Explore a universe of particles with gravity, orbital mechanics, and collision detection - all powered by Three.js WebGL for silky-smooth 60 FPS performance.

![License](https://img.shields.io/badge/license-MIT-green)
![Made with Three.js](https://img.shields.io/badge/Made%20with-Three.js-black)
![WebGL](https://img.shields.io/badge/WebGL-Enabled-blue)

## ✨ Features

🌠 **Interactive 3D Visualization**
- Thousands of particles forming a dynamic galaxy
- Smooth camera controls (mouse drag, scroll zoom)
- Real-time particle animation and rotation

🎮 **Advanced Physics Simulation**
- Gravity simulation with n-body physics
- Orbital mechanics for realistic particle behavior
- Collision detection and response
- Velocity and acceleration calculation

🎨 **Stunning Visual Effects**
- Neon color scheme with vibrant gradients
- Glow and bloom effects
- Trail effects for particle motion
- Dynamic lighting and shadows

📊 **Real-time Performance Metrics**
- Live FPS counter
- Particle count display
- Memory usage information
- Performance optimization

📱 **Fully Responsive**
- Works seamlessly on desktop, tablet, and mobile
- Touch gesture support (pinch to zoom, swipe to rotate)
- Auto-adjusting resolution for performance

⚡ **Performance Optimized**
- GPU-accelerated rendering with WebGL
- Efficient particle system with instancing
- Adaptive quality settings
- 60 FPS target on most devices

🎵 **Audio Reactive** (Coming Soon)
- Particle behavior responds to sound
- Microphone input support
- Music visualization mode

## 🚀 Live Demo

[🌐 View Live Demo](https://snakeeye-sudo.github.io/particle-galaxy-3d/)

## 📥 Installation

### Option 1: Use Online (Easiest)

Simply visit the [live demo link](https://snakeeye-sudo.github.io/particle-galaxy-3d/) and start exploring the galaxy!

### Option 2: Local Setup

```bash
# Clone the repository
git clone https://github.com/SnakeEye-sudo/particle-galaxy-3d.git

# Navigate to directory
cd particle-galaxy-3d

# Open in your browser
# If you have Python 3 installed:
python -m http.server 8000

# Then visit: http://localhost:8000
```

## 🎮 How to Use

### Mouse Controls
- **Left Click + Drag**: Rotate the galaxy
- **Scroll**: Zoom in/out
- **Right Click + Drag**: Pan the view
- **Double Click**: Reset view

### Keyboard Shortcuts
- **SPACE**: Pause/Resume animation
- **R**: Reset particle system
- **P**: Toggle pause
- **S**: Change color scheme
- **+/-**: Increase/decrease particle count

### Touch Controls (Mobile/Tablet)
- **Single Finger Drag**: Rotate
- **Two Finger Pinch**: Zoom
- **Two Finger Drag**: Pan

## 🛠️ Technologies Used

- **Three.js**: 3D graphics rendering engine
- **WebGL**: GPU-accelerated graphics
- **JavaScript (ES6+)**: Interactive logic
- **GLSL**: Custom vertex and fragment shaders
- **Canvas**: HTML5 rendering context

## 📦 Project Structure

```
particle-galaxy-3d/
├── index.html           # Main HTML file
├── style.css            # Styling (embedded)
├── script.js            # Application logic (embedded)
├── README.md            # This file
└── .gitignore           # Git ignore rules
```

## 🎨 Customization

Edit the configuration variables in `index.html` to customize:

```javascript
const CONFIG = {
  PARTICLE_COUNT: 5000,      // Number of particles
  PARTICLE_SIZE: 2,          // Size of each particle
  GRAVITY_STRENGTH: 0.5,     // Gravity force
  COLOR_SCHEME: 'neon',      // 'neon', 'sunset', 'ocean', 'cyberpunk'
  CAMERA_DISTANCE: 200,      // Initial camera distance
  ROTATION_SPEED: 0.0001,    // Auto-rotation speed
  GLOW_INTENSITY: 2.0,       // Bloom/glow effect strength
};
```

## 📊 Performance

- **Target FPS**: 60 FPS
- **Particle Limit**: 10,000+ (depends on hardware)
- **Memory Usage**: ~50-200 MB
- **Browser Support**: Chrome, Firefox, Safari, Edge (all modern versions)
- **Recommended**: GPU with 2GB+ VRAM

## 🌟 Features in Development

- [ ] Audio reactive particles
- [ ] Multiple galaxy formations
- [ ] Trail effects
- [ ] Time-lapse simulation
- [ ] Export to PNG/video
- [ ] VR support
- [ ] Mobile app version

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

MIT License - see LICENSE file for details

## 👨‍💻 Author

**Er. Sangam Krishna** (SnakeEye-sudo)
- GitHub: [@SnakeEye-sudo](https://github.com/SnakeEye-sudo)
- Portfolio: [snakeeye-sudo.github.io](https://snakeeye-sudo.github.io)
- Buy Me a Coffee: [buymeacoffee.com/snakeeye](https://buymeacoffee.com/snakeeye)

## 🙏 Acknowledgments

- Inspired by Bruno Simon's WebGL experiments
- Three.js community and documentation
- WebGL specifications and best practices
- Physics simulation algorithms from Game Development

## 📞 Support

If you found this project helpful:
- ⭐ Star the repository!
- 🐛 Report issues on GitHub
- 💬 Discuss improvements in discussions
- 🔄 Share with the community

---

**Made with 💜 by SnakeEye-sudo**

*Live, Learn, Build, Repeat!*
