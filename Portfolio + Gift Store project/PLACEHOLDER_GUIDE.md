# Image Placeholder Guide

## Quick Start with Placeholder Images

If you want to see the website immediately without adding real images, you can use placeholder services. Here's how to modify your `index.html`:

## Option 1: Using Placeholder.com (Recommended)

Replace image `src` attributes with these URLs:

### Profile Image (Line 220)
```html
<!-- Replace this line: -->
<img src="images/profile.jpg" alt="Profile Image">

<!-- With this: -->
<img src="https://via.placeholder.com/280x280/667eea/ffffff?text=Your+Profile" alt="Profile Image">
```

### Project Images (Lines 262, 278, 294, 310)
```html
<!-- Project placeholders: -->
<img src="https://via.placeholder.com/400x300/667eea/ffffff?text=E-Commerce+Project" alt="Project 1">
<img src="https://via.placeholder.com/400x300/764ba2/ffffff?text=Portfolio+Website" alt="Project 2">
<img src="https://via.placeholder.com/400x300/667eea/ffffff?text=Business+Website" alt="Project 3">
<img src="https://via.placeholder.com/400x300/764ba2/ffffff?text=Landing+Page" alt="Project 4">
```

### Gift Product Images (Lines 370, 390, 410, 430, 450, 470)
```html
<!-- Gift product placeholders: -->
<img src="https://via.placeholder.com/300x300/ec4899/ffffff?text=Luxury+Gift+Box" alt="Gift 1">
<img src="https://via.placeholder.com/300x300/f59e0b/ffffff?text=Romance+Box" alt="Gift 2">
<img src="https://via.placeholder.com/300x300/ec4899/ffffff?text=Party+Package" alt="Gift 3">
<img src="https://via.placeholder.com/300x300/f59e0b/ffffff?text=Corporate+Box" alt="Gift 4">
<img src="https://via.placeholder.com/300x300/ec4899/ffffff?text=Kids+Delight" alt="Gift 5">
<img src="https://via.placeholder.com/300x300/f59e0b/ffffff?text=Wellness+Box" alt="Gift 6">
```

## Placeholder URL Format

```
https://via.placeholder.com/WIDTHxHEIGHT/BACKGROUND_COLOR/TEXT_COLOR?text=TEXT
```

### Parameters:
- **WIDTH x HEIGHT**: Image dimensions (e.g., 300x300)
- **BACKGROUND_COLOR**: Hex color without # (e.g., ec4899, 667eea)
- **TEXT_COLOR**: Text color (ffffff = white)
- **text**: What to display on image (use + for spaces)

## Recommended Dimensions

| Image Type | Size | Placeholder URL |
|-----------|------|-----------------|
| Profile | 280x280 | `https://via.placeholder.com/280x280/667eea/ffffff?text=Profile` |
| Projects | 400x300 | `https://via.placeholder.com/400x300/667eea/ffffff?text=Project` |
| Products | 300x300 | `https://via.placeholder.com/300x300/ec4899/ffffff?text=Gift` |

## Adding Real Images Later

1. **Create `images` folder** in project directory
2. **Add your image files:**
   - profile.jpg
   - project1.jpg, project2.jpg, project3.jpg, project4.jpg
   - gift1.jpg, gift2.jpg, gift3.jpg, gift4.jpg, gift5.jpg, gift6.jpg
3. **Replace placeholder URLs** with local file paths:
   ```html
   <img src="images/profile.jpg" alt="Profile Image">
   ```

## Alternative Placeholder Services

If placeholder.com is unavailable, try these alternatives:

### Picsum.photos (Random Photos)
```html
<img src="https://picsum.photos/280/280?random=1" alt="Profile">
```

### Loremflickr.com (Themed Images)
```html
<img src="https://loremflickr.com/280/280/gift" alt="Gift Box">
<img src="https://loremflickr.com/400/300/portfolio" alt="Project">
```

### DummyImage.com (Simple Colored Blocks)
```html
<img src="https://dummyimage.com/280x280/667eea/ffffff&text=Profile" alt="Profile">
```

## Recommended Image Sources for Real Images

When you're ready to add real images:

### Free Stock Photos:
- **Unsplash** - https://unsplash.com (High quality)
- **Pexels** - https://pexels.com (Royalty-free)
- **Pixabay** - https://pixabay.com (Free stock images)
- **Freepik** - https://freepik.com (Vectors & photos)

### For Product Images:
- **Amazon** - Product images for reference
- **Etsy** - Gift box inspirations
- **Create your own** - Take photos of real gift boxes
- **Canva** - Design product mock-ups

## Image Optimization Tips

1. **Compress images** - Use TinyPNG or ImageOptim
2. **Correct size** - Resize before uploading (not in CSS)
3. **Format** - Use .jpg for photos, .png for graphics
4. **Naming** - Use lowercase, no spaces (profile.jpg, gift_box.jpg)
5. **Folder structure** - Keep organized in `/images` folder

## Testing with Placeholders

The website looks great with placeholder images! You can:
1. ✅ Test all responsive layouts
2. ✅ Check hover effects
3. ✅ Verify color schemes
4. ✅ Practice presenting
5. ✅ Share demo with others

Then replace with real images for final submission.

---

**Pro Tip**: Use high-quality images that match your color scheme for best visual impact in presentations!
