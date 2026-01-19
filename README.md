# Personal Website

A modern, stylish personal website built with HTML, CSS, and JavaScript.

## Features

- 🎨 Modern gradient design with smooth animations
- 📱 Fully responsive layout
- ⚡ Fast and lightweight
- 🎯 Smooth scrolling navigation
- 🌟 Interactive elements and hover effects

## Local Development

### Option 1: Python HTTP Server (Recommended - No Installation Required)

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

### Option 2: Jekyll (For GitHub Pages)

If you want to use Jekyll for GitHub Pages compatibility:

1. Install Ruby and dependencies:
   ```bash
   sudo apt install ruby-rubygems ruby-dev build-essential libffi-dev libyaml-dev zlib1g-dev libssl-dev
   ```

2. Install Jekyll and Bundler:
   ```bash
   gem install bundler jekyll
   ```

3. Install dependencies:
   ```bash
   bundle install
   ```

4. Start Jekyll server:
   ```bash
   bundle exec jekyll serve
   ```

   Then open http://localhost:4000 in your browser.

## Deployment

This site can be deployed to:
- **GitHub Pages** - Just push to your repository
- **Netlify** - Drag and drop the folder
- **Vercel** - Connect your GitHub repository
- Any static hosting service

## Customization

- Update personal information in `index.html`
- Modify colors in `assets/css/style.css` (CSS variables at the top)
- Add your projects/publications in the Projects section
- Update social media links in the About section

## File Structure

```
.
├── index.html          # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css   # All styles and animations
│   ├── js/
│   │   └── main.js     # Interactive functionality
│   └── img/
│       └── portrait.jpeg # Your portrait image
├── _config.yml         # Jekyll configuration
└── README.md           # This file
```

## License

Personal use - All rights reserved.
