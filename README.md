```
# Portfolio-Model
Portfolio for modeling

A clean, modern portfolio website inspired by other model websites. Built with HTML, CSS, and JavaScript featuring smooth animations, responsive design, and professional styling.

File Structure

portfolio
 index.html          # Main HTML file
 styles.css          # CSS styles
 script.js           # JavaScript functionality
 README.md          # This file
```
```


 Styling Customization

Colors
The main color scheme uses:
- Primary: `#333` (dark gray)
- Secondary: `#666` (medium gray)
- Background: `#f8f9fa` (light gray)
- White: `#fff`

```

Font
The website uses the Montserrt font family. To change fonts:

1. Update the Google Fonts link in the HTML head
2. Change the `font-family` property in the CSS


To add images:
1. Create an `images/` folder
2. Add your images to the folder
3. Update the HTML to reference your images:

```html
<img src="images/your-image.jpg" alt="Description">
```

3. Vercel (Free)
 Made on [Vercel](https://vercel.com)


 Browser Support

- Chrome 
- Safari
- Internet Explorer



 SEO Optimization

The website includes basic SEO optimization:

- Semantic HTML structure
- Meta tags for title and description
- Proper heading hierarchy
- Alt text for images
- Clean URL structure


Adding a Gradient Background
```css
.hero {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

Adding More Animations
```css
.project-card {
    animation: slideInUp 0.6s ease;
}

@keyframes slideInUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}
```

Credits
- Fonts: [Inter](https://fonts.google.com/specimen/Inter) by Google Fonts
- Icons: [Font Awesome](https://fontawesome.com/)
