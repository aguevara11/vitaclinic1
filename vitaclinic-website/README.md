# VitaClinic Website

Modern, responsive website for VitaClinic dental clinic in Veracruz, Mexico.

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile
- **WhatsApp Integration**: Direct contact via WhatsApp with pre-filled messages
- **Modern UI**: Clean, professional design with VitaClinic's brand colors
- **Smooth Animations**: Scroll animations and transitions
- **Contact Form**: Redirects to WhatsApp with form data

## Structure

```
vitaclinic/
├── index.html          # Main homepage
├── css/
│   └── style.css       # All styling
├── js/
│   └── main.js         # JavaScript functionality
└── images/             # Logo and photos (to be added)
```

## Setup Instructions

1. **Add Images**:
   - Place the VitaClinic logo as `images/vitaclinic-logo.png`
   - Add team member photos:
     - `images/dra-alheli.jpg`
     - `images/dr-kaleb.jpg`
     - `images/dra-adriana.jpg`
     - `images/lic-diana.jpg`

2. **Update WhatsApp Number**:
   - Open `index.html`
   - Find all instances of `522299999999`
   - Replace with actual clinic WhatsApp number (format: 52 + 10-digit number)
   - Also update in `js/main.js` line 54

3. **Update Contact Info**:
   - Add actual clinic address in the contact section
   - Update Instagram handle if different from @vitaclinic.ver

## WhatsApp Integration

The website includes several WhatsApp touchpoints:

1. **Hero Section**: Primary CTA button with pre-set greeting message
2. **Contact Section**: Large WhatsApp button
3. **Contact Form**: Submits via WhatsApp with all form fields included
4. **Phone Numbers**: Click-to-WhatsApp functionality

### WhatsApp Message Format

When users submit the contact form, it creates a WhatsApp message like:
```
Hola! Mi nombre es [Name].

Teléfono: [Phone]
Correo: [Email]

Mensaje: [Message]
```

## Customization

### Colors
Main brand colors are defined in `css/style.css`:
- Primary: `#6BA4B8` (soft teal/blue)
- Secondary: `#E8D5C4` (beige/tan)
- Accent: `#4A90A4` (darker teal)

### Services
Edit the services section in `index.html` to add/modify services offered.

### Team Members
Team member information is in the "Nuestro Equipo" section of `index.html`.

## Hosting Options

This is a static site and can be hosted on:
- GitHub Pages (free)
- Netlify (free)
- Vercel (free)
- Any web hosting service

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Future Enhancements

Potential additions for phase 2:
- Employee portal for payment tracking
- Online appointment booking system
- Patient testimonials section
- Photo gallery
- Services detail pages
- Blog section

## Notes

- All text is in Spanish (Mexican market)
- Mobile-first responsive design
- No backend required (static site)
- WhatsApp integration eliminates need for email server
- Form validation included
- Smooth scroll navigation

---

Built with HTML, CSS, and vanilla JavaScript.
