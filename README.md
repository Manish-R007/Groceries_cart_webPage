✨ Key Features:

    Header:

        Logo on the left

        Navigation links (Home, About, Contact)

        Search bar

        Buttons for Sign Up and Login

    Main Content:

        Title: “Shop here”

        Three horizontal, scrollable rows (overflow-x-auto) of product cards

        Each card includes an image, discount info, and a call-to-action "Grab Now"

        Smooth hover transitions using Tailwind’s hover:translate-y, hover:shadow, and transition-transform

    Footer:

        Simple centered copyright

The structure is modular and responsive by design, thanks to Tailwind’s utility-first approach. The layout supports a horizontal scroll UX suitable for mobile and desktop shopping experiences.
🧱 Tech Stack
Layer	Tool / Framework	Purpose
Markup Language	HTML5	Page structure
CSS Framework	Tailwind CSS	Utility-first styling and responsive layout
Image Sources	Pixabay & Bing	Free high-quality product images
Font & Icons	Tailwind defaults	Simple fonts and hover animations
Deployment (optional)	GitHub Pages / Netlify	To publish the static site
📁 Project Structure (Recommended)

ecommerce-landing-page/
├── index.html         # Main HTML file
├── output.css         # Tailwind CSS file (compiled)
├── tailwind.config.js # Tailwind config (if using PostCSS)
├── README.md          # Project description & usage
└── package.json       # If using npm build for Tailwind

📌 Highlights

    Uses overflow-x-auto with flex and w-max to create horizontally scrollable product rows

    Button and card animations are powered by Tailwind’s GPU transforms and transitions

    Clean separation of header, main, and footer for maintainability

    Consistent styling using classes like rounded-xl, bg-amber-*, text-amber-*, etc.

