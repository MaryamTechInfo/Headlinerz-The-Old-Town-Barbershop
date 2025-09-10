# Headlinerz - The Old Town Barbershop

A modern, responsive website for Headlinerz barbershop located in the heart of Old Town. This project showcases the barbershop's services, team, and booking information with a clean, professional design.

## Project Overview

Headlinerz-The-Old-Town-Barbershop is a static website built with HTML, CSS (using Tailwind CSS), and JavaScript. The site features:

- Responsive design that works on all devices
- Service listings and pricing
- Team member profiles
- Contact information and location details
- Modern barbershop aesthetic

## File Structure

```
├── README.md
├── LICENSE
├── .gitignore
├── index.html
├── styles.css
├── scripts.js
├── robots.txt
├── sitemap.xml
├── favicon.ico
├── site.webmanifest
├── og.jpg
├── data/
│   ├── business.json
│   └── sources.md
├── docs/
│   ├── assumptions.md
│   └── owner-intro.md
└── .github/
    └── workflows/
        └── pages.yml
```

## Editing Instructions

### Making Changes
1. Edit files directly in the GitHub web interface or clone the repository locally
2. Business information can be updated in `/data/business.json`
3. Content assumptions and notes are documented in `/docs/assumptions.md`
4. Owner introduction content is in `/docs/owner-intro.md`

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/MaryamTechInfo/Headlinerz-The-Old-Town-Barbershop.git
   ```
2. Open `index.html` in your browser to view the site
3. Make changes to HTML, CSS, or JavaScript files as needed
4. Test responsiveness using browser developer tools

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the main branch.

### GitHub Pages Setup
1. Go to repository Settings → Pages
2. Source should be set to "Deploy from a branch"
3. Branch should be set to "main" with "/ (root)" folder
4. The site will be available at: `https://maryamtechinfo.github.io/Headlinerz-The-Old-Town-Barbershop/`

### Custom Domain (Optional)
To use a custom domain:
1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Enable HTTPS in GitHub Pages settings

## Technologies Used

- **HTML5**: Semantic markup structure
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **JavaScript**: Interactive functionality
- **GitHub Pages**: Static site hosting
- **GitHub Actions**: Automated deployment

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions about this project, please contact the repository owner through GitHub.
