# CSS Layouts & Responsive Web Design

## Overview
This project demonstrates modern CSS layout techniques using Flexbox and Grid to create a fully responsive webpage. The implementation follows best practices for responsive web design, ensuring optimal viewing across desktop, tablet, and mobile devices.

## Objective
Build a responsive multi-section webpage that uses both Flexbox and CSS Grid for layout while demonstrating adaptive content across various screen sizes.

## What I Practiced
- Structuring content using Flexbox for 1D layouts
- Using CSS Grid for complex 2D layouts (overall page structure)
- Applying responsive design techniques with media queries and relative units
- Creating adaptive layouts that respond to different screen sizes

## Implementation Details

### HTML Structure
The webpage includes these semantic sections:
- Header with title and description
- Navigation menu
- Main content area with card components
- Sidebar with additional information
- Footer with copyright information

### CSS Techniques

#### Flexbox Implementation
- **Navigation menu**: Horizontal on desktop/tablet, vertical on mobile
- **Content cards**: Flexible internal layout with consistent spacing
- **Footer content**: Responsive alignment of elements

#### CSS Grid Implementation
- **Overall page layout**: Grid template areas define the page structure
- **Responsive grid**: Layout changes at breakpoints (900px, 600px, 400px)
- **Content grid**: Adaptive card layout that responds to screen size

#### Responsive Design
- **Media queries**: Three breakpoints for desktop, tablet, and mobile
- **Relative units**: Use of %, rem, and em for flexible sizing
- **Fluid layouts**: Elements resize proportionally to viewport

## File Structure
```
├── index.html      
├── style.css       
└── README.md       
```
- [index.html](index.html)
- [style.css](style.css)