# Amazon Product Page Clone

A mock Amazon product page built as part of a **Full Stack Development** course project. The page replicates the look and feel of a real Amazon product listing using only **HTML** and **CSS** — no JavaScript.

The featured product is a *Steampunk Hippo Figurine*, used to demonstrate a complete product detail page including image gallery, product info, buy box, related items, and footer.



## Features

- Fully static front-end built with pure HTML & CSS
- **Interactive image gallery without JavaScript** — image switching is done with hidden radio buttons and CSS sibling selectors
- Amazon-style top navigation bar with logo, location, search, language, account, and cart
- Sub-navigation and promotional banner
- Breadcrumb navigation
- Product detail layout: gallery, product info, and buy box side-by-side
- Quantity dropdown, Add to Cart, Buy Now, and Add to List buttons
- "Products related to this item" grid with star ratings, prices, and badges
- "What other items do customers buy" grid
- Full Amazon-style footer with multiple link columns and back-to-top button
- **Responsive design** with breakpoints at 1100px and 720px

## Technologies Used

- HTML5 (semantic markup, SVG for the Amazon logo)
- CSS3 (Flexbox, CSS Grid, media queries)

## Project Structure

```
.
├── index.html         # Main HTML file
├── base.css           # Global reset and base styles
├── header.css         # Top navigation, search, sub-nav, breadcrumb
├── product.css        # Product page layout: gallery, info, buy box
├── related.css        # Related products grids
├── footer.css         # Site footer
├── responsive.css     # Media queries for tablet and mobile
├── hippo1.jpg         # Product images
├── hippo2.jpg
├── hippo3.jpg
├── hippo4.jpg
├── hippo5.jpg
├── hippo6.jpg
├── hippo7.jpg
└── kindel.jpg         # Kindle promo banner image
```

The CSS is split into multiple files by section, making the codebase easier to navigate and maintain.

## How to Run

No build step or server required — just open `index.html` in any modern browser:

```bash
git clone https://github.com/karam979/Amazon-mock-website-Full-Stack-project-.git
cd Amazon-mock-website-Full-Stack-project-
# Then double-click index.html, or open it from your browser
```

## What I Learned

- Structuring a real-world UI with semantic HTML
- Building complex layouts using CSS Grid and Flexbox
- Creating interactive components (image gallery) using only CSS
- Writing responsive styles with media queries
- Organizing CSS across multiple files for maintainability

## Course

Built as part of a **Full Stack Development** course — front-end module focusing on HTML & CSS fundamentals.

## Author

**karam979** — [GitHub Profile](https://github.com/karam979)
