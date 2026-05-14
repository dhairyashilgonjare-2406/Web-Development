# Portfolio + Gift Store Combo Website

A modern, fully responsive website combining a personal portfolio and online gift store, built with pure HTML and CSS.

## 📁 Project Structure

```
Portfolio + Gift Store project/
├── index.html
├── style.css
├── README.md
└── images/
    ├── profile.jpg
    ├── project1.jpg
    ├── project2.jpg
    ├── project3.jpg
    ├── project4.jpg
    ├── gift1.jpg
    ├── gift2.jpg
    ├── gift3.jpg
    ├── gift4.jpg
    ├── gift5.jpg
    └── gift6.jpg
```

## 🚀 Quick Start

1. **Clone or Download** the project files
2. **Open `index.html`** in your web browser
3. **No server required** - it runs completely in the browser!

## 📸 Adding Images

The project uses placeholder image paths. To add your own images:

1. **Create an `images` folder** in the project directory
2. **Add images with these names:**
   - `profile.jpg` - Your profile photo (280x280px recommended)
   - `project1.jpg`, `project2.jpg`, `project3.jpg`, `project4.jpg` - Project screenshots
   - `gift1.jpg` through `gift6.jpg` - Product images (300x300px recommended)

3. **Or use placeholder services** like:
   ```
   https://via.placeholder.com/280x280?text=Profile
   https://via.placeholder.com/300x300?text=Gift+Box
   ```

## 🎨 Features

### Responsive Design
- ✅ Mobile-friendly (320px and up)
- ✅ Tablet optimized (768px)
- ✅ Desktop ready (1200px+)
- ✅ Smooth scrolling navigation
- ✅ Sticky navbar

### Portfolio Section
- Hero section with profile image
- About me with skills grid
- 4 showcase projects with hover effects
- Contact information

### Gift Store Section
- Eye-catching banner with special offers
- 4 gift categories
- Limited-time offer section
- 6 featured products with ratings & pricing
- Pickup service information
- Maharashtra pickup locations

### Design Elements
- Modern gradient backgrounds
- Smooth hover animations
- Professional color palette
- Flexbox & CSS Grid layouts
- Font Awesome icons
- Clean typography

## 🛠️ Customization Guide

### Update Personal Information

**In `index.html`:**
- Line 52: Replace "Your Name" with your actual name
- Line 53: Update subtitle
- Line 54: Personalize description
- Line 115: Update about section text
- Add your contact details in the Contact section (lines 435-447)

### Change Colors

**In `style.css` (Lines 29-36):**
```css
--primary-color: #6366f1;        /* Main blue */
--secondary-color: #ec4899;      /* Pink */
--accent-color: #f59e0b;         /* Orange */
```

### Update Gift Store Details

- Gift box price: Line 332
- Discount percentage: Line 320
- Offer validity date: Line 336
- Pickup locations: Line 464

### Add Social Media Links

**In `index.html` (Lines 481-495):**
Replace `#` with your actual social media URLs

## 📱 Responsive Breakpoints

| Device | Width | Breakpoint |
|--------|-------|-----------|
| Mobile | < 480px | Full stack layout |
| Small Mobile | < 320px | Extra small |
| Tablet | 768px | 2-column grid |
| Desktop | 1200px+ | Full layout |

## ✨ Key Features Explained

### Sticky Navigation
The navbar remains at the top while scrolling, with smooth transitions between sections.

### Smooth Scrolling
All navigation links use `scroll-behavior: smooth` for elegant page navigation.

### Hover Animations
- Cards lift up on hover with shadow effects
- Images zoom smoothly on hover
- Buttons have color transitions
- Social icons scale on hover

### Grid Layouts
- Flexbox for navigation and hero sections
- CSS Grid for projects, categories, and products
- Responsive `auto-fit` with `minmax()` for flexible grids

### Animation
- Floating gift box animation
- Pulsing pulse effect on offers
- Heartbeat animation on heart emoji
- Smooth fade transitions

## 🎯 For College Presentations

This project is perfect for:
- ✅ Web Development course submissions
- ✅ Portfolio showcasing
- ✅ PPT presentations
- ✅ Interview portfolio pieces
- ✅ Learning HTML & CSS

### Pro Tips for Presentation:
1. Use high-quality images for best visual impact
2. Update your real name and contact info
3. Add actual project descriptions
4. Test on multiple browsers (Chrome, Firefox, Safari, Edge)
5. Open on mobile to show responsive design
6. Use browser DevTools to show CSS Grid/Flexbox layouts

## 🌐 Browser Support

- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 📄 Code Quality

- **Well-commented CSS** - Easy to understand sections
- **Semantic HTML5** - Proper heading hierarchy and structure
- **Mobile-first approach** - Base styles then enhancements
- **Clean organization** - Logical file structure
- **No dependencies** - Pure HTML & CSS

## 🔧 If Images Don't Load

If images folder is not found, use placeholder services in `index.html`:

```html
<!-- Replace -->
<img src="images/profile.jpg" alt="Profile">

<!-- With -->
<img src="https://via.placeholder.com/280x280?text=Profile+Photo" alt="Profile">
```

## 📝 License

Free to use for educational and personal projects. Perfect for college submissions!

## 💡 Next Steps

To enhance this project further, you could add:
- JavaScript for form functionality
- Backend for actual product orders
- Database for dynamic content
- Authentication system
- Blog section
- Customer testimonials

---

**Created**: May 2026
**Designed for**: College Project Submission
**Best for**: Web Development Showcase

Enjoy your modern Portfolio + Gift Store website! 🎉
