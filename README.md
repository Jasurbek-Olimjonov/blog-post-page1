# Blog Post Page

A food blog post / magazine-style landing page built as a front-end practice project, focused on translating a design into a pixel-close layout using Bootstrap's utility classes and SASS.

## Live Demo
[View live site](https://Jasurbek-Olimjonov.github.io/blog-post-page1/)

## Overview
This project recreates a full-page food blog layout — header section, post content, inbox to follow and recipe columns are built with Bootstrap's utilities (like `d-flex`, `d-grid` and mostly 'spacing utilities'), used SASS for staff Bootstrap couldn't handle.

## Built With
- HTML5
- SASS (SCSS)
- Bootstrap 5 — display, position, and spacing/margin utility classes
- Custom SASS overrides for layout details Bootstrap couldn't handle out of the box

## Approach
Most of the layout — spacing, alignment, and structure — was handled using Bootstrap's built-in utility classes (`d-flex`, `position-absolute`, margin/padding helpers, etc.) rather than writing custom CSS from scratch. Custom SASS was used selectively, for the specific layout details and fine adjustments that Bootstrap's utility system doesn't cover directly.

## What I Practiced
- Deciding when to reach for a utility class vs. writing custom SASS
- Positioning elements precisely within their containers using `flex`, `position`, and `translate-middle` utilities
- Centering and aligning overlapping elements (like images and badges) using Bootstrap's `translate-middle` class combined with `position-absolute`

## Project Structure

```
blog-post-page1/
├── assets/
|   ├── images/
|   ├── svg/
├── styles/
│   ├── sections/
│   ├── utils/
│   │   ├── _mixins.scss
│   │   ├── _utilities.scss
│   │   └── _variables.scss
│   ├── style.css
│   ├── style.css.map
│   └── style.scss
├── LICENSE
└── index.html
```

## Getting Started
Clone the repo and open `index.html` in your browser — or, if you're editing the SASS:
```bash
git clone https://github.com/Jasurbek-Olimjonov/blog-post-page1.git
cd blog-post-page1
# compile SASS if using a live-sass-compiler or similar
```

## Author
**Jasurbek Olimjonov**
[GitHub](https://github.com/Jasurbek-Olimjonov)

## License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
