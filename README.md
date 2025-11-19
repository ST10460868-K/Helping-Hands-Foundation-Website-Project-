# Helping Hands Foundation Website
## WEDE5020 - Web Development Assignment - Part 3

**Student ID:** ST10460868  
**Project:** Community Foundation Website  
**Submission Date:** 19 November 2025

---

 🎯 Project Overview

The Helping Hands Foundation website is a comprehensive web platform for a fictional charitable organization based in Johannesburg, South Africa. The website facilitates community engagement through three core programs: Food Distribution, Education Support, and Shelter Assistance.

**Website Purpose:**
- Inform visitors about charitable programs
- Enable volunteer and sponsor enrollment
- Provide contact and location information
- Showcase community impact through interactive galleries

---

 🚀 Part 3 Enhancements

### JavaScript Functionality Implemented

 1. Interactive Elements
- ✅ **Accordion Components** - Program details expand/collapse smoothly
- ✅ **Tabs Interface** - Navigation between Overview, Impact, and Locations
- ✅ **Modal Windows** - Form submission responses and lightbox gallery
- ✅ **Lightbox Gallery** - Full-screen image viewing with keyboard navigation
- ✅ **Animated Statistics** - Counter animations on Impact tab
- ✅ **Search Functionality** - Real-time program filtering
- ✅ **Smooth Scrolling** - Enhanced navigation experience

 2. Interactive Maps
- ✅ **Leaflet.js Integration** - Open-source mapping library
- ✅ **Multiple Location Markers** - Johannesburg office and Soweto center
- ✅ **Popup Information** - Address and contact details on markers
- ✅ **Responsive Map Display** - Mobile-friendly implementation

 3. Dynamic Content
- ✅ **Real-time Search** - Filter programs by keywords
- ✅ **Dynamic Form Fields** - Show/hide based on user selection
- ✅ **Animated Counters** - Impact statistics count up
- ✅ **Character Counters** - Live feedback on text input length

 4. Form Validation & Functionality

**Enquiry Form (enquiry.html):**
- Full name validation (letters and spaces only)
- Email format validation with regex
- South African phone number validation (+27 or 0 prefix)
- Date of birth validation (age 16-100)
- Role selection (volunteer/sponsor/both)
- Conditional field display based on role
- Program selection via checkboxes
- Availability dropdown validation
- Sponsorship amount validation (minimum R100)
- Message length validation (10-500 characters)
- Terms agreement checkbox
- Real-time validation with visual feedback
- Success/error icons
- Modal response with personalized details

**Contact Form (contact.html):**
- Name and email validation
- Optional phone number validation
- Message type dropdown (General, Support, Feedback, etc.)
- Subject line validation
- Message body validation (10-1000 characters)
- Character counter
- Email compilation with mailto: functionality
- Opens default email client with pre-filled data
- Success modal with instructions

 SEO Optimization

 On-Page SEO
- ✅ **Title Tags** - Unique, descriptive titles for each page (50-60 characters)
- ✅ **Meta Descriptions** - Compelling descriptions with keywords (150-160 characters)
- ✅ **Meta Keywords** - Relevant keywords for each page
- ✅ **Header Tags Hierarchy** - Proper H1, H2, H3 structure
- ✅ **Image Alt Text** - Descriptive alt attributes for accessibility
- ✅ **Clean URLs** - Semantic file naming (Programs.html, Contact.html)
- ✅ **Internal Linking** - Strategic links between pages
- ✅ **Mobile Responsive** - Optimized for all devices
- ✅ **Open Graph Tags** - Social media sharing optimization

 Technical SEO
- ✅ **robots.txt** - Search engine crawler instructions
- ✅ **sitemap.xml** - XML sitemap with all pages
- ✅ **Semantic HTML** - Proper use of HTML5 elements
- ✅ **Fast Loading** - Optimized images and minimal dependencies
- ✅ **HTTPS Ready** - Prepared for secure hosting
- ✅ **Schema Markup Ready** - Structured data preparation

 Performance Optimization
- Minified CSS in critical sections
- Lazy loading for images (via browser native)
- CDN usage for external libraries
- Compressed image formats suggested (WebP)
- Efficient JavaScript execution

---

 💻 Technologies Used

 Core Technologies
- **HTML5** - Semantic markup and structure
- **CSS3** - Styling, animations, and responsive design
- **JavaScript (ES6+)** - Interactive functionality and validation

 Libraries & Frameworks
- **Leaflet.js 1.9.4** - Interactive mapping
- **OpenStreetMap** - Map tile provider
- **Google Fonts** - Typography (Segoe UI fallback)

 Development Tools
- **Git** - Version control
- **GitHub** - Repository hosting
- **VS Code** - Code editor (recommended)

---

 ✨ Features Implementation

 Programs Page (Programs.html)
1. **Interactive Program Cards** - Hover effects and click handlers
2. **Accordion Details** - Expandable program information
3. **Image Gallery** - 4 images per program with lightbox
4. **Lightbox Navigation** - Previous/Next buttons and keyboard support
5. **Search Filter** - Real-time program filtering
6. **Tabbed Interface** - Overview, Impact, Locations
7. **Animated Statistics** - Count-up animations
8. **Interactive Map** - Leaflet.js with location markers

 Enquiry Page (Enquiry.html)
1. **Multi-step Logic** - Conditional field display
2. **Comprehensive Validation** - All input types validated
3. **Real-time Feedback** - Success/error indicators
4. **Character Counters** - Live text length tracking
5. **Role-based Fields** - Volunteer vs Sponsor options
6. **Program Selection** - Checkbox array for volunteers
7. **Amount Validation** - Minimum sponsorship checking
8. **Success Modal** - Personalized response display
9. **Form Reset** - Clean state after submission

 Contact Page (Contact.html)
1. **Contact Information Cards** - Office details with icons
2. **Office Hours Display** - Operating times
3. **Social Media Links** - Placeholder for future integration
4. **Message Type Selector** - Categorized inquiries
5. **Email Integration** - Mailto functionality
6. **Dual-location Map** - Both offices displayed
7. **Validation System** - Comprehensive input checking
8. **Email Compilation** - Formatted message body

---

 🔍 SEO Optimization Details

 Keyword Strategy
**Primary Keywords:**
- Helping Hands Foundation
- Johannesburg charity
- Community programs South Africa
- Volunteer Johannesburg
- Charity sponsor

**Secondary Keywords:**
- Food distribution program
- Education support
- Shelter assistance
- Soweto community help
- Gauteng foundation

 Meta Tags Implemented

**Index.html:**
```html
<title>Helping Hands Foundation | Community Support Johannesburg</title>
<meta name="description" content="Helping Hands Foundation supports families in Johannesburg through food distribution, education programs, and shelter assistance since 2012.">
```

**Programs.html:**
```html
<title>Our Programs - Food, Education & Shelter | Helping Hands Foundation</title>
<meta name="description" content="Discover Helping Hands Foundation's community programs: food distribution, education support, and shelter assistance across Johannesburg and Soweto.">
```

**Enquiry.html:**
```html
<title>Get Involved - Volunteer & Sponsor | Helping Hands Foundation</title>
<meta name="description" content="Join Helping Hands Foundation as a volunteer or sponsor. Make a difference in Johannesburg communities.">
```

**Contact.html:**
```html
<title>Contact Us - Get in Touch | Helping Hands Foundation Johannesburg</title>
<meta name="description" content="Contact Helping Hands Foundation. Reach our offices in Johannesburg and Soweto.">
```

 URL Structure
- `/Index.html` - Homepage
- `/About.html` - About the foundation
- `/Programs.html` - Program details
- `/Enquiry.html` - Volunteer/sponsor enrollment
- `/Contact.html` - Contact information

### Image Optimization
- Descriptive file names (e.g., `food-distribution-program.jpg`)
- Alt text on all images
- Recommended formats: WebP for photos, SVG for icons
- Compressed sizes for faster loading

---

## 📦 Installation & Setup

### Precondition
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code recommended)
- Git for version control
- Local web server (optional - Live Server extension)

### Setup Instructions

1. **Clone Repository**
```bash
[git clone https://github.com/yourusername/helping-hands-foundation.git](https://github.com/ST10460868-K/Helping-Hands-Foundation-Website-Project-.git)
cd helping-hands-foundation
```

2. **File Structure Check**
Ensure all files are present:
```
helping-hands-foundation/
├── Index.html
├── About.html
├── Programs.html
├── Enquiry.html
├── Contact.html
├── Style.css
├── script.js
├── robots.txt
├── sitemap.xml
├── README.md
└── images/
    ├── food-program/
    ├── education-program/
    └── shelter-program/
```

3. **Update Image Paths**
Replace local file paths with:
- Relative paths: `images/food-program/image1.jpg`
- OR use placeholder services: Unsplash URLs (as implemented)

5. **Test Locally**
- Open `Index.html` in browser
- OR use Live Server extension in VS Code
- Test all navigation and forms

6. **Deploy**
- Upload to web hosting (GitHub Pages, Netlify, etc.)
- Verify all links work
- Test forms and interactive elements

---

## 📁 File Structure

```
Project Root/
│
├── Index.html              # Homepage with hero section
├── About.html              # Foundation history and mission
├── Programs.html           # Interactive program showcase
├── Enquiry.html            # Volunteer/sponsor form
├── Contact.html            # Contact form with email
├── Style.css               # Main stylesheet
├── script.js               # Global JavaScript
├── robots.txt              # Search engine instructions
├── sitemap.xml             # XML sitemap
├── README.md               # This file
│
└── images/                 # Image directory (to be created)
    ├── food-program/
    │   ├── image1.jpg
    │   └── image2.jpg
    ├── education-program/
    │   ├── image1.jpg
    │   └── image2.jpg
    └── shelter-program/
        ├── image1.jpg
        └── image2.jpg
```

---

## 📚 References

### Documentation & Tutorials
1. **MDN Web Docs** - HTML, CSS, JavaScript Reference  
   URL: https://developer.mozilla.org/  
   Used for: Form validation, DOM manipulation, event handling

2. **W3Schools** - Web Development Tutorials  
   URL: https://www.w3schools.com/  
   Used for: CSS animations, form elements, validation patterns

3. **Leaflet.js Documentation**  
   URL: https://leafletjs.com/reference.html  
   Used for: Interactive map implementation, markers, popups

4. **Google SEO Starter Guide**  
   URL: https://developers.google.com/search/docs/fundamentals/seo-starter-guide  
   Used for: On-page SEO optimization, meta tags, sitemap creation

5. **Moz SEO Learning Center**  
   URL: https://moz.com/learn/seo  
   Used for: Keyword research, meta descriptions, title tag optimization

### Code Resources
6. **Stack Overflow** - Programming Q&A  
   URL: https://stackoverflow.com/  
   Used for: JavaScript validation solutions, CSS flexbox issues

7. **RegExr** - Regular Expression Testing  
   URL: https://regexr.com/  
   Used for: Email validation, phone number patterns

8. **Unsplash** - Free Stock Photos  
    URL: https://unsplash.com/  
    Used for: Placeholder images for programs

### Tools & Libraries
9. **Leaflet.js** - Open-source JavaScript Library  
    Version: 1.9.4  
    URL: https://leafletjs.com/  
    License: BSD 2-Clause License

10. **OpenStreetMap** - Map Tile Provider  
    URL: https://www.openstreetmap.org/  
    License: Open Database License (ODbL)

11. **Font Awesome** - Icon Library (if used)  
    URL: https://fontawesome.com/  
    License: Free License

### Accessibility Resources
12. **WCAG 2.1 Guidelines**  
    URL: https://www.w3.org/WAI/WCAG21/quickref/  
    Used for: Color contrast, keyboard navigation, form labels

13. **WebAIM** - Web Accessibility Resources  
    URL: https://webaim.org/  
    Used for: Form accessibility, semantic HTML

### Validation Tools
14. **W3C HTML Validator**  
    URL: https://validator.w3.org/  
    Used for: HTML markup validation

15. **W3C CSS Validator**  
    URL: https://jigsaw.w3.org/css-validator/  
    Used for: CSS syntax validation

16. **Google PageSpeed Insights**  
    URL: https://pagespeed.web.dev/  
    Used for: Performance optimization

### Learning Resources
17. **freeCodeCamp** - Web Development Curriculum  
    URL: https://www.freecodecamp.org/  
    Used for: JavaScript concepts, responsive design

18. **YouTube - Traversy Media**  
    URL: https://www.youtube.com/@TraversyMedia  
    Used for: JavaScript form validation tutorials

---

## 🎓 Academic Integrity Statement

This project was completed independently for WEDE5020 Part 3. All code was written by the student (ST10460868) with reference to the documentation and resources listed above. External libraries (Leaflet.js) are properly attributed and used under their respective licenses.

---

## 📞 Support

For questions or issues:
- **Student Email:** st10460868@rcconnect.edu.za
- **Lecturer:** S Malepe
- **Institution:** Rosebank College

---

## 📄 License

This project is submitted for academic purposes as part of the WEDE5020 course. All rights reserved by the student author.

---

**Last Updated:** November 16, 2025  
**Version:** 3.0  
**Student ID:** ST10460868
