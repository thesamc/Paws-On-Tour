# Paws On Tour - web app

An interactive web application for exploring Texas State University's campus landmarks and locations. Built with Vue.js and Leaflet maps.

## 🌟 Features

- Interactive campus map with location markers
- Detailed information about 18 campus landmarks
- Search functionality for finding specific locations
- Multiple sorting options (Walking Order, Alphabetical, Location)
- Responsive design for mobile and desktop viewing
- Turn-by-turn walking directions between landmarks
- Photo galleries for each location
- Integration with OpenStreetMap via Leaflet.js

## 🛠️ Technologies

- Vue.js 2.x
- Vue Router 3.x
- Leaflet.js for mapping
- Bootstrap 5.3
- Custom CSS with CSS Variables
- Mobile-first responsive design

## 📍 Landmarks Included

- Campus buildings (Old Main, LBJ Student Center, etc.)
- Dining facilities (Harris, Jones, Commons)
- Recreation areas (Student Rec Center, Sewell Park)
- Historic locations (LBJ Statue, Bobcat Statue)
- Hidden gems (The Hammocks, Glade Amphitheater)
- Athletic facilities (Bobcat Stadium)
- Natural attractions (The Meadows Center)

## 🚀 Getting Started

1. Clone the repository
2. Open `index.html` in a web browser
3. No build process required - all dependencies are loaded via CDN

## 💻 Dependencies

```json
{
  "dependencies": {
    "vue": "^2.x",
    "vue-router": "^3.x",
    "leaflet": "latest",
    "bootstrap": "^5.3.0-alpha1"
  }
}
```

## 📱 Responsive Design

- Mobile-first approach
- Breakpoints at 768px for tablet/desktop
- Optimized navigation for all screen sizes
- Fluid typography and spacing

## 🎨 Customization

The application uses CSS variables for easy theming:

```css
:root {
  --primary: #501214;    /* Maroon */
  --secondary: #6a5638;  /* Gold */
  --accent: #d2b650;     /* Light Gold */
  --background: #f8f9fa; /* Light Gray */
  --text: #2d3748;      /* Dark Gray */
  --light: #f4f1ed;     /* Off White */
}
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Texas State University for location information
- OpenStreetMap contributors
- Vue.js and Leaflet.js communities

## 📞 Contact

For questions or feedback, please open an issue in the repository.
