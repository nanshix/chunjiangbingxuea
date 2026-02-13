# Project Blueprint: chunjiangbingxue

This document serves as a comprehensive technical specification for the chunjiangbingxue demonstration website for CHUNJIANG ice and snow theme park. It provides all necessary details for an AI agent to recreate the website from scratch.

## 5. Development Roadmap

### Phase 1: Foundation (Week 1)
- [ ] Create file structure and folders
- [ ] Build HTML templates for all pages
- [ ] Implement CSS design system
- [ ] Create responsive navigation system

### Phase 2: Content & Styling (Week 2)
- [ ] Populate content sections
- [ ] Style hero sections with winter theme
- [ ] Create photo placeholders in assets/pictures
- [ ] Implement footer with social links

### Phase 3: Interactive Features (Week 3)
- [ ] Add JavaScript for smooth scrolling
- [ ] Implement parallax effects
- [ ] Build image gallery functionality
- [ ] Create contact form validation

### Phase 4: Polish & Testing (Week 4)
- [ ] Optimize performance
- [ ] Test all browsers and devices
- [ ] Add loading animations
- [ ] Final content review

### Phase 5: Launch Preparation
- [ ] Set up local server for testing
- [ ] Test all booking flows
- [ ] Prepare for image assets
- [ ] Quality assurance checklist

## 1. Project Overview
- **Name:** chunjiangbingxueshijie (春江冰雪世界)
- **Concept:** A fun, exciting, must-go, kids best love, family friendly ice and snow theme park in shangzhi, harbin
- **Core Functionality:** Multi-page website showcasing the winter wonderland experience
- **Target Audience:** Chinese families, children, winter sports enthusiasts, tourists
- **Language:** Chinese content only (no English version needed)
- **Primary Goal:** Drive park visits and ticket bookings

## Important Notes
- **Language:** All content in Chinese, comments in English
- **Performance:** Fast loading and highly mobile-optimized
- **Deployment:** Push to https://github.com/nanshix/chunjiangbingxue

## 2. Technical Stack
- **Frontend:** Vanilla HTML5, Vanilla CSS3 (Custom Design System), Vanilla JavaScript (ES6+)
- **Data:** Images stored in assets/pictures folder
- **Environment:** Requires a local HTTP server for Fetch API functionality (e.g., Python `http.server`)
- **Layout:** Responsive design with mobile-first approach
- **Interactive Features:**
  - Smooth scrolling navigation
  - Parallax effects on hero sections
  - Image gallery with lightbox
  - Dynamic pricing calculator
  - Contact form validation

## 3. Design System (Aesthetics)
- **Style:** Winter wonderland theme with ice blues, cool whites, and crisp whites. Clean, modern, family-friendly design with rounded elements and playful accents
- **Color Palette:**
  - Primary: #E0F2FE (Ice Blue)
  - Secondary: #F0F9FF (Light Sky Blue)
  - Accent: #0EA5E9 (Sky Blue)
  - Text: #1E293B (Dark Slate)
  - Background: #FFFFFF (White)
- **Typography:**
  - Headings: Poppins (bold, playful)
  - Body: Inter (clean, readable)
- **Key UI Elements:**
  - Navigation bar with ice crystal icons
  - Hero banner with parallax effect
  - Feature cards with snowflake borders
  - Photo gallery with hover effects
  - "Book Now" buttons with gradient fills
  - Footer with social icons

## 4. Site Structure (Multi-page Layout)

### File Structure:
```
/
├── index.html              # Main landing page
├── about.html              # About the park
├── attractions.html        # Attractions and activities
├── gallery.html            # Photo gallery
├── tickets.html            # Pricing and booking
├── contact.html            # Contact information
├── css/
│   ├── style.css          # Main styles
│   └── style.css.map      # Source map
├── js/
│   ├── main.js             # JavaScript interactions
│   └── navigation.js       # Navigation logic
└── assets/
    └── pictures/          # Park images
        ├── hero/          # Hero section images
        ├── attractions/   # Attraction photos
        ├── gallery/       # Gallery photos
        └── logo/          # Brand logos
```

### Page Structure:
1. **index.html** - Landing Page
   - Hero section with "Welcome to Winter Wonderland" tagline
   - Quick overview of top attractions
   - "Explore Our World" CTA to attractions
   - Featured events/promotions

2. **about.html** - About The Park
   - Story and mission
   - Location and facilities
   - Safety information
   - Winter sports heritage

3. **attractions.html** - Attractions & Activities
   - Ice skating rink
   - Snow tubing area
   - Ice sculptures
   - Kids play zone
   - Adventure courses
   - Winter cafes

4. **gallery.html** - Photo Gallery
   - High-quality park photos
   - Visitor experiences
   - Seasonal events
   - Virtual tour option

5. **tickets.html** - Tickets & Pricing
   - Ticket types and prices
   - Package deals
   - Booking system
   - Opening hours
   - Seasonal promotions

6. **contact.html** - Contact Information
   - Map location
   - Phone/email
   - Social media links
   - FAQ section
   - Visitor inquiries

### Global Navigation:
- Sticky header with logo
- Main navigation links
- Language selector (English/Chinese)
- Booking button
- Mobile hamburger menu
