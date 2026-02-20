# Immaculata High School Website

A modern, responsive website for Immaculata High School in Somerville, NJ with an easy-to-use content management system.

## 🌟 Features

- **Modern Design**: Clean, professional layout with school colors (Spartan Blue & Gold)
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Easy Content Management**: Simple admin interface for non-technical users
- **No Technical Skills Required**: Edit content through user-friendly forms
- **Fast Loading**: Optimized for speed and performance
- **SEO Friendly**: Proper meta tags and semantic HTML
- **Accessible**: WCAG compliant with proper ARIA labels and contrast ratios

## 📁 Files Overview

```
immaculata-site/
├── index.html           # Main website file
├── admin.html          # Content management interface
├── site-content.json   # All editable content stored here
└── README.md          # This file
```

## 🚀 Quick Start

### For Website Administrators

1. **Access the Admin Panel**: Open `admin.html` in your web browser
2. **Login**: Enter password: `spartan2026`
3. **Edit Content**: Use the tabs to modify different sections
4. **Preview Changes**: Click "Preview Website" to see how it looks
5. **Save & Update**: Click "Download Updated Content" to get the new JSON file
6. **Upload**: Replace the old `site-content.json` on your web server

### For Web Developers

1. **Deploy Files**: Upload all files to your web server
2. **Test**: Visit your domain to see the website
3. **SSL Certificate**: Ensure HTTPS is configured
4. **Backup**: Keep regular backups of `site-content.json`

## 📋 Admin Panel Guide

### Login Information
- **URL**: `yourdomain.com/admin.html`
- **Password**: `spartan2026`
- **Change Password**: Edit the `correctPassword` variable in admin.html

### Available Sections

#### 🏛️ School Info
- School name, motto, address, phone, email
- Founded year and founder information
- Office hours

#### 🦸 Hero Section
- Main headline and subheadline
- Background image URL
- Call-to-action buttons

#### 📰 News & Highlights
- Add/remove news articles
- Edit titles, dates, summaries
- Update image URLs and links

#### 🎓 Academics
- Section description and vice president info
- Academic programs (AP, Honors, College Prep, etc.)

#### 🎒 Admissions
- Admissions information and director contact
- Student testimonials
- Application process details

#### ⚽ Athletics
- Sports programs and achievements
- Athletics director information
- Seasonal sport categories

#### 📅 Events
- Upcoming events calendar
- Event titles, dates, times, descriptions

#### 📊 Quick Stats
- Number of AP courses, sports, clubs
- College acceptance rate
- Social media links

## 🔧 Deployment Options

### GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select "Deploy from a branch" → main branch
5. Your site will be available at `username.github.io/repository-name`

### Netlify (Free)
1. Drag and drop the folder to netlify.com/drop
2. Get instant deployment with custom domain support
3. Connect to GitHub for automatic updates

### Traditional Web Hosting
1. Upload files via FTP/SFTP to your hosting provider
2. Ensure `index.html` is in the root directory
3. Configure domain and SSL certificate

## 🎨 Customization

### Colors
The website uses CSS custom properties for easy color changes:
```css
:root {
    --primary-blue: #1e3a5f;    /* Main school color */
    --secondary-blue: #2c5282;  /* Secondary blue */
    --accent-gold: #c9a227;     /* Gold accents */
}
```

### Fonts
- **Headlines**: Montserrat (Google Fonts)
- **Body Text**: Open Sans (Google Fonts)

### Images
- Use high-quality images (1200px+ width recommended)
- Unsplash.com provides free professional photos
- Optimize images for web (WebP format preferred)

## 🔒 Security Notes

### Admin Panel Security
- Change the default password in `admin.html`
- The current system uses JavaScript authentication (client-side)
- For production, consider server-side authentication
- Restrict access to `admin.html` via server configuration

### Content Backup
- Always backup `site-content.json` before major changes
- Consider version control (Git) for tracking changes
- Test changes in a staging environment first

## 📱 Mobile Optimization

The website is fully responsive with:
- Mobile-first CSS design
- Touch-friendly buttons and navigation
- Optimized images for different screen sizes
- Fast loading on mobile networks

## 🔧 Technical Details

### Browser Support
- Chrome/Edge/Safari: Latest 2 versions
- Firefox: Latest 2 versions
- Mobile browsers: iOS Safari 14+, Android Chrome 90+

### Performance
- Lightweight vanilla JavaScript (no frameworks)
- Optimized CSS with minimal external dependencies
- Lazy loading for images
- Efficient animations using CSS transforms

### SEO Features
- Semantic HTML5 structure
- Proper heading hierarchy (H1 → H6)
- Meta descriptions and social media tags
- Fast loading speeds
- Mobile-friendly design

## 🆘 Troubleshooting

### Common Issues

#### Content Not Loading
- Check if `site-content.json` exists and is valid
- Verify file permissions on the server
- Check browser console for JavaScript errors

#### Admin Panel Won't Load
- Ensure `admin.html` is in the same directory as `site-content.json`
- Check if browser blocks local file access (use a web server)
- Clear browser cache and cookies

#### Images Not Displaying
- Verify image URLs are correct and accessible
- Check for HTTPS/HTTP mixed content issues
- Ensure images are optimized for web

#### Mobile Display Issues
- Test on actual devices, not just browser tools
- Check viewport meta tag is present
- Verify touch targets are at least 44px

### Getting Help

If you need assistance:
1. **Documentation**: Check this README file
2. **Browser Console**: Press F12 to see JavaScript errors
3. **Backup**: Always restore from a working backup
4. **Support**: Contact your web developer

## 🔄 Updates and Maintenance

### Regular Tasks
- **Weekly**: Check for broken links and images
- **Monthly**: Review and update news/events
- **Quarterly**: Update student testimonials and achievements
- **Annually**: Refresh photos and major content updates

### Content Best Practices
- Keep news articles to 2-3 sentences for summaries
- Use high-quality, properly licensed images
- Maintain consistent tone and voice
- Update contact information promptly
- Archive old events and news regularly

## 📞 Support Information

**Website System**: Easy-Edit CMS v1.0  
**Created**: February 2026  
**Compatible**: All modern browsers  
**Hosting**: Static hosting compatible (GitHub Pages, Netlify, traditional hosting)

---

*Built with ❤️ for the Immaculata High School Spartan community*