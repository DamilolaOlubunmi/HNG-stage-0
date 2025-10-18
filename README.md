# Interactive Profile Card

A responsive, modern profile card implementation with real-time clock display and interactive elements.

## Overview

This project creates a stylish profile card that displays:
- User avatar
- Name and bio
- Real-time clock (updating every second in milliseconds)
- Social media links (Twitter, GitHub, LinkedIn)
- Personal details (Hobbies and Dislikes)
- Interactive hover effects

## Files Structure

- `index.html` - Main HTML structure with semantic markup and test attributes
- `style.css` - Responsive styling with glass-morphism effect
- `script.js` - JavaScript for real-time clock functionality

## Features

- **Responsive Design**: Adapts seamlessly to different screen sizes
- **Glass Morphism**: Modern UI with backdrop-filter blur effect
- **Interactive Elements**: Hover animations on card and social links
- **Real-time Updates**: Live clock display in milliseconds
- **Accessible Markup**: Semantic HTML with proper ARIA attributes
- **Test-Ready**: Includes data-testid attributes for automated testing

## Technical Implementation

### HTML
- Semantic structure using `article`, `figure`, `nav`, and `section` elements
- Test-friendly attributes (data-testid) for QA purposes
- Responsive image handling with proper alt text

### CSS
- Flexbox layout for responsive design
- Glass-morphism effect using backdrop-filter
- Interactive hover states
- Mobile-first responsive breakpoints
- Custom color scheme with #7494fd as primary color

### JavaScript
- Real-time clock implementation using `Date.now()`
- Interval-based updates every second
- DOM manipulation using querySelector

## Running Locally

1. Clone or download the repository
2. Open `index.html` in a modern web browser
3. No build tools or server required

## Browser Compatibility

Requires modern browsers that support:
- Backdrop-filter
- Flexbox
- CSS transitions
- ES6 JavaScript

## Testing

The application includes data-testid attributes for automated testing implementation.

## License

Free to use and modify for personal and commercial projects.