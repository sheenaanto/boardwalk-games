# Boardwalk Games

![Boardwalk Games](assets/images/logo-sm.png)

Boardwalk Games is your ultimate gaming retreat, designed for casual gamers, enthusiasts, and student gatherings. This website provides information about our board game café, services, game library, and booking system.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Pages](#pages)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Design](#design)
- [Credits](#credits)

## About

Boardwalk Games is a modern, responsive website for a board game café that offers:
- A vast library of board games available for rent or purchase
- Event hosting and gaming experiences
- Online booking system for reservations
- Comprehensive information about services and offerings

## Features

### Core Features
- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Interactive Navigation**: Fixed navigation bar with smooth scrolling and mobile-friendly hamburger menu
- **Image Carousels**: Dynamic image sliders showcasing games and venue atmosphere
- **Booking System**: User-friendly booking enquiry form with validation
- **Game Library**: Browse available board games with detailed information
- **Contact Information**: Easy access to location, contact details, and social media links

### Technical Features
- Bootstrap 5 framework for responsive grid and components
- Custom CSS with CSS variables for consistent theming
- Accessible HTML5 semantic markup
- SEO-optimized meta descriptions
- Favicon support across devices
- Form validation and user feedback

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with modern features
- **Bootstrap 5.3**: Responsive framework and components
- **Google Fonts**: Inter and Macondo font families
- **JavaScript**: Bootstrap's JavaScript for interactive components

## Pages

### 1. Home Page (`index.html`)
- Hero carousel with venue images
- Services section highlighting key offerings
- Events information
- Featured and new games showcase
- Contact section with location and business hours
- Social media integration

### 2. Game Library (`game-library.html`)
- Comprehensive game catalog
- Game categorization and display
- Visual game cards with information
- Call-to-action for booking

### 3. Booking Page (`booking.html`)
- Reservation enquiry form
- Date and time selection
- Group size input
- Special requirements field
- Form submission with validation

### 4. Success Page (`success.html`)
- Booking confirmation message
- Next steps information
- Navigation back to main site

## Project Structure

```
boardwalk-games/
│
├── index.html              # Home page
├── game-library.html       # Game library page
├── booking.html            # Booking enquiry page
├── success.html            # Booking confirmation page
├── README.md               # Project documentation
│
└── assets/
    ├── css/
    │   └── style.css       # Custom styles
    │
    └── images/
        ├── logo-sm.png                          # Logo image
        ├── logo-sm-white.png                    # White logo variant
        ├── favicon-16x16.png                    # Favicon 16x16
        ├── favicon-32x32.png                    # Favicon 32x32
        ├── apple-touch-icon.png                 # Apple touch icon
        ├── boardwalk-games-carousel-image-*.webp # Carousel images
        ├── game-library-carousel-*.webp         # Game library images
        ├── fav-games-*.webp                     # Featured games
        ├── new-games-*.webp                     # New arrivals
        └── services-*.webp                      # Services images
```

## Installation

1. Clone or download the repository
2. No build process required - this is a static website
3. Open `index.html` in a web browser to view the site

```bash
# Clone the repository (if using Git)
git clone https://github.com/sheenaanto/boardwalk-games.git

# Navigate to the project directory
cd boardwalk-games

# Open in browser
start index.html
```

## Usage

### Local Development
- Simply open any HTML file in a modern web browser
- No server required for basic functionality
- For form submission to work, integrate with a backend service or form handler

### Navigation
- Use the navigation bar to move between pages
- Click "Book now" button to access the booking form
- Browse the game library to explore available games
- Scroll to sections on the home page using navigation links

## Design

### Color Scheme
- **Primary Color**: `#3a2620` (Dark Brown) - Main text and headings
- **Secondary Color**: `#aa9581` (Light Brown) - Accents
- **Highlight Color**: `#416a8e` (Blue) - Interactive elements
- **Highlight Color Light**: `#7a9fc2` (Light Blue) - Hover states

### Typography
- **Primary Font**: Inter (sans-serif) - Body text
- **Secondary Font**: Macondo (cursive) - Headings and branding

### Layout
- Mobile-first responsive design
- Bootstrap grid system
- Flexbox for component alignment
- Sticky footer implementation

## Browser Compatibility

The website is compatible with:
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Safari (latest)
- Microsoft Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Future Enhancements

Potential features for future development:
- Backend integration for booking system
- User accounts and login functionality
- Online payment integration
- Real-time game availability checker
- Customer reviews and ratings
- Newsletter subscription
- Blog or news section
- Loyalty program

## Credits

### Content
- Website content created for Boardwalk Games

### Media
- Images stored in `assets/images/` directory
- Favicon generated using [Favicon.io](https://favicon.io)

### Frameworks & Libraries
- [Bootstrap 5.3](https://getbootstrap.com/) - CSS Framework
- [Google Fonts](https://fonts.google.com/) - Typography

### Tools
- [Autoprefixer](https://autoprefixer.github.io/) - CSS vendor prefixing
- Visual Studio Code - Development environment

## License

This project is developed as part of a Code Institute project.

## Contact

For questions or feedback about this project, please use the contact information provided on the website.

---

**Note**: This is a student project created for educational purposes as part of the Code Institute curriculum.