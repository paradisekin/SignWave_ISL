# SignWave ISL 🤟

Real-time Indian Sign Language detection system powered by YOLOv8 with a Progressive Web App interface.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8+-green.svg)

## Features

- ✅ Real-time ISL gesture recognition using YOLOv8
- ✅ Multiple detection modes (webcam, image, video)
- ✅ Progressive Web App with offline support
- ✅ Separate interfaces for teachers and learners
- ✅ Responsive, cross-platform design

## Quick Start

**Installation:**
```bash
git clone https://github.com/paradisekin/SignWave_ISL.git
cd SignWave_ISL
pip install ultralytics opencv-python numpy
```

**Run Detection:**
```bash
python detect-2.py          # Live webcam
python detect-image2.py     # Image detection
python detect-3.py          # Advanced detection
```

**Web Interface:**
Open `index.html` or `teacher.html` in your browser. Install as PWA for offline access.

## Project Structure
```
SignWave_ISL/
├── detect-*.py           # Python detection scripts
├── index.html           # Main interface
├── teacher.html         # Teacher interface
├── css/, js/, html/     # Frontend assets
├── manifest.json        # PWA configuration
└── serviceworker.js     # Offline support
```

## Technologies

**Backend:** YOLOv8, OpenCV, Python  
**Frontend:** HTML/CSS/JavaScript, PWA, Service Workers

## Contributing

Fork the repo, create a feature branch, and submit a pull request. All contributions welcome!

## License

MIT License - see [LICENSE](LICENSE)

## Author

**Utkarsh Kumar** - [paradisekin](https://github.com/paradisekin)

---

*Made for accessible communication. Give it a ⭐ if helpful!*
