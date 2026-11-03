# task9
# Laundry Services Website

A responsive landing page for a laundry service business. The page
includes a navigation bar, a hero section, a washing-machine
illustration, and a call-to-action (CTA) button with an animated hover
effect.

## Features

-   Responsive layout for desktop, tablet, and mobile screens
-   Navigation links for Home, Services, About Us, and Contact Us
-   Mobile navigation menu with a toggle button
-   Hero section with headline and service description
-   CTA button with a smooth hover animation:
    -   Increases in size
    -   Tilts slightly
    -   Displays a soft shadow
-   Keyboard focus styling for the CTA button
-   Reduced-motion accessibility support

## Project Structure

``` text
laundry-services/
├── index.html
├── style.css
└── README.md
```

## Getting Started

1.  Download or clone this project.
2.  Keep `index.html`, `style.css`, and `README.md` in the same folder.
3.  Open `index.html` in your web browser.

No installation or build tools are required.

## Technologies Used

-   HTML5
-   CSS3
-   JavaScript (for the mobile navigation toggle)

## CTA Hover Effect

The CTA button uses CSS transitions and transforms to create the hover
animation:

``` css
.cta {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.cta:hover {
  transform: scale(1.1) rotate(-5deg);
  box-shadow: 0 12px 25px rgba(33, 150, 243, 0.32);
}
```

Move the mouse pointer over **Book a service today!** to see the effect.
When the pointer leaves, the button returns to its original appearance.

## Customization

-   Edit the text and navigation links in `index.html`.
-   Change colors, spacing, typography, and responsive breakpoints in
    `style.css`.
-   Replace the image URL in `index.html` to use a different
    illustration.

## Notes

-   The washing-machine illustration is loaded from an external
    Iconscout URL, so an internet connection is required to display it.
-   The navigation and CTA links currently use `#` placeholders. Replace
    them with real page URLs or section IDs when those pages are
    available.

## License

This project is provided for learning and personal use. Check the
license and usage terms of any third-party image asset before publishing
the website.
