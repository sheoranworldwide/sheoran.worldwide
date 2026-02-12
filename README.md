# Sheoran Worldwide Website

A modern, professional landing page for Sheoran Worldwide.

## Features

- Clean, modern design
- Fully responsive (mobile-friendly)
- Smooth scrolling navigation
- Contact form
- Animated elements
- Professional gradient hero section

## Files Included

- `index.html` - Main HTML file
- `styles.css` - All styling
- `script.js` - Interactive features
- `README.md` - This file

## How to Deploy to GitHub Pages (FREE)

### Step 1: Create a GitHub Account
1. Go to https://github.com
2. Click "Sign up"
3. Create your free account

### Step 2: Create a New Repository
1. Click the "+" icon in top right corner
2. Select "New repository"
3. Name it: `sheoran-worldwide` (or any name you want)
4. Make it **Public**
5. Click "Create repository"

### Step 3: Upload Your Files
1. On your new repository page, click "uploading an existing file"
2. Drag and drop all 4 files (index.html, styles.css, script.js, README.md)
3. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to repository "Settings"
2. Scroll down to "Pages" in left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 1-2 minutes

### Step 5: Access Your Site
Your site will be live at:
```
https://YOUR-USERNAME.github.io/sheoran-worldwide/
```

## Custom Domain (Optional)

If you want to use `sheoran.worldwide` as your domain:

1. Buy the domain from Namecheap or similar (~$12/year)
2. In your repository settings under "Pages", add custom domain: `sheoran.worldwide`
3. In your domain registrar, add these DNS records:
   - Type: A, Name: @, Value: 185.199.108.153
   - Type: A, Name: @, Value: 185.199.109.153
   - Type: A, Name: @, Value: 185.199.110.153
   - Type: A, Name: @, Value: 185.199.111.153
   - Type: CNAME, Name: www, Value: YOUR-USERNAME.github.io

## Customization

### Change Colors
Edit `styles.css` and look for these color codes:
- Primary gradient: `#667eea` and `#764ba2`
- Text: `#333` and `#6b7280`
- Background: `#f8f9fa`

### Change Content
Edit `index.html` and update:
- Page title (line 6)
- Heading text (line 23)
- Tagline (line 24)
- About section (lines 35-57)
- Feature descriptions (lines 41-55)

### Add Your Logo
Replace the text logo (line 15) with an image:
```html
<img src="logo.png" alt="Sheoran Worldwide" class="logo">
```

## Contact Form Setup

The contact form currently shows an alert. To make it actually send emails:

**Option 1: Use Formspree (Free)**
1. Go to https://formspree.io
2. Create free account
3. Get your form endpoint
4. Update the form tag in index.html:
```html
<form action="https://formspree.io/f/YOUR-FORM-ID" method="POST" class="contact-form">
```

**Option 2: Use EmailJS**
1. Go to https://www.emailjs.com
2. Follow their setup guide
3. Update script.js with their code

## Support

Need help? Common issues:

**Site not showing up?**
- Wait 2-3 minutes after enabling GitHub Pages
- Make sure index.html is in the root folder
- Check repository is Public

**Custom domain not working?**
- DNS changes take 24-48 hours
- Double-check DNS records
- Make sure you added domain in GitHub Pages settings

## License

Free to use and modify for your needs.

---

Built with ❤️ for Sheoran Worldwide
