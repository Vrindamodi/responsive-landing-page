# Responsive Landing Page - TechFlow

A modern, fully responsive landing page built with HTML5 and CSS3, featuring a clean design, smooth animations, and mobile-first approach.

## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Responsive Design](#responsive-design)
- [Code Highlights](#code-highlights)
- [Browser Support](#browser-support)
- [Author](#author)

## Demo
[[Live Demo](https://github.com/Vrindamodi/responsive-landing-page/blob/main/index.html)(http://127.0.0.1:5500/index.html#)

## Features

### Header & Navigation
- **Fixed navigation bar** that stays at the top while scrolling
- **Gradient background** (purple to violet) for modern look
- **Responsive hamburger menu** for mobile devices
- **Smooth navigation links** with hover effects
- **Logo branding** with custom typography

### Hero Section
- **Full viewport height** for impactful first impression
- **Centered content layout** using Flexbox
- **Call-to-action button** with hover animations
- **Gradient background** matching the header
- **Compelling headline and description**

### Footer
- **Social media links** (Facebook, Twitter, LinkedIn, Instagram)
- **Copyright information**
- **Flexible layout** that adapts to screen sizes
- **Hover effects** on social links

### Responsive Features
- **Mobile-first design** approach
- **Three breakpoints**: Desktop (>768px), Tablet (≤768px), Mobile (≤480px)
- **Collapsible navigation menu** on smaller screens
- **Fluid typography** that scales with screen size
- **Flexible layouts** using CSS Flexbox

## Technologies Used

- **HTML5**: Semantic markup, accessibility features
- **CSS3**: Modern styling, animations, transitions
- **Flexbox**: Responsive layout system
- **Media Queries**: Breakpoints for different devices
- **JavaScript**: Hamburger menu toggle functionality
- **Git**: Version control
- **GitHub Pages**: Hosting

## Project Structure

```
responsive-landing-page/
│
├── index.html          # Main HTML file
├── style.css           # CSS stylesheet
└── README.md           # Project documentation
```

## Installation

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- VS Code or any text editor
- Live Server extension (for VS Code)

### Steps

1. **Clone the repository**

   git clone https://github.com/Vrindamodi/responsive-landing-page.git
  

2. **Navigate to project directory**

   cd responsive-landing-page
   

3. **Open in VS Code**
  

4. **Run with Live Server**
   - Right-click on `index.html`
   - Select "Open with Live Server"
   - Page will open in your default browser

## Usage

### Viewing the Landing Page
Simply open `index.html` in any modern web browser.

### Testing Responsiveness
1. Open Developer Tools (F12 in Chrome)
2. Click the device toggle icon (Ctrl+Shift+M)
3. Select different device sizes
4. Or manually resize the browser window

### Customization

#### Change Colors
Edit the gradient colors in `style.css`:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

#### Update Content
Modify text in `index.html`:
- Hero headline: `<h1>Your Title Here</h1>`
- Description: `<p>Your description here</p>`
- Button text: `<button class="cta-button">Your CTA</button>`

#### Add Logo Image
Replace the text logo with an image:
```html
<div class="logo">
    <img src="your-logo.png" alt="Company Logo">
</div>
```

## Responsive Design

### Breakpoints

| Device | Screen Width | Changes Applied |
|--------|-------------|-----------------|
| **Desktop** | > 768px | Full navigation bar, large text |
| **Tablet** | ≤ 768px | Hamburger menu, adjusted padding |
| **Mobile** | ≤ 480px | Smaller fonts, stacked layout |

### Mobile Navigation
- Hamburger icon appears on screens ≤768px
- Click/tap to toggle navigation menu
- Menu slides in from the left
- Click any link to navigate (menu stays open until toggled)

## Code Highlights

### CSS Flexbox Layout
```css
.hero {
    display: flex;
    align-items: center;
    justify-content: center;
}
```

### Smooth Transitions
```css
.cta-button:hover {
    transform: translateY(-3px);
    transition: all 0.3s ease;
}
```

### Media Query Example
```css
@media (max-width: 768px) {
    .hamburger {
        display: flex;
    }
    .nav-links {
        flex-direction: column;
    }
}
```

### JavaScript Toggle
```javascript
hamburger.addEventListener('click', () => {
    navLinks.classList.toggle('active');
});
```

## Browser Support

 Chrome (latest)  
 Firefox (latest)  
 Safari (latest)  
 Edge (latest)  
 Opera (latest)

##  Learning Outcomes

1. **HTML5 Structure**: Semantic elements, proper document structure
2. **CSS3 Styling**: Gradients, shadows, transitions, transforms
3. **Responsive Design**: Media queries, mobile-first approach
4. **Flexbox Layout**: Alignment, justification, flexible containers
5. **JavaScript DOM**: Event listeners, classList manipulation
6. **Git & GitHub**: Version control, repository management, GitHub Pages
7. **Web Development Workflow**: VS Code, Live Server, browser dev tools

## Key Concepts Demonstrated

### 1. HTML Structure
- Semantic tags (`<header>`, `<nav>`, `<section>`, `<footer>`)
- Proper heading hierarchy
- Accessibility attributes
- Clean, organized code

### 2. CSS Layout
- Flexbox for responsive alignment
- Fixed positioning for navbar
- Box model understanding
- CSS custom properties potential

### 3. Responsive Design
- Mobile-first approach
- Fluid typography
- Flexible images
- Breakpoint strategy

### 4. User Experience
- Smooth hover effects
- Clear call-to-action
- Intuitive navigation
- Fast load times

## Author

**Vrinda Modi**
- GitHub:(https://github.com/Vrindamodi)
- Email: Vrindamodi21@gmail.com


## Acknowledgments

- Design inspiration from modern landing page trends
- Color palette from UI gradient collections
- Font choices from web-safe font stacks
