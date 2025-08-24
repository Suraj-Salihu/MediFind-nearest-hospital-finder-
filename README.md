# MediFind - Hospital Locator

## Overview

MediFind is a modern, responsive web application that helps users quickly locate the nearest hospitals and medical facilities. Designed for both emergency situations and regular healthcare needs, MediFind provides accurate distance calculations, contact information, and direct navigation options to medical facilities.

![MediFind Hospital Locator](https://img.shields.io/badge/Version-1.0.0-blue) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Features
- **GPS-Based Location Detection**: Automatically detects user's location to find the nearest hospitals
- **Distance Calculation**: Uses the Haversine formula for accurate distance measurements
- **Hospital Details**: Displays comprehensive information including address, phone numbers, and services
- **One-Click Actions**: Direct call functionality for emergencies and Google Maps integration for directions
- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Dark/Light Mode**: Toggle between color themes for comfortable viewing in different lighting conditions
- **User-Friendly Interface**: Clean, intuitive design with clear visual hierarchy

## How It Works
1. The application requests permission to access your location
2. Using the Haversine formula, it calculates distances to predefined hospitals
3. Results are sorted by proximity and displayed with relevant details
4. Users can get directions via Google Maps or call emergency numbers directly

## Technical Details

### Built With
- **HTML5**: Semantic markup for structure
- **CSS3**: Custom properties, Flexbox, Grid, and responsive design
- **JavaScript**: Geolocation API, distance calculations, and dynamic content rendering
- **Font Awesome**: Icons for enhanced UI
- **Google Maps**: Integration for navigation

### Algorithms

- **Haversine Formula**: Calculates great-circle distances between two points on a sphere given their longitudes and latitudes
- **Sorting Algorithm**: Orders hospitals by proximity to the user

### Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Installation

No installation required! MediFind runs directly in your web browser:

1. Download the `index.html` file
2. Open it in any modern web browser
3. Allow location access when prompted

## Usage

1. Click the "Find Hospitals Near Me" button
2. Allow location access when your browser prompts you
3. View the list of nearby hospitals sorted by distance
4. Use the "Get Directions" button to open navigation in Google Maps
5. Use the "Call Emergency" button to directly call the hospital's emergency line

## Customization

To add or modify hospitals, edit the `hospitals` array in the JavaScript section:

```javascript
const hospitals = [
  { 
    name: "Your Hospital Name", 
    lat: 00.000, 
    lon: 00.000,
    address: "Hospital Address",
    phone: "Phone Number",
    emergency: "Emergency Number",
    services: ["Service 1", "Service 2", "Service 3"]
  }
  // Add more hospitals as needed
];
```

## Privacy

MediFind respects user privacy:
- Location data is used only for finding nearby hospitals
- No location data is stored or transmitted to servers
- All processing happens locally in your browser

## Support

For support, bug reports, or feature requests, please contact:
- **Developer**: Suraj Salihu
- **GitHub**: [https://github.com/Suraj-Salihu](https://github.com/Suraj-Salihu)

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [GitHub repository](https://github.com/Suraj-Salihu) for more information.

## Acknowledgments

- Icons provided by [Font Awesome](https://fontawesome.com)
- Maps integration powered by [Google Maps](https://developers.google.com/maps)
- Inspired by the need for quick access to healthcare facilities in emergencies

---

**Disclaimer**: This application provides approximate locations and distances. Always verify information with official sources before making healthcare decisions. In emergencies, call your local emergency number immediately.