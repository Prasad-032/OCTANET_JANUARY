# OCTANET_JANUARY
OCTANET WEB DEVELOPMENT INTERNSHIP TASKS

## Project Overview
This project is a modern, responsive image gallery website showcasing professional photography with an elegant dark theme and smooth animations.

---

## Files Documentation

### index.html
The HTML file serves as the structural foundation of the gallery website. Key components include:

**Structure:**
- **Navbar**: A fixed navigation bar with the "Lens" branding and menu items (Home, Gallery, About, Explore)
- **Hero Section**: A full-viewport hero area with a featured image collection, social media icons, and descriptive text elements
- **Bottom Grid Layout**: A three-section grid (b1, b2, b3) displaying different gallery collections with interactive cards

**Key Features:**
- Uses semantic HTML5 markup for better accessibility
- Integrates RemixIcon library (CDN) for social media and interface icons
- Responsive meta viewport configuration for mobile compatibility
- Navigation items: Home, Gallery, About, and Explore CTA button
- Three main content sections showcasing "Popular", "Latest", and "More" gallery items
- Footer quick links section with Privacy Policies, Terms and Conditions, Contact Us, and About Us

**External Dependencies:**
- RemixIcon library (v4.2.0) for icon display

---

### style.css
The CSS file handles all visual styling, layout, and animations. It implements a modern dark-themed design with glassmorphism effects.

**Design System:**
- **Color Scheme**: Dark background (#0a0a0a) with white text and semi-transparent overlays
- **Font Family**: Trebuchet MS with fallbacks to Lucida Sans and Arial
- **Dimensions**: 100% width and height with responsive viewport settings

**Key Styling Sections:**

1. **Navbar Styling**
   - Fixed positioning with blur backdrop effect
   - Semi-transparent background with subtle border
   - Navigation links with hover color transitions
   - Explore button with white background and rounded style

2. **Hero Section (.top)**
   - Full viewport height with background image from Unsplash
   - Linear gradient overlay for text readability
   - Flexible layout for content distribution
   - Image hover effect with 1.03x scale transform

3. **Bottom Grid Layout**
   - Three responsive sections (b1: 30%, b2: 30%, b3: 40%)
   - **b1**: Popular section with overlay gradient and card styling
   - **b2**: Two-part section (up/down) with Latest gallery and More content
   - **b3**: Quick links footer section with gradient overlay
   - All sections include hover effects with z-index elevation

4. **Interactive Elements**
   - Card buttons with hover opacity transitions
   - Light variant buttons with glassmorphic styling
   - Tag badges with backdrop blur effect
   - Social icons with circular borders and hover fill effect
   - Footer links with animated arrow indicators

5. **Responsive Design**
   - **Tablet (max-width: 900px)**: Grid converts to column layout, adjusted dimensions
   - **Mobile (max-width: 600px)**: Simplified navigation, stacked layouts, reduced font sizes

**Visual Effects:**
- Backdrop blur filters for glassmorphic design
- Smooth transitions (0.2s - 0.4s) on hover states
- Scale transforms on image and card interactions
- Linear gradients for depth and overlay effects

---

## How to Use
1. Open `index.html` in a web browser
2. The page loads with a responsive gallery layout
3. Hover over images and cards to see interactive effects
4. Navigation menu provides access to different sections
5. All responsive breakpoints adapt automatically on smaller screens