# Frontend Guide Projects

A collection of frontend projects for learning and practice, including both working versions and debug versions with intentional mistakes for learning purposes.

## Live Demos

Visit our GitHub Pages site to see all projects in action: https://YOUR_USERNAME.github.io/frontend-guide/

## Projects

### 1. Buttons Collection
- [Demo](https://YOUR_USERNAME.github.io/frontend-guide/buttons/)
- [Debug Version](https://YOUR_USERNAME.github.io/frontend-guide/debug-buttons/)
- Features: Basic, outlined, sharp, shadow, gradient, and 3D buttons

### 2. Blog Layout
- [Demo](https://YOUR_USERNAME.github.io/frontend-guide/blog/)
- [Debug Version](https://YOUR_USERNAME.github.io/frontend-guide/debug-blog/)
- Features: Responsive layout, sidebar, featured posts

### 3. Landing Page
- [Demo](https://YOUR_USERNAME.github.io/frontend-guide/landing/)
- [Debug Version](https://YOUR_USERNAME.github.io/frontend-guide/debug-landing/)
- Features: Hero section, features showcase, call-to-action

### 4. Image Gallery
- [Demo](https://YOUR_USERNAME.github.io/frontend-guide/gallery/)
- [Debug Version](https://YOUR_USERNAME.github.io/frontend-guide/debug-gallery/)
- Features: Grid layout, lightbox functionality

## Project Structure

```
frontend-guide/
├── project/                 # Working versions
│   ├── buttons-collection/
│   ├── blog-layout/
│   ├── landing-page/
│   └── image-gallery/
├── debug/                   # Debug versions with intentional mistakes
│   ├── buttons-collection/
│   ├── blog-layout/
│   ├── landing-page/
│   └── image-gallery/
└── .github/
    └── workflows/          # GitHub Actions workflow
        └── deploy.yml
```

## Setup Instructions

1. Fork this repository
2. Replace `YOUR_USERNAME` in the following files with your GitHub username:
   - `index.html`
   - `README.md`
3. Enable GitHub Pages in your repository settings:
   - Go to Settings > Pages
   - Select "GitHub Actions" as the source
4. Push your changes to the main branch
5. GitHub Actions will automatically deploy your projects

## Development

- Working versions are in the `project/` directory
- Debug versions with intentional mistakes are in the `debug/` directory
- Each project contains:
  - `index.html`: HTML structure
  - `style.css`: Styling

## Contributing

1. Fork the repository
2. Create a new branch: `git checkout -b feature-name`
3. Make your changes
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## License

MIT License - feel free to use this for learning purposes!
