# Personal Portfolio Website - Assignment 1

A modern, responsive personal portfolio website built with HTML5, CSS3, and JavaScript. Features a sleek dark theme with creative design elements.

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file with all sections
├── styles.css          # Complete CSS styling and responsive design
├── script.js           # JavaScript for interactivity
├── README.md           # This file
└── screenshots/        # (Create folder for screenshots)
```

## ✨ Features

### HTML Elements Used
- ✅ Semantic headings (h1-h6)
- ✅ Paragraphs and text content
- ✅ Navigation hyperlinks
- ✅ Profile image/placeholder with SVG
- ✅ Unordered lists (skills, projects)
- ✅ Tables (skills matrix)
- ✅ Contact form with input fields
- ✅ Footer with copyright

### CSS Features Implemented
- ✅ **CSS Selectors**: Class, ID, element, pseudo-classes, pseudo-elements
- ✅ **Colors & Typography**: 
  - Custom CSS variables for theme colors
  - Modern font stack
  - Gradient text effects
  - Color contrast for accessibility
- ✅ **Box Model**: Padding, margins, borders, box-sizing
- ✅ **Flexbox Layout**:
  - Navigation menu
  - Hero section (text + image)
  - Button groups
  - Contact section (2-column layout)
- ✅ **Grid Layout**:
  - Skills table
  - Projects showcase (responsive grid)
  - Stats cards
- ✅ **Responsive Design**:
  - Mobile-first approach
  - Media queries for tablets (768px)
  - Media queries for mobile (480px)
  - Flexible font sizes and spacing
  - Touch-friendly buttons and links
- ✅ **Transitions & Hover Effects**:
  - Smooth color transitions
  - Scale and transform effects
  - Underline animations on nav links
  - Box shadow transitions
  - Floating animations for decorative elements
- ✅ **Advanced Styling**:
  - Gradient backgrounds and text
  - Backdrop filters (blur effect)
  - CSS animations (@keyframes)
  - Pulsing animation on hero image
  - Form styling with focus states

### JavaScript Interactivity
- ✅ Form validation and submission
- ✅ Alert notifications (success/error)
- ✅ Active navigation link highlighting
- ✅ Intersection Observer for scroll animations
- ✅ Smooth scroll behavior
- ✅ Dynamic element animations

## 🎨 Design Highlights

### Color Scheme (Dark Mode)
- **Primary**: `#00d4ff` (Cyan/Electric Blue)
- **Secondary**: `#ff006e` (Hot Pink)
- **Background**: `#0f0f1e` (Very Dark Blue)
- **Cards**: `#1a1a2e` (Dark Navy)
- **Text**: `#e0e0ff` (Light Lavender)

### Typography
- **Headings**: 'Segoe UI', sans-serif (600-700 weight)
- **Body**: 'Segoe UI', sans-serif (400 weight)
- **Line Height**: 1.6 (excellent readability)

### Responsive Breakpoints
- **Desktop**: 1200px max-width
- **Tablet**: 768px and below
- **Mobile**: 480px and below

## 🚀 Getting Started

### Option 1: Local Setup
1. Create a new folder for your project:
   ```bash
   mkdir portfolio
   cd portfolio
   ```

2. Download these files into the folder:
   - `index.html`
   - `styles.css`
   - `script.js`

3. Open `index.html` in your browser:
   ```bash
   # On Windows
   start index.html
   
   # On Mac
   open index.html
   
   # On Linux
   xdg-open index.html
   ```

### Option 2: Live Server (Recommended)
If you have VS Code installed:
1. Install the "Live Server" extension
2. Right-click `index.html` → "Open with Live Server"
3. Browser will open with hot-reload enabled

## 📋 Assignment Checklist

### Step 1: Project Setup ✅
- [x] Create project folder structure
- [x] Organize HTML, CSS, and JS files
- [x] Create README documentation

### Step 2: HTML Structure ✅
- [x] Semantic HTML5
- [x] Home section with hero content
- [x] About Me section with stats
- [x] Skills section with table and cards
- [x] Projects section with portfolio items
- [x] Contact section with form
- [x] Navigation menu
- [x] Footer

### Step 3: HTML Elements ✅
- [x] Headings (h1-h6)
- [x] Paragraphs
- [x] Hyperlinks (navigation, buttons, project links)
- [x] Image placeholder with SVG
- [x] Lists (unordered lists for skills/tech)
- [x] Table (skills matrix with rows/columns)
- [x] Form (contact form with inputs, textarea, button)

### Step 4: CSS Styling ✅
- [x] External stylesheet
- [x] CSS variables for theming
- [x] Selectors (class, ID, pseudo-classes)
- [x] Colors (gradients, solid colors)
- [x] Fonts (typography hierarchy)
- [x] Box model (padding, margin, borders)
- [x] Flexbox layouts
- [x] Grid layouts
- [x] Hover effects
- [x] Transitions and animations

### Step 5: Responsive Design ✅
- [x] Mobile-first approach
- [x] Media queries for tablets (768px)
- [x] Media queries for mobile (480px)
- [x] Flexible layouts
- [x] Touch-friendly elements
- [x] Responsive images/placeholders
- [x] Readable font sizes on all devices

### Step 6: Testing ✅
- [x] Desktop view (tested at 1200px+)
- [x] Tablet view (tested at 768px)
- [x] Mobile view (tested at 480px)
- [x] Cross-browser compatibility
- [x] Form submission
- [x] Navigation links
- [x] Hover effects
- [x] Animations

## 📸 Taking Screenshots

### For Desktop:
1. Open website in full browser window
2. Press F12 to open DevTools
3. Close DevTools (F12 again)
4. Press Win+Shift+S (Windows) or Cmd+Shift+4 (Mac) to take screenshot
5. Save as `screenshot-desktop.png`

### For Tablet:
1. Open DevTools (F12)
2. Click device toolbar (Ctrl+Shift+M)
3. Select iPad or Tablet view
4. Take screenshot
5. Save as `screenshot-tablet.png`

### For Mobile:
1. Keep DevTools open with mobile view
2. Select iPhone or mobile phone view
3. Take screenshot
4. Save as `screenshot-mobile.png`

## 🔧 Customization Guide

### Change Your Name
Open `index.html` and replace:
- Line 17: `<div class="nav-brand">Shubh</div>` → Your Name
- Line 24: `<h1 class="hero-title">Hi, I'm <span class="accent">Shubh</span></h1>`
- Line 118: `<title>Shubh - Creative Developer & Designer</title>`

### Update Skills
Modify the skills table in `index.html` (lines 244-280):
```html
<tr>
    <td class="category-cell">Your Category</td>
    <td>Your Technologies</td>
    <td><span class="proficiency advanced">Level</span></td>
</tr>
```

### Add Your Projects
Update the projects section (lines 307-375) with your actual projects.

### Change Colors
Edit CSS variables in `styles.css` lines 6-18:
```css
--primary: #00d4ff;      /* Main color */
--secondary: #ff006e;    /* Accent color */
--dark-bg: #0f0f1e;      /* Background */
```

## 🌐 Deployment

### Option 1: GitHub Pages (Free)
1. Create GitHub account
2. Create new repository: `username.github.io`
3. Upload your files (index.html, styles.css, script.js)
4. Visit `https://username.github.io`

### Option 2: Netlify (Free)
1. Go to netlify.com
2. Drag and drop your project folder
3. Get instant live link
4. Custom domain available

### Option 3: Google Drive (Quick Share)
1. Create folder in Google Drive
2. Upload all files
3. Share with "Anyone with the link can view"
4. Share the folder link

## 📝 Submission Requirements

### Files to Include
- [x] Complete HTML file (`index.html`)
- [x] CSS file (`styles.css`)
- [x] JavaScript file (`script.js`)
- [x] README file (`README.md`)
- [x] Screenshots:
  - Desktop view
  - Tablet view
  - Mobile view

### Submission Steps
1. Create a Google Drive folder: "Web_Design_Assignment_1"
2. Upload all files to the folder
3. Right-click folder → Share
4. Select "Anyone with the link can view"
5. Copy the sharing link
6. Submit the link before the deadline

## 🎓 Learning Outcomes

This project demonstrates:
- ✅ HTML5 semantic structure
- ✅ Professional CSS styling
- ✅ Responsive web design principles
- ✅ Flexbox and Grid layouts
- ✅ CSS animations and transitions
- ✅ JavaScript interactivity
- ✅ Form handling and validation
- ✅ Web accessibility considerations
- ✅ Mobile-first design approach
- ✅ Professional portfolio creation

## 🐛 Troubleshooting

### Styles not loading?
- Make sure `styles.css` is in the same folder as `index.html`
- Check file names are exactly matching (case-sensitive)
- Hard refresh browser: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)

### Form not working?
- Check browser console (F12) for errors
- Ensure `script.js` is in the same folder
- Try submitting with all fields filled

### Responsive design not working?
- Make sure viewport meta tag is in HTML head
- Test in browser's responsive mode (F12 → Toggle Device Toolbar)
- Check media queries in CSS

### Animations not showing?
- Check that CSS variables are correctly defined
- Ensure transitions are not disabled by browser extensions
- Test in a different browser

## 📚 Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Tricks - Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS Tricks - CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Web.dev - Responsive Design](https://web.dev/responsive-web-design-basics/)
- [JavaScript.info](https://javascript.info/)

## 📄 License

This project is open source and available for educational purposes.

## ✨ Notes

- The portfolio is fully customizable - feel free to modify colors, content, and layout
- All code is commented and follows best practices
- Responsive design works on all modern browsers
- No external libraries or frameworks required - pure HTML, CSS, and JavaScript

---

**Created for Web Design Assignment 1**  
**Last Updated**: September 2024
