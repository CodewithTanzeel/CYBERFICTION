# CYBERFICTION

**CYBERFICTION** is an interactive web experience that merges the narrative of the metaverse with advanced web animations and scroll interactions. This project leverages GSAP and Locomotive Scroll to create a smooth and immersive storytelling environment.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## Introduction
CYBERFICTION aims to be a decentralized community that can create new values and profits through play in the virtual world. The project emphasizes cooperation and shared enjoyment, breaking down barriers of age, gender, region, and status.

## Features
- **Smooth Scrolling:** Implemented using Locomotive Scroll for a seamless scroll experience.
- **GSAP Animations:** Rich animations to enhance the storytelling aspect.
- **Canvas Animation:** Utilizes HTML5 Canvas to create a dynamic visual experience.
- **Responsive Design:** Adaptable to various screen sizes.

## Technologies Used
- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **GSAP (GreenSock Animation Platform)**
- **Locomotive Scroll**

## Installation
To set up the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/CYBERFICTION.git
   cd CYBERFICTION
   ```

2. **Open the project:**
   Open the `index.html` file in your preferred browser to view the project.

## Usage
The project consists of multiple sections, each contributing to the narrative of CYBERFICTION. The primary functionalities are managed by GSAP and Locomotive Scroll, providing a fluid animation and scroll experience.

### Local Development
1. **Install dependencies:**
   If you use a package manager like npm or yarn, you can initialize the project and install dependencies:
   ```bash
   npm install
   ```
   (Make sure to add a `package.json` with the required dependencies if not already present.)

2. **Run a local server:**
   You can use a local server to serve the files. One simple way is using the VS Code Live Server extension.

## Project Structure
The project is structured as follows:
```
CYBERFICTION/
│
├── index.html           # Main HTML file
├── style.css            # Main CSS file
├── script.js            # Main JavaScript file
├── assets/              # Directory for images and other assets
│   ├── male0001.png     # Example image file
│   ├── ...
│   └── male0299.png     # Example image file
└── README.md            # Project README file
```

### HTML
The HTML structure includes the main navigation, multiple sections (`#page`, `#page1`, `#page2`, `#page3`), and a canvas element for animations.

### CSS
The CSS file contains styles for the layout and animations. Key components include:
- `#main` for the main container
- `#nav` for navigation
- `#page`, `#page1`, `#page2`, `#page3` for different sections

### JavaScript
The JavaScript file manages the animations and scroll interactions:
- **Locomotive Scroll:** Initializes and configures smooth scrolling.
- **GSAP:** Handles frame-by-frame canvas animations and scroll-triggered effects.
- **Canvas Rendering:** Dynamically adjusts and renders images on the canvas based on scroll position.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

This detailed `README.md` provides a comprehensive overview of the project, making it easier for others to understand, set up, and contribute to the project.
