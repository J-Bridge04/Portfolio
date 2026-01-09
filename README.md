# Jacob Borbridge - Portfolio Website

A modern, responsive portfolio website to showcase your skills, projects, and experience to potential employers.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Engaging scroll animations and transitions
- **Modern UI**: Clean and professional design with gradient accents
- **Sections Include**:
  - Hero section with call-to-action buttons
  - About section with statistics
  - Skills showcase organized by category
  - Featured projects with descriptions
  - Contact form and social links
  - Responsive navigation menu

## Getting Started

1. **Customize Your Content**:
   - Open `index.html` and replace placeholder content with your information:
     - Update your name, title, and bio
     - Modify the skills to match your expertise
     - Add your actual projects with descriptions
     - Update contact information (email, phone, location)
     - Add your social media links (GitHub, LinkedIn, Twitter)

2. **Update Stats**:
   - Change the numbers in the "About" section to reflect your experience
   - Years of experience, projects completed, etc.

3. **Customize Colors** (Optional):
   - Open `styles.css`
   - Modify the CSS variables at the top to change the color scheme:
     ```css
     :root {
         --primary-color: #667eea;
         --secondary-color: #764ba2;
         --accent-color: #f093fb;
     }
     ```

4. **Add Project Images**:
   - Replace the placeholder project images with actual screenshots
   - You can replace the `.project-placeholder` div with an `<img>` tag

5. **Set Up Contact Form**:
   - The form currently shows an alert message
   - To make it functional, you'll need to:
     - Set up a backend service (e.g., Node.js, PHP)
     - Or use a service like Formspree, EmailJS, or Netlify Forms
     - Update the form submission code in `script.js`

## Viewing Your Website

Simply open `index.html` in your web browser to view your portfolio locally.

## Deploying Your Website

You can deploy this website for free using:

1. **GitHub Pages**:
   - Create a GitHub repository
   - Push your files
   - Enable GitHub Pages in repository settings

2. **Netlify**:
   - Drag and drop your folder to Netlify
   - Or connect your GitHub repository

3. **Vercel**:
   - Import your GitHub repository
   - Automatic deployments on every push

4. **Other Options**:
   - Render
   - Firebase Hosting
   - AWS S3 + CloudFront

## Customization Tips

- **Fonts**: Change fonts by linking Google Fonts in the HTML `<head>`
- **Icons**: The site uses Font Awesome icons (loaded via CDN)
- **Animations**: Modify animation speeds and effects in `styles.css`
- **Content**: Keep descriptions concise and impactful
- **Images**: Use high-quality images for your projects

## Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Next Steps

1. Replace all placeholder content with your real information
2. Add actual project screenshots or graphics
3. Test on different devices and browsers
4. Optimize images for web (compress them)
5. Set up a custom domain (optional)
6. Add Google Analytics to track visitors (optional)
7. Consider adding a blog section (optional)

## Need Help?

- HTML/CSS/JavaScript basics: [MDN Web Docs](https://developer.mozilla.org/)
- Free hosting: Search for "free static site hosting"
- Icons: [Font Awesome](https://fontawesome.com/)
- Images: [Unsplash](https://unsplash.com/) or [Pexels](https://pexels.com/)

Good luck with your job search! 🚀
