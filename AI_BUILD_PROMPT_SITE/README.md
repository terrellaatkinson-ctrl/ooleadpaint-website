# 00 Lead Inspections & Abatements LLC - Website

A modern, responsive, SEO-optimized website for 00 Lead Inspections & Abatements LLC. This website showcases certified lead paint inspection and risk reduction services for Maryland homeowners, landlords, and property managers.

## 📁 Project Structure

```
website/
├── index.html                 # Homepage
├── assets/
│   ├── css/
│   │   └── styles.css        # Main stylesheet with responsive design
│   └── js/
│       └── script.js         # JavaScript functionality
└── pages/
    ├── mission.html          # About Us / Mission page
    ├── services.html         # Services & Pricing
    ├── landlords.html        # Landlord Compliance Guide
    ├── health-risks.html     # Health Risks of Lead Exposure
    ├── compliance.html       # Compliance & Regulations
    ├── videos.html           # Educational Videos
    ├── testimonials.html     # Client Reviews
    └── contact.html          # Contact Form & Information
```

## 🎯 Pages Included

### 1. **Homepage (index.html)**
- Hero section with strong call-to-action
- Trust badges and certifications
- Services overview
- "Why Choose Us" section
- Testimonials preview
- Contact information and booking CTA

### 2. **Our Mission (mission.html)**
- Company history and values
- Explanation of risk reduction vs. abatement
- Certifications and credentials
- Promise to customers

### 3. **Services (services.html)**
- Detailed service descriptions
- Lead Paint Inspection service details
- Risk Reduction Practices guidance
- How we work process
- FAQ section
- Accordion functionality for Q&A

### 4. **For Landlords (landlords.html)**
- Landlord compliance requirements
- Legal obligations overview
- Affordable risk reduction examples
- Timeline for compliance
- Tenant notification requirements
- FAQ for landlords

### 5. **Health Risks (health-risks.html)**
- Lead poisoning symptoms in children and adults
- Sources of lead in homes
- Who is most at risk
- Prevention steps
- Links to external health resources

### 6. **Compliance & Regulations (compliance.html)**
- Maryland lead safety law overview
- EPA regulations (RRP Rule, Disclosure Rule)
- MDE certification information
- Official regulatory resource links
- Compliance FAQ with accordion

### 7. **Videos (videos.html)**
- Embedded YouTube videos for:
  - Pre-inspection preparation guide
  - Lead prevention tips
- Links to YouTube channel
- FAQ about inspections

### 8. **Testimonials (testimonials.html)**
- Client reviews and feedback
- Why clients trust the company
- Service statistics
- Links to other pages

### 9. **Contact (contact.html)**
- Contact form with validation
- Contact information
- Business hours
- Service area map (Google Maps embed)
- FAQ section

## 🎨 Design Features

### Color Scheme
- **Primary Green**: #43a047 (Trust, safety, growth)
- **Primary Black**: #000 (Authority, professionalism)
- **Accent Gray**: #f5f5f5 (Clean, modern)

### Responsive Design
- Mobile-first approach
- Hamburger menu for mobile devices (< 480px)
- Tablet-optimized layout (768px breakpoint)
- Full desktop experience

### Accessibility
- Skip to content link
- Semantic HTML
- ARIA labels
- Keyboard navigation support
- High contrast colors
- Readable font sizes

## ✨ Key Features

### Navigation
- Sticky navigation bar
- Mobile hamburger menu with toggle
- Active page highlighting
- Breadcrumb navigation on inner pages

### Interactive Elements
- Accordion functionality for FAQs
- Smooth scrolling to sections
- Form validation on contact form
- Notification system for form submission
- Lazy loading for images (when applicable)
- Hover effects on buttons and cards

### SEO Optimization
- Meta descriptions on all pages
- Schema markup for Local Business
- SEO-friendly titles
- Proper heading hierarchy
- Alt text placeholders for images
- Mobile-responsive meta viewport
- Canonical URLs
- Open Graph tags

### Forms
- Contact form with validation
- Email field validation
- Phone field formatting support
- Subject dropdown for categorization
- Privacy policy checkbox

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+ (full layout)
- **Tablet**: 768px - 1199px (adjusted grid)
- **Mobile**: 480px - 767px (single column, hamburger menu)
- **Small Mobile**: < 480px (optimized for small screens)

## 🚀 Getting Started

### 1. Open the Website
```bash
# Open index.html in your browser
# Or use a local server:
python -m http.server 8000
# Then visit: http://localhost:8000
```

### 2. File Structure
- Place all files in the same directory structure
- CSS is in `assets/css/styles.css`
- JavaScript is in `assets/js/script.js`
- All pages link relatively within the structure

### 3. Customization

#### Update Contact Information
- Edit phone number: Search for "443-839-3565"
- Edit email: Search for "terrell@ooleadpaint.com"
- Edit address: Update in footer and contact page
- Edit hours: Update in footer and contact page

#### Update Social Media Links
- Facebook: Update href in social icons
- Instagram: Update href in social icons
- LinkedIn: Update href in social icons
- YouTube: Update href in social icons

#### Embed Calendly
- All booking buttons link to: `https://calendly.com/terrell-ooleadpaint`
- Update with your own Calendly link if needed

#### Add Google Analytics
- Find the Google Analytics placeholder in index.html
- Replace `GA_MEASUREMENT_ID` with your actual ID

#### Customize Google Map
- Update the map embed in contact.html
- Replace the iframe src with your Google Maps embed code

## 🔧 JavaScript Features

### Mobile Navigation Toggle
```javascript
// Hamburger menu functionality
// Toggles nav-links visibility on mobile
```

### Accordion
```javascript
// Click accordion headers to expand/collapse
// Only one section open at a time
```

### Form Handling
```javascript
// Form validation
// Success/error notifications
// Email validation
```

### Smooth Scrolling
```javascript
// Anchor links scroll smoothly
// Scroll behavior: smooth
```

### Lazy Loading
```javascript
// Lazy load images using IntersectionObserver
// Add data-src attribute to images
```

## 📊 SEO Considerations

### On-Page SEO
- ✅ Unique title tags on every page
- ✅ Meta descriptions (150-160 characters)
- ✅ Proper heading hierarchy (H1, H2, H3)
- ✅ Keyword usage: "Lead Paint Inspection Maryland", "Baltimore Risk Reduction", "Certified MDE Inspector"
- ✅ Internal linking between pages
- ✅ Mobile responsive design
- ✅ Fast load times (CSS/JS optimized)

### Schema Markup
- LocalBusiness schema on homepage
- Service schema for lead paint inspection
- Aggregate ratings for reviews
- Open Graph tags for social sharing

### Technical SEO
- Canonical URLs
- Sitemap-ready structure
- Clean URL structure
- Mobile-first responsive
- Accessibility standards (WCAG)

## 🔐 Security Notes

- Form data is validated on client-side
- For production, implement server-side validation and email handling
- Consider using a form service like:
  - Formspree
  - GetForm
  - Basin
  - Email.js

## 📝 Content Management

### Update Testimonials
- Edit testimonials in `pages/testimonials.html`
- Maintain 5-star rating format
- Update author locations

### Add New Services
- Edit services section in `pages/services.html`
- Update pricing information
- Add to services grid

### Update Certifications
- Edit MDE certificate numbers if they change
- Update dates and credentials

### Add New Pages
- Create new HTML file in `pages/` directory
- Copy navigation from existing page
- Copy footer from existing page
- Link from main navigation

## 🎓 Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📲 Mobile Optimization

- Touch-friendly buttons (min 44px)
- Mobile menu for small screens
- Fast loading (optimized CSS/JS)
- Responsive images
- No horizontal scroll
- Readable font sizes

## 🖼️ Image Recommendations

For best results, add images to:
- Homepage hero section
- Services cards
- Team photos on Mission page
- Before/after examples
- Service area map

Use placeholder images from:
- Unsplash
- Pexels
- Pixabay

## 📞 Support & Customization

To customize this website further:

1. **Change Colors**: Edit CSS variables at top of `styles.css`
2. **Add Images**: Create `assets/images/` folder and reference in HTML
3. **Update Content**: Edit text directly in HTML files
4. **Add Pages**: Create new HTML file with template structure
5. **Modify Styles**: Update `styles.css` for design changes

## 🚀 Deployment

### Host on Various Platforms:
- **Netlify**: Drag & drop folder
- **GitHub Pages**: Push to `gh-pages` branch
- **Vercel**: Connect GitHub repo
- **Traditional Host**: FTP upload files

### Domain
- Update domain DNS to point to hosting
- Update canonical URLs if domain changes
- Update social media links with new domain

## 📋 Checklist Before Launch

- [ ] Replace placeholder phone number
- [ ] Replace placeholder email
- [ ] Update address
- [ ] Add Google Analytics ID
- [ ] Update Calendly link
- [ ] Customize Google Map
- [ ] Add business logo
- [ ] Update social media links
- [ ] Test on mobile devices
- [ ] Check all links work
- [ ] Test contact form
- [ ] Verify SEO meta tags
- [ ] Set up email notifications
- [ ] Configure form submission handling

## 📄 License

This website template is created for 00 Lead Inspections & Abatements LLC. Customize as needed for your business.

---

**Created**: 2024
**Last Updated**: November 14, 2024
**Version**: 1.0
