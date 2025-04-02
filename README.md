# Basatwar Physio Care Website

A modern, responsive website for Basatwar Physio Care, featuring Dr. Mrunali Basatwar's physiotherapy services.

## Features

- Responsive design that works on all devices
- Modern and soothing color scheme
- Interactive appointment booking system
- About section with doctor's credentials
- Services section showcasing available treatments
- Contact information and working hours
- Mobile-friendly navigation
- Smooth scrolling and animations
- Form validation and date restrictions (no Sunday appointments)

## Setup Instructions

1. Clone this repository to your local machine
2. Open the `index.html` file in a web browser
3. For development, you can use a local server (recommended)

### Using a Local Server

You can use Python's built-in HTTP server:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then open `http://localhost:8000` in your browser.

## Customization

### Images
- Replace `doctor-placeholder.jpg` with Dr. Mrunali Basatwar's professional photo
- Replace `hero-bg.jpg` with your preferred hero section background image

### Contact Information
Update the contact information in the `index.html` file:
- Clinic address
- Phone number
- Email address

### Working Hours
The working hours are set to Monday-Saturday, 9:00 AM - 7:00 PM. You can modify these in the contact section of `index.html`.

## Technologies Used

- HTML5
- CSS3 (with CSS Variables and Flexbox/Grid)
- JavaScript (Vanilla)
- Font Awesome Icons

## Browser Support

The website is compatible with all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Notes

- The appointment booking form currently shows a success message but doesn't actually send data to a server. You'll need to implement the backend functionality to handle form submissions.
- The website uses a soothing blue color scheme that can be customized in the `styles.css` file.
- All animations and transitions are optimized for performance. 