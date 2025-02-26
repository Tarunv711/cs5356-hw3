# Personal Portfolio Website

A responsive personal portfolio website built for CS5356 HW3.

## Features

- Responsive design that works on all screen sizes
- Modern, clean interface with smooth animations
- Semantic HTML5 structure
- Flexbox and Grid layout
- Interactive elements
- Real-time weather data from an API
- Modern CSS features like backdrop-filter

## Assignment Requirements Met

1. ✅ Created GitHub repository
2. ✅ Enabled GitHub Pages
3. ✅ Website contains picture, bio, and more
4. ✅ Used semantic HTML tags (`<section>`, `<nav>`, `<header>`, etc.)
5. ✅ Used CSS Grid and Flexbox for layout
6. ✅ Added an HTML element not discussed in class: `<details>` and `<summary>`
7. ✅ Added a CSS property not discussed in class: `backdrop-filter`
8. ✅ Fetched data from an API (Open-Meteo weather API)

## How to Set Up GitHub Pages

1. Create a new repository on GitHub named `cs5356-hw3` or similar
2. Initialize with a README file
3. Clone the repository to your local machine:
   ```
   git clone https://github.com/YOUR-USERNAME/cs5356-hw3.git
   ```
4. Copy all files from this project into the repository directory
5. Add, commit, and push the changes:
   ```
   git add .
   git commit -m "Add personal website files"
   git push origin main
   ```
6. Go to your repository on GitHub → Settings → Pages
7. Under "Source", select "main" branch
8. To bypass Jekyll processing, create a file named `.nojekyll` in the root directory:
   ```
   touch .nojekyll
   git add .nojekyll
   git commit -m "Add nojekyll file to bypass Jekyll processing"
   git push origin main
   ```
9. Your site will be published at `https://YOUR-USERNAME.github.io/cs5356-hw3/`

## Local Development

To view the website locally:

1. Navigate to the project directory
2. Start a local server:
   ```
   python -m http.server 8000
   ```
3. Open your browser and go to `http://localhost:8000`

## Credits

- Weather data provided by [Open-Meteo API](https://open-meteo.com/)
- Icons from [Font Awesome](https://fontawesome.com/) 