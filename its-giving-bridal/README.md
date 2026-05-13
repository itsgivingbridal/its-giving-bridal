# It's Giving Bridal — Website

## Files
- `index.html` — Homepage
- `about.html` — About page
- `services.html` — Services page
- `work.html` — Portfolio/Work page
- `inquire.html` — Inquiry/Contact page
- `style.css` — Shared styles across all pages

## Setup Checklist

### 1. Add Your Images
Create a folder called `images/` in this project folder.
Drop your photos in there and update the `src` attribute on each image tag.
Every image placeholder is marked with a comment like:
`<!-- REPLACE: swap with your hero image path e.g. images/hero.jpg -->`

### 2. Set Up Your Contact Form
The inquiry form uses Formspree (free tier available).
- Go to formspree.io
- Create a new form
- Copy your form ID
- In `inquire.html` replace `YOUR-FORM-ID` in the form action URL

### 3. Deploy to Netlify
- Go to netlify.com
- Connect your GitHub repository
- Netlify will auto-deploy every time you push a change

### 4. Connect Your Domain
- In Netlify: Site Settings > Domain Management > Add Custom Domain
- Enter: itsgivingbridal.com
- Follow the DNS instructions Netlify provides
- Point your domain registrar DNS to Netlify's nameservers

## Making Updates
1. Open the file in VS Code
2. Make your changes
3. Save
4. In GitHub Desktop: commit the change with a short note
5. Push to GitHub — Netlify updates automatically

## Colors
- Matte Black: #0E0E0E
- Charcoal: #383836
- Champagne: #D0C8B4
- Cloud Dancer: #F0EEE9

## Fonts
- Headings: Playfair Display (Bold + Italic)
- Body: Raleway (Light 300)
