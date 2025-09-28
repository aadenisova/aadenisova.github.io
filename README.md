# Alexandra Denisova - Personal Website

A minimalistic personal website built with Jekyll, supporting both English and Russian languages.

## Features

- **Bilingual Support**: English and Russian language versions
- **Minimalistic Design**: Clean, readable layout with white background and black text
- **Responsive**: Mobile-friendly design
- **Jekyll-based**: Easy to maintain and update
- **GitHub Pages Ready**: Configured for deployment on GitHub Pages

## Setup

1. **Install Ruby and Jekyll**:
   ```bash
   # Install Ruby (if not already installed)
   # On macOS with Homebrew:
   brew install ruby
   
   # Install Jekyll and Bundler
   gem install jekyll bundler
   ```

2. **Install Dependencies**:
   ```bash
   bundle install
   ```

3. **Run the Site Locally**:
   ```bash
   bundle exec jekyll serve
   ```
   
   The site will be available at `http://localhost:4000`

## Deployment

### GitHub Pages

1. Push this repository to GitHub
2. Go to repository Settings > Pages
3. Select "Deploy from a branch" and choose `main` branch
4. The site will be available at `https://yourusername.github.io/repository-name`

### Custom Domain

To use a custom domain (like `aadenisova.github.io`):
1. Add a `CNAME` file with your domain name
2. Configure your domain's DNS settings to point to GitHub Pages

## Content Management

### Adding New Content

- **Pages**: Create new `.md` files in the root directory
- **Russian Pages**: Create corresponding files in the `ru/` directory
- **Images**: Place images in `assets/images/`
- **Poetry**: Add to the poetry section in the respective language files

### Language Support

- English pages are in the root directory
- Russian pages are in the `ru/` directory
- Language switcher automatically detects current language
- All navigation and UI elements are translated

## Contact Form

The contact form uses Formspree. To activate:
1. Sign up at [Formspree.io](https://formspree.io)
2. Create a new form
3. Replace `YOUR_FORM_ID` in the contact pages with your actual form ID

## Customization

### Styling
- Main styles are in `assets/css/main.css`
- Follows minimalistic design principles
- Easy to modify colors, fonts, and layout

### Configuration
- Site settings in `_config.yml`
- Social links and metadata can be updated there

## Structure

```
├── _config.yml          # Jekyll configuration
├── _layouts/            # Page layouts
├── assets/              # CSS, images, and other assets
├── ru/                  # Russian language pages
├── index.md             # English homepage
├── about.md             # English about page
├── poetry.md            # English poetry page
├── projects.md          # English projects page
├── contact.md           # English contact page
└── README.md            # This file
```

## License

This project is open source and available under the [MIT License](LICENSE).
