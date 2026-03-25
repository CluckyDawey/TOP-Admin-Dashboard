# TOP-Admin-Dashboard

Guided project by TheOdinProject to test student's knowledge with CSS Grid.

## Project Overview

This is an admin dashboard interface built with HTML5, CSS3 (CSS Grid), and semantic structure. The dashboard demonstrates modern web design principles including responsive layout, component-based styling, and visual hierarchy.

## Features

- **Responsive Layout**: CSS Grid-based layout that adapts to different screen sizes
- **Sidebar Navigation**: Blue sidebar with primary and secondary navigation menus
- **Search Bar**: Quick search functionality in the header
- **Welcome Section**: User greeting with action buttons
- **Projects Grid**: 2-column layout showcasing project cards with interactive elements
- **Announcements Panel**: Side panel with latest announcements
- **Trending Section**: Shows trending projects and users
- **Card Interactions**: Hover effects on project cards and buttons
- **Accessibility**: Semantic HTML structure with proper heading hierarchy

## Project Structure

```
TOP-Admin-Dashboard/
├── index.html       # Main HTML structure
├── styles.css       # Complete CSS styling (CSS Grid layout)
├── README.md        # Project documentation
└── Images/
    └── dashboard-project.png  # Design reference
```

## Layout Architecture

### Grid System
The main layout uses a two-column grid:
- **Column 1**: Sidebar (fixed width)
- **Column 2**: Main content area (flexible)

The main content uses a nested grid:
- **Left**: Projects section (2-column grid for cards)
- **Right**: Sidebar with announcements and trending

### Key Sections

1. **Sidebar**
   - Dashboard logo and branding
   - Primary navigation (Home, Profile, Messages, History, Tasks, Communities)
   - Secondary navigation (Settings, Support, Privacy)

2. **Header**
   - Search bar
   - Notification icon
   - User profile section

3. **Welcome Section**
   - User avatar and greeting
   - Action buttons (New, Upload, Share)

4. **Projects Grid**
   - 6 project cards in a 2-column layout
   - Each card includes title, description, and action buttons
   - Yellow left border accent
   - Hover animation effects

5. **Right Sidebar**
   - **Announcements**: 3 announcement items
   - **Trending**: 4 trending items with user avatars

## Responsive Breakpoints

- **Desktop** (1200px+): Full multi-column layout
- **Tablet** (768px - 1199px): Single column main grid with 2-column sidebar
- **Mobile** (480px - 767px): Fully stacked layout
- **Small Mobile** (<480px): Optimized for small screens

## Styling Features

- Modern color scheme with blue primary (#1e88e5)
- Gold accent color for card borders (#ffc107)
- Subtle shadows for depth
- Smooth transitions and hover effects
- Icon integration using SVG
- Typography hierarchy with varied font sizes and weights

## Browser Compatibility

- Chrome/Chromium 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Future Enhancements

- Add JavaScript interactivity
- Implement dark mode toggle
- Add data visualization charts
- Mobile menu toggle
- User authentication
- Backend integration
