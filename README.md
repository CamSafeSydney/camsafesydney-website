# CamSafe Sydney Website

Professional website for CamSafe Sydney, offering CCTV installation and security solutions across Sydney.

## Features

- Modern, responsive design using Tailwind CSS
- Comprehensive information about CCTV services
- Online quote request system
- Calendly integration for consultations
- Netlify CMS for content management

## Pages

- Home (index.html)
- About Us (about.html)
- Services (services.html)
- Residential CCTV (residential.html)
- Commercial CCTV (commercial.html)
- FAQ (faq.html)
- Testimonials (testimonials.html)
- Contact (contact.html)

## Technology Stack

- HTML5
- Tailwind CSS
- JavaScript
- Netlify CMS
- Netlify Forms

## Deployment

1. The site is configured to deploy on Netlify
2. Connected to domain: camsafesydney.com.au
3. Forms are handled by Netlify Forms
4. Content management through Netlify CMS

## Local Development

To run the site locally:

```bash
# Using Python's built-in server
python3 -m http.server 8000

# Then visit:
http://localhost:8000
```

## Content Management

Access the CMS at: `/admin`

## Domain Configuration

Domain is managed through Namecheap. Configure DNS settings:

```
Type: CNAME
Host: www
Value: [your-netlify-url].netlify.app

Type: A Record
Host: @
Value: [Netlify's Load Balancer IP]
```

## Contact

For support or inquiries:
- Phone: 1300 CAMSAFE
- Email: info@camsafesydney.com.au