# index.html

## About

This page serves as the **homepage** of the PC Setup Central website. It provides an overview of the site's purpose and links to its main sections through both text and clickable image tiles.

## Features

- Navigation bar with links to all major pages
- Grid layout with image-based links to:
  - Beginner vs Advanced
  - Workstation vs Gaming
  - Reviews & Comparisons
  - Accessories, Aesthetics & Maintenance
- Responsive design and unified styling

## Notes

- The homepage introduces users to the overall structure of the website.
- Images are manually added and self-made or sourced from royalty-free collections.

# setup.html

## About

This page compares **Beginner Builds** and **Advanced Builds**. It helps users understand the difference between entry-level and performance-oriented PC setups.

## Features

- Two major sections:
  - Beginner PC Build
  - Advanced PC Build
- Bullet point breakdowns for each type of build
- Covers components, installation tips, and optimization
- Linked from `index.html` and returns to it

## Notes

- This page is purely informative and does not use external APIs.
- Future versions may include charts or video walkthroughs.

# pc.html

## About

This page provides a comparison between **Workstation PCs** and **Gaming PCs**, showing users how to choose the best build for their use case.

## Features

- Divides content into two major sections:
  - Workstation PC
  - Gaming PC
- Uses bullet points to explain component choices, features, and design priorities
- Consistent layout and styling with the rest of the site

## Notes

- Each section can be expanded in the future to include specific build recommendations or benchmarking links.

# review.html

## About

This page provides **component reviews and comparisons**, with a focus on:
- CPU performance
- GPU performance
- Cooling options

## Features

- Three sections: CPU, GPU, Cooling
- Each section has:
  - A clickable image (links to external reviews)
  - Bullet points explaining comparison factors
- Uses flexbox for image-left/content-right layout

## Notes

- All images are clickable and open external sources in new tabs.
- All content is summarized in plain language; no proprietary data is used.


# extra.html

## About

This page includes information about **accessories, visual customization, and maintenance** practices that improve a PC's usability and lifespan.

## Features

- Three sections:
  - Essential Accessories (mice, keyboards, monitors)
  - Aesthetic Add-ons (RGB, cables, themed cases)
  - Maintenance (cleaning, thermal paste, airflow)
- Content is organized using clean, semantic HTML and styled lists

## Notes

- This page is intended for long-term PC owners looking to maintain or beautify their builds.
- Can be expanded to include video links or maintenance kits.

# PR3.css

## About

This file contains the **primary stylesheet** for the PC Setup Central website. It defines the layout, color scheme, typography, spacing, and responsive behavior for all HTML pages.

## Class Reference

### .review-section
- A flex container for placing an image on the left and a list or content on the right.
- Used in `review.html` for CPU, GPU, and Cooling comparisons.

### .image-box
- Container for images in the flex layout.
- Controls max width and applies shadows and border radius to images.

### .text-box
- Wraps bullet point lists or descriptive content beside images.
- Expands to fill available space in `.review-section`.

### `.navbar` *(optional if used)*
- If included in future versions, controls the fixed top navigation bar layout and spacing.

## Tag Styling

- Global reset applied using `* { box-sizing: border-box; }`
- `body`: Sets font family, background color, text color, and base layout
- `header`: Dark background with light text; center-aligned title and nav
- `nav a`: Styled navigation links with spacing, color, and hover effects
- `main`: Applies padding, max width, center alignment, and drop shadows
- `ul`, `li`: Consistent list formatting for all sections

## Responsive Behavior

- `flex-wrap: wrap` is applied to `.review-section` for mobile responsiveness.
- Image and text stack vertically on small screens (handled naturally by flexbox).
- Can be extended with media queries if needed.

## Planned Enhancements

- Add media queries for smaller screens (below 768px) to adjust text size and padding.
- Introduce light/dark mode toggle (optional).
- Create additional utility classes for margins, alignment, or section spacing.

## Notes

- All styles in this file are custom-written and do not depend on third-party frameworks.
- The layout has been tested for compatibility on Chrome and Firefox desktop.
- Used across all HTML pages for consistency.


## Contributors
This page was fully developed by Sheldon Tang
