# Muddu Tech Construction Website

## Overview
Muddu Tech Construction is a professional construction company website based in Uganda. The website showcases the company's services, projects, values, and provides contact information for potential clients.

## Files Structure
- `index.html` - Main homepage
- `projects.html` - Detailed projects portfolio page
- `images/` - Directory containing all website images
  - `logo.png` - Company logo
  - `favicon.ico` - Website favicon
  - `hero-bg.jpg` - Hero section background
  - `about-team.jpg` - About section image
  - `muddu0.jpg`, `muddu2.jpg`, `muddu6.jpg` - Project images
  - `client1.jpg`, `client2.jpg` - Testimonial client photos
  - `project1.jpg`, `project2.jpg`, `project3.jpg` - Project modal images

## Color Scheme
- **Primary Color**: `#f97316` (Orange)
- **Primary Dark**: `#ea580c` (Darker Orange)
- **Primary Light**: `#fdba74` (Light Orange)
- **Secondary Color**: `#1e293b` (Dark Blue-Gray)
- **Accent Color**: `#f59e0b` (Amber)
- **Light Color**: `#f8fafc` (Off-white)
- **Dark Color**: `#0f172a` (Navy)
- **Text Color**: `#334155` (Gray)
- **Text Light**: `#64748b` (Light Gray)

## Features

### Homepage (index.html)
1. **Responsive Navigation Bar**
   - Fixed header with scroll effect
   - Mobile-friendly hamburger menu
   - Smooth scrolling to sections

2. **Hero Section**
   - Full-screen background with overlay
   - Call-to-action buttons
   - Animated scroll indicator

3. **About Section**
   - Company history and description
   - Key features list with icons
   - Team image

4. **Stats Counter**
   - Years of experience
   - Projects completed
   - Team members
   - Client satisfaction rate

5. **Services Section** (6 services)
   - Residential Construction
   - Commercial Construction
   - Industrial Construction
   - Renovation & Remodeling
   - Civil Engineering Works
   - Architectural Design
   - *Grid layout: 3 columns on desktop, 2 on tablet, 1 on mobile*

6. **Projects Showcase**
   - Filterable project gallery (All/Residential/Commercial/Industrial)
   - 3 featured projects with overlay effects
   - "View All Projects" button linking to projects.html

7. **Values Section** (6 values)
   - Safety First
   - Quality Excellence
   - Integrity
   - Collaboration
   - Sustainability
   - Innovation
   - *Grid layout: 3 columns on desktop, 2 on tablet, 1 on mobile*

8. **Testimonials**
   - Auto-rotating client testimonials
   - Client photos and details

9. **Contact Section**
   - Contact information with icons
   - Contact form with service selection
   - Form validation and submission alert

10. **Footer**
    - Company info and social links
    - Quick links
    - Services list
    - Newsletter signup

### Projects Page (projects.html)
1. **Page Header**
   - Large background image
   - Page title and description

2. **Breadcrumb Navigation**
   - Home > Projects

3. **Project Portfolio**
   - Filter buttons (All/Residential/Commercial/Industrial/Infrastructure)
   - 6 detailed project cards
   - Each card shows:
     - Project image
     - Category tag
     - Title
     - Description
     - Completion date
     - "View Details" button

4. **Project Details Modal**
   - Large project image
   - Category tag
   - Project title and description
   - Project details grid (Type, Location, Date, Client)
   - Project highlights
   - Scope of work
   - Close button and click-outside-to-close functionality
   - Escape key support

5. **Back to Top Button**
   - Appears after scrolling down
   - Smooth scroll to top

## JavaScript Functionality

### Common Features (Both Pages)
- Mobile menu toggle
- Header scroll effect
- Smooth scrolling for anchor links
- Animation on scroll

### Homepage Specific
- Project filtering
- Testimonial slider with auto-rotation
- Form submission with alert
- Active navigation highlighting

### Projects Page Specific
- Project filtering by category
- Modal popup with detailed project information
- Back to top button visibility toggle
- Newsletter form submission
- Escape key modal closing
- Body scroll lock when modal is open

## Responsive Breakpoints
- **Desktop**: 1200px+ - 3-4 columns
- **Tablet**: 768px - 992px - 2 columns
- **Mobile**: Below 768px - 1 column

## Browser Compatibility
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Setup Instructions
1. Download all files maintaining the directory structure
2. Place all images in the `images/` folder
3. Open `index.html` in a web browser
4. For production, replace placeholder images with actual company photos
5. Update contact information and social media links
6. Configure the contact form to send emails to your server

## Customization
- **Colors**: Modify the CSS variables in the `:root` section
- **Content**: Update text in the HTML sections
- **Projects**: Add/remove project cards in both index.html and projects.html
- **Images**: Replace image paths with your own images
- **Contact Info**: Update phone numbers, email, and address in the contact section

## Dependencies
- Font Awesome 6.0.0-beta3 (icons)
- Google Fonts - Inter font family
- No external JavaScript libraries (pure vanilla JS)

## Notes
- The contact form currently shows an alert on submission - implement backend integration for actual email sending
- Newsletter form also shows an alert - needs backend integration
- All image paths should be verified and updated to match your actual file names
- The modal in index.html uses placeholder project details - update with real project information
