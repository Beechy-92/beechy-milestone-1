# Pawsitive Training

## Live Site

[Click here to view the live website] https://beechy-92.github.io/beechy-milestone-1/

**Pawsitive Training** is a responsive, multi-page website built for a fictional dog training buisness based in Cheadle, Staffordshire. The site provides information about dog trtaining classes, social dog walks, and specialised sessions, with the goal of encouraging user engagement and sign-ups.

---

## Project Overview

This website was created as part of a front-end development project and includes:

- A responsive navigation system
- An engaging photo gallery
- A functional sign-up form
- Consistant visual design across all pages

The project follows modern best practices in HTML and CSS to deliver a clean, accessable user experience.

---

## File and Folder Structure

'''
/
   index.html          # Homepage
   gallery.html        # Gallery page with dog photos
   signup.html         # Sign-up form for users
   style.css           # Custom style sheet
   assets/
     ___> images/      # Project images
'''

---

## Features

### General
- Fully responsive layout (mobile first design)
- Semantic HTML5 for enhanced accessibility 
- External CSS for clean seperation of concerns helping with organisation, readability and maintainable code.

### Homepage (`index.html`)
- Hero section with branding and CTA
- Summary of services
- Embedded navigation

### Gallery Page (`gallery.html`)
- Responsive photo gallery using `column count`
- Hover zoom effect for images

### Sign-Up Page (`signup.html`)
- Form with required fields and accessible labels
- Uses `formdump.codeinstitute.net` to simulate submissions

### Navigation
- Mobile-friendly navigation with a burger toggle
- Transforms to a horizontal navbar on larger screens

### Footer
- Font awesome social icons
- Consistant across all pages

---

**Fonts**: 
  - Headings: [Oswald](https://fonts.google.com/specimen/Oswald)
  - Body: [Lato](https://fonts.google.com/specimen/Lato)
**Color Scheme**:
  - Primary: Earthy green tones to reflect nature and trust
  - Accent: Light cream for contrast
**Layout**:
  - Flexbox and media queries used for responsive structure
  - Column-based image gallery for visual engagement

---

## Deployment

### GitHub Pages

To deploy this project:

1. Push your code to a GitHub repository.
2. Navigate to **Settings** > **Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder.
4. Click **Save**.
5. GitHub will generate a link to your live website (e.g., `https://beechy-92.github.io/beechy-milestone-1/`).

**Important**: Ensure all paths to files (e.g., images, stylesheets) are **relative**, not absolute.

---

## Project Rationale

Pawsitive Training was developed in response to the need for a central online hub for dog training services and community engagement for pet owners in the Cheadle, Staffordshire area.

### Target Audience

- New or first-time dog owners seeking support.
- Dog owners interested in socialisation and behaviour training.
- Local residents looking for community pet-friendly events.

### User Needs & Stories

- As a new dog owner, I want to easily find training options near me.
- As a pet owner, I want to sign up for events online to save time.
- As a community member, I want to see schedules and event details quickly.
- As a cautious user, I want to view photos of past sessions before committing.

### Why This Solution?

The website is:
- Easy to navigate, even on mobile.
- Optimised for clear and fast access to training information.
- Designed to encourage user trust and participation through testimonials and images.
- Built with accessibility and user engagement as key priorities.

---

## Testing

### Manual Testing

#### Desktop
- Chrome, Firefox, Edge, Safari
- Screen sizes: 1024px+, 1440px

#### Mobile & Tablet
- iPhone (iOS Safari, Chrome)
- Android (Chrome, Firefox)
- Responsive layout tested at:
  - ≤480px (phones)
  - 481–768px (tablets)
  - 769–1024px (small laptops)
  - 1025px+ (desktops)

### Functional Testing

- Navigation links work on all devices
- Burger menu toggles open/close
- Images load correctly and resize on smaller screens
- Form submits data via external endpoint
- HTML and CSS pass [W3C validation](https://validator.w3.org/)

<img src="assets\readme-images\css-validation.jpg" alt="CSS Validation" width="300">
<img src="assets\readme-images\home-validation.jpg" alt="Home Validation" width="300">
<img src="assets\readme-images\gallery-validation.jpg" alt="Gallery Validation" width="300">
<img src="assets\readme-images\signup-validation.jpg" alt="Sign-Up Validation" width="300">

### Walkthrough Testing

[Watch the walkthrough test 1 here](https://app.screencastify.com/v3/watch/biftxotph59y1d7xc2xe)

- As you can see there was an issue with the browser showing the content on the homepage.
- This was solved with a quick refresh of the browser.

[Watch the walkthrough test 2 here](https://app.screencastify.com/v3/watch/3dMLtkof2vInppzhR6Us)

### Accessibility

- Uses semantic HTML5 elements
- All images contain descriptive `alt` text
- Form fields have proper `label` associations
- Good color contrast for readability
- Keyboard navigable
- All images checked and any special characters removed

---

## Performance Optimization

- Images resized and compressed
- CSS minified for efficiency
- External resources (e.g., fonts, icons) loaded via CDN

---

## Screenshots

<img src="assets\readme-images\home-page.png" alt="Home Page" width="300">
<img src="assets\readme-images\gallery.png" alt="Gallery Page" width="300">
<img src="assets\readme-images\sign-up.png" alt="Sign-Up Page" width="300">

---

## Credits

- **Font Awesome** – for social media icons  
- **Google Fonts** – for Oswald and Lato  
- **Code Institute’s Formdump** – for testing form submissions  
- **All images** – provided by the project owner

---

## License

This project is created for educational purposes and is not intended for commercial use.