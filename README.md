# Portfolio Website - Jorge Luis Sandoval Urenda

A modern, responsive professional portfolio website featuring a technological aesthetic with electric blue and electric purple color palette, smooth animations, and multi-language support (Spanish, English, French).

## Features

- ✨ **Modern Design**: Electric blue and electric purple gradient theme with smooth animations
- 🌍 **Multi-language Support**: Spanish, English, and French with intuitive flag-based language switcher
- 📱 **Fully Responsive**: Adapts perfectly to all screen sizes (mobile, tablet, desktop)
- ⚡ **Performance Optimized**: Lightweight and fast loading
- ♿ **Accessible**: Follows web accessibility best practices
- 🎨 **Animated Background**: Subtle animated background that enhances without distracting
- 📄 **Sections Included**:
  - Landing page with professional information
  - About Me section
  - Technical Skills (categorized)
  - Projects showcase (with preview images and demo links)
  - Certifications and Achievements
  - Contact section
  - Downloadable CV

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styles with Tailwind CSS framework
- **JavaScript**: Vanilla JS for interactivity and language switching
- **Tailwind CSS**: Via CDN for rapid development
- **Font Awesome**: Icons library

## Project Structure

```
Protafolio/
├── index.html          # Main HTML file
├── styles.css          # Custom CSS styles
├── script.js           # JavaScript functionality
├── assets/             # Images and documents
│   ├── profile-photo.jpg
│   ├── project1.jpg
│   ├── project2.jpg
│   └── cv.pdf
├── .gitignore
└── README.md
```

## Setup Instructions

1. **Clone or download this repository**

2. **Add your assets**:
   - Place your professional photo as `assets/profile-photo.jpg` (500x500px recommended)
   - Add project preview images as `assets/project1.jpg` and `assets/project2.jpg` (800x450px recommended)
   - Add your CV as `assets/cv.pdf`

3. **Customize content**:
   - Edit `index.html` to update project descriptions, links, and personal information
   - Modify `script.js` translations if you need to change any text
   - Update social media links (GitHub, LinkedIn) in the HTML

4. **Test locally**:
   - Open `index.html` in a web browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```

## Deployment

### Netlify Deployment

1. Create a new account at [Netlify](https://www.netlify.com/)
2. Drag and drop the project folder to Netlify dashboard, OR
3. Connect your GitHub repository:
   - Click "New site from Git"
   - Choose your repository
   - Build settings:
     - Build command: (leave empty)
     - Publish directory: `/` (root)
   - Click "Deploy site"

### GitHub Pages Deployment

1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Under "Source", select your branch (usually `main` or `master`)
4. Select `/` (root) as the folder
5. Click "Save"
6. Your site will be available at: `https://yourusername.github.io/repository-name`

## Customization

### Changing Colors

Edit the Tailwind config in `index.html`:
```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                'electric-blue': '#00B4D8',  // Change this
                'electric-purple': '#7B2CBF', // Change this
                // ...
            }
        }
    }
}
```

### Adding New Projects

1. Add a new project card in the projects section of `index.html`
2. Add the project image to `assets/` folder
3. Update translations in `script.js` for all three languages
4. Add `data-i18n` attributes to translatable text

### Modifying Animations

Edit `styles.css` to adjust:
- Animation speeds (change `animation-duration` values)
- Hover effects
- Background animations

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

- Optimize images before adding them (use tools like TinyPNG or ImageOptim)
- Keep CV file size reasonable (< 2MB recommended)
- Consider using a CDN for assets if needed

## License

This project is open source and available for personal use.

## Contact

Jorge Luis Sandoval Urenda
Email: jorgluisu@hotmail.com

---

Built with ❤️ using modern web technologies
