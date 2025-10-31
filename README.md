# Core Assets Management Website

A professional, static website for Core Assets Management - institutional-grade portfolio management for private note investors.

## Files Included

- `index.html` - Main homepage with all sections
- `styles.css` - Complete styling with responsive design
- `script.js` - Mobile menu and form interaction JavaScript

## Features

- **Responsive Design** - Works on desktop, tablet, and mobile
- **Professional Color Scheme** - Navy (#0A2540) and Bright Blue (#0093DC)
- **Single Page Layout** - All sections on one page with smooth scrolling
- **Contact Form** - Ready for integration with form services

## Deploying to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository (e.g., `core-assets-website` or `yourusername.github.io`)
4. Make it **Public**
5. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**

1. In your new repository, click "uploading an existing file"
2. Drag and drop all three files:
   - index.html
   - styles.css
   - script.js
3. Scroll down and click "Commit changes"

**Option B: Using Git Command Line**

```bash
# Navigate to your website folder
cd /path/to/core-assets-website

# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit - Core Assets Management website"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/your-repo-name.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" (top menu)
3. Click "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait 1-2 minutes for deployment
7. Your site will be live at: `https://yourusername.github.io/repo-name/`

## Making the Contact Form Work

The contact form currently shows an alert. To make it functional, you have several options:

### Option 1: Formspree (Recommended - Free)

1. Go to [formspree.io](https://formspree.io)
2. Sign up for free account
3. Create a new form
4. Replace the form submission code in `script.js` with Formspree's code

### Option 2: Netlify Forms

If you deploy to Netlify instead of GitHub Pages, add `netlify` attribute to form.

### Option 3: Google Forms

1. Create a Google Form with matching fields
2. Use a service like [FormSubmit](https://formsubmit.co) to bridge your form to email

## Customization

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --navy: #0A2540;
    --bright-blue: #0093DC;
    /* Edit these values */
}
```

### Updating Content

All content is in `index.html`. Simply edit the text within the HTML tags.

### Adding Your Email

Replace `info@coreassetsmgmt.com` in the contact section with your actual email.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Need Help?

If you encounter issues deploying:

1. Make sure all files are in the root directory (not in subfolders)
2. File names must be exactly: `index.html`, `styles.css`, `script.js`
3. Wait 2-3 minutes after enabling GitHub Pages
4. Clear your browser cache if changes don't appear

## License

© 2025 Core Assets Management. All rights reserved.
