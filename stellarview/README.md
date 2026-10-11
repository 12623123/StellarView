# StellarView

StellarView is a space-themed website that invites visitors to explore the wonders of the universe through an interactive visual experience. The project presents information about stars, planets, galaxies, black holes, nebulae, rockets, and the Solar System.

## Features

- Space-themed landing page with a visual image gallery
- Interactive image gallery powered by [Fancybox](https://fancyapps.com/fancybox/)
- Explore page with links to different space topics
- Dedicated pages covering:
  - The Solar System
  - Black holes
  - Nebulae
  - Rockets
- About page with project information
- Responsive navigation with a mobile menu
- Custom space-themed styling and local image assets
- Bulgarian-language interface content

## Technologies

- HTML5
- CSS3
- JavaScript
- Fancybox UI via jsDelivr CDN
- Optional frontend tooling configuration for Gulp, Grunt, and Bower

## Project Structure

```text
stellarview/
├── public_html/
│   ├── index.html          # Home page
│   ├── explore.html        # Space topics overview
│   ├── about.html          # About page
│   ├── solarsystem.html    # Solar System information
│   ├── black hole.html     # Black hole information
│   ├── nabula.html         # Nebula information
│   ├── rockets.html        # Rockets information
│   ├── style.css           # Website styles
│   └── imgs/               # Local images and branding assets
├── package.json
├── bower.json
├── gulpfile.js
└── Gruntfile.js
```

## Getting Started

Because StellarView is a static website, no backend server or database is required.

### Option 1: Open locally

1. Clone the repository:

   ```bash
   git clone https://github.com/12623123/StellarView.git
   ```

2. Open the project directory:

   ```bash
   cd StellarView/stellarview/public_html
   ```

3. Open `index.html` in a web browser.

### Option 2: Run with a local server

Using a local server is recommended for a more realistic development environment. For example, with Python:

```bash
cd StellarView/stellarview/public_html
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000) in your browser.

## External Resources

The home page uses Fancybox from jsDelivr for the interactive gallery. Some gallery images are loaded from external image-hosting services, so an internet connection may be required for all visual content to appear.

## Customization

- Update page content in the HTML files inside `public_html/`.
- Modify the visual design in `public_html/style.css`.
- Add or replace local images in `public_html/imgs/`.
- Add new space topics by creating an HTML page and linking it from `explore.html`.

## Browser Support

StellarView is designed for modern browsers with support for HTML5, CSS3, JavaScript, and responsive layouts.

## Credits

The website is inspired by space exploration and astronomical discoveries. Content on the site references space research and discoveries from NASA and other astronomy resources.

## License

No license has currently been specified for this project. Contact the repository owner before redistributing or reusing the project.
