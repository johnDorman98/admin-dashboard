# Admin Dashboard

A modern admin dashboard template built with HTML, CSS, and vanilla JavaScript. This project provides a clean, professional interface for managing projects, user interactions, and system settings. **Note: Currently optimized for desktop view - full responsive design is planned for future updates.**

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Dashboard Overview](#dashboard-overview)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Technologies Used](#technologies-used)
- [File Descriptions](#file-descriptions)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [License](#license)

## 📖 About

This project was completed as part of [The Odin Project](https://www.theodinproject.com/) curriculum, specifically the Intermediate HTML and CSS course. It demonstrates proficiency in modern web development techniques including semantic HTML, CSS Grid and Flexbox layouts, and responsive design principles.

## ✨ Features

- **Desktop-Optimized Design**: Clean and professional dashboard interface optimized for desktop viewing
- **Modern UI**: Intuitive navigation and user interface design
- **Sidebar Navigation**: Organized navigation menu with main and footer sections
- **Header Section**: Includes search bar, notifications, user profile, and action buttons
- **Project Cards**: Display project information with quick action buttons
- **Custom Typography**: Uses Inter font family for optimal readability
- **Theme Support**: CSS variables for easy color customization
- **Icon Integration**: SVG icons throughout the interface for visual clarity
- **Accessibility**: Semantic HTML structure with proper alt text for images

## 🎯 Dashboard Overview

This admin dashboard template provides a comprehensive interface for managing various aspects of a web application or service:

### Navigation & Layout

- **Sidebar**: Quick access to main sections (Home, Profile, Messages, History, Tasks, Communities)
- **Header**: Search functionality, notifications, user profile, and action buttons
- **Main Content**: Project showcase area with interactive cards

### Interactive Elements

- **Search Bar**: Global search functionality (UI ready for implementation)
- **Notification Bell**: User notification indicator (UI placeholder)
- **Action Buttons**: New, Upload, and Share buttons (UI ready for implementation)
- **Project Cards**: Individual project displays with star, view, and share options

### User Experience

- **Responsive Typography**: Professional Inter font family throughout
- **Consistent Iconography**: SVG icons for visual clarity and scalability
- **Color-Coded Interface**: Primary blue theme with accent colors
- **Semantic Structure**: Proper HTML5 structure for accessibility

## 📁 Project Structure

```
admin-dashboard/
├── index.html           # Main HTML file with dashboard structure
├── style.css            # Complete styling and layout
├── README.md            # This file
├── assets/
│   ├── fonts/           # Custom font files (Inter)
│   │   ├── inter-v20-latin-regular.woff2
│   │   ├── inter-v20-latin-500.woff2
│   │   └── inter-v20-latin-700.woff2
│   └── icons/           # SVG icon files
│       ├── view-dashboard.svg
│       ├── home-heart.svg
│       ├── account.svg
│       ├── message-alert-outline.svg
│       ├── history.svg
│       ├── file-check.svg
│       ├── account-group.svg
│       ├── cog.svg
│       ├── help-box.svg
│       ├── shield-account.svg
│       ├── magnify.svg
│       ├── bell.svg
│       ├── account-circle.svg
│       ├── star-outline.svg
│       ├── eye-outline.svg
│       └── share-all.svg
└── design_files/        # Design assets and mockups
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies or build tools required

### Live Demo

View the live demo hosted on GitHub Pages: [Admin Dashboard Demo](https://johndorman98.github.io/admin-dashboard/)

### Local Development

1. Clone or download the project:

   ```bash
   git clone https://github.com/johnDorman98/admin-dashboard.git
   cd admin-dashboard
   ```

2. Open the project in your browser:
   - Double-click `index.html` to open directly
   - Or use a local server:

     ```bash
     # Using Python 3
     python -m http.server 8000

     # Using Node.js (http-server)
     npx http-server
     ```

3. Navigate to `http://localhost:8000` (or the appropriate port)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with CSS variables, Grid, and Flexbox
- **SVG Icons**: Scalable vector graphics for icons
- **Inter Font**: Professional, open-source font family
- **Vanilla JavaScript**: Ready for custom functionality integration

## 📄 File Descriptions

### index.html

The main HTML file containing:

- **Sidebar**: Navigation menu with logo and links to main sections (Home, Profile, Messages, History, Tasks, Communities) and footer sections (Settings, Support, Privacy)
- **Header**: Search bar, notification bell, user info section, greeting message, and action buttons
- **Main Content**: Project cards with descriptions and action buttons
- **Layout**: Dashboard container using semantic HTML structure

### style.css

Complete stylesheet featuring:

- **CSS Resets**: Consistent styling across all browsers
- **CSS Variables**: Theme colors and spacing for easy customization
- **Font Configuration**: @font-face declarations for Inter font family
- **Layout Styles**: Grid and flexbox layouts for dashboard organization
- **Component Styling**: Buttons, cards, navigation, and typography
- **Responsive Design**: Media queries for mobile-first approach

## 🎨 Customization

### Color Scheme

Modify the CSS variables in `:root` to change the color theme:

```css
:root {
  --color-primary: #1565c0; /* Primary blue */
  --bg-dashboard: #e2e8f0; /* Dashboard background */
  --bg-sidebar: #1565c0; /* Sidebar background */
  --bg-card: #ffffff; /* Card background */
  --text-main: #1e293b; /* Main text color */
  --text-muted: #64748b; /* Secondary text color */
  --accent: #f59e0b; /* Accent color */
}
```

### Adding New Icons

1. Place SVG files in `assets/icons/`
2. Reference in HTML:
   ```html
   <img src="./assets/icons/icon-name.svg" alt="Description" class="icon" />
   ```

### Modifying Fonts

The project uses the Inter font family. To change:

1. Replace font files in `assets/fonts/`
2. Update @font-face declarations in `style.css`
3. Modify the `font-family` property in the body style

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Future Enhancements

- **Responsive Design**: Full mobile and tablet optimization
- JavaScript functionality for interactive features
- Backend integration for dynamic data
- User authentication system
- Dark mode theme support
- Additional dashboard sections and widgets
- Performance optimization

## 📧 Support & Contribution

For questions, issues, or contributions, please refer to the project repository.

## 📜 License

This project is open source and available for educational and commercial use.
