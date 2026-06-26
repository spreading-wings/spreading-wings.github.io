# Logo Setup Instructions

## Quick Setup

The website is configured to display `logo.png` in the navigation bar and footer. Follow these steps to add your company logo:

## ✅ Step 1: Prepare Your Logo

### If You Already Have a Logo:
1. Ensure it's in PNG format
2. Recommended size: 200x200px to 500x500px
3. Use transparent background for best results
4. Name it exactly: `logo.png`
5. Place it in the root directory (same folder as index.html)

### If You Need to Create a Logo:

#### Using the Included SVG Template:
1. Open `logo.svg` in your browser or image editor
2. Modify colors, text, or design as needed
3. Convert to PNG using one of these methods:

**Online Converters:**
- https://cloudconvert.com/svg-to-png
- https://convertio.co/svg-png/
- https://svgtopng.com/

**Design Software:**
- Figma: Import SVG → Export as PNG
- Adobe Illustrator: File → Export → Export As → PNG
- Inkscape: File → Export PNG Image
- GIMP: Open SVG → Export As → PNG

#### Creating from Scratch:

**Free Online Tools:**
- **Canva** (https://canva.com)
  - Search "Logo" templates
  - Customize with your brand colors
  - Download as PNG

- **Figma** (https://figma.com)
  - Create new design (200x200px)
  - Design your logo
  - Export as PNG

- **Looka** (https://looka.com)
  - AI-powered logo generator
  - Input company name and industry
  - Download PNG

**Professional Options:**
- Hire a designer on Fiverr, Upwork, or 99designs
- Use Adobe Illustrator or Photoshop
- Commission a custom design

## ✅ Step 2: Sizing Guidelines

### Navigation Logo (Top Bar):
- Height: 50px (auto-width)
- Displayed on white background
- Should have good contrast

### Footer Logo:
- Height: 60px (auto-width)
- Displayed on dark navy background
- Automatically filtered to white for visibility

### Recommended Original Sizes:
- **Minimum**: 200x200px
- **Recommended**: 400x400px or 500x500px
- **Maximum**: 1000x1000px (will be scaled down)

## ✅ Step 3: File Format Details

**Best Format: PNG**
- Transparent background (alpha channel)
- High quality, no compression artifacts
- File size: Under 200KB recommended

**Alternative: SVG**
If you prefer SVG:
1. Rename your file to `logo.svg`
2. Update `index.html` - change:
   - `<img src="logo.png"` to `<img src="logo.svg"`
3. SVG benefits: Perfect scaling, smaller file size

## ✅ Step 4: Testing Your Logo

After adding `logo.png`:
1. Open `index.html` in your browser
2. Check the navigation bar (top) - logo should appear next to "Spreading Wings"
3. Scroll to footer (bottom) - logo should appear in white
4. Test on mobile view (resize browser window)

### If Logo Doesn't Appear:
- Check filename is exactly `logo.png` (case-sensitive)
- Verify file is in root directory (same level as index.html)
- Clear browser cache (Ctrl+F5 or Cmd+Shift+R)
- Check browser console for errors (F12)

## 🎨 Brand Colors Used in Website

Use these colors when creating your logo for consistency:

- **Primary Navy**: #1a365d
- **Secondary Blue**: #2d7dd2
- **Accent Gold**: #f59e0b
- **Dark Text**: #1f2937
- **Light Gray**: #6b7280

## 📐 Logo Design Tips

1. **Keep it Simple**: Clean, minimal designs work best at small sizes
2. **Use Vectors**: SVG or high-res PNG ensures crisp display
3. **Test Contrast**: Make sure logo is visible on both white and dark backgrounds
4. **Mobile-Friendly**: Should be recognizable even at 30-40px height
5. **Brand Consistency**: Match website colors and style

## 🔧 Advanced Customization

### Change Logo Size:
Edit `css/styles.css` or `styles.css`:

```css
/* Navigation logo */
.logo-img {
    height: 50px;  /* Change this value */
    width: auto;
}

/* Footer logo */
.footer-logo {
    height: 60px;  /* Change this value */
}
```

### Remove Text Next to Logo:
In `index.html`, find and remove:
```html
<span class="logo-text">Spreading Wings</span>
```

### Use Logo Only in Nav (No Text):
Already configured - just add logo.png and it will display alongside text

## 📞 Need Help?

Common issues and solutions:

**Logo appears pixelated:**
- Use higher resolution PNG (at least 400x400px)
- Try SVG format instead

**Logo too large/small:**
- Edit the height values in CSS (see Advanced Customization)

**Logo not showing:**
- Check file name is exactly `logo.png`
- Verify it's in the correct directory
- Check browser console for 404 errors

---

**Ready to Launch?**

Once you've added your logo:
1. Review all sections of the website
2. Update contact information
3. Add real images for case studies
4. Test on mobile devices
5. Deploy to your web host

Your premium market research website for Spreading Wings is ready to take flight! 🦅
