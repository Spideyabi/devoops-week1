# GitHub Guides Blog

A well-organized blog application for GitHub guides and tutorials, designed to help developers learn and master GitHub.

## 📁 Project Structure

```
devoops-week1/
├── assets/
│   ├── css/
│   │   ├── style.css      # Main stylesheet
│   │   └── guide.css      # Guide page styles
│   ├── js/
│   │   └── main.js        # JavaScript functionality
│   └── images/            # Image assets
├── guides/
│   ├── getting-started.html    # Getting started guide
│   ├── github-actions.html     # GitHub Actions guide
│   └── collaboration.html      # Collaboration guide
├── templates/
│   └── guide-template.html     # Template for new guides
├── index.html                  # Main homepage
├── .gitignore                  # Git ignore file
└── README.md                   # Project documentation
```

## 🚀 Features

- **Clean, Organized Structure**: Separated assets, guides, and templates for easy maintenance
- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Multiple Guides**: Pre-built guides covering:
  - Getting Started with GitHub
  - GitHub Actions
  - Collaboration Best Practices
- **Reusable Templates**: Guide template for creating new content
- **Modern UI**: GitHub-inspired design with smooth interactions
- **Smooth Navigation**: Scroll animations and active section highlighting

## 🛠️ Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Spideyabi/devoops-week1.git
   cd devoops-week1
   ```

2. Open `index.html` in your web browser to view the blog

3. To create a new guide:
   - Copy `templates/guide-template.html` to the `guides/` folder
   - Rename it appropriately
   - Fill in your content
   - Update `index.html` to link to the new guide

## 📝 Adding New Guides

1. Use the template in `templates/guide-template.html`
2. Add your content in the guide body section
3. Update the title, date, and reading time
4. Link to it from the main page

## 🎨 Customization

- **Colors**: Modify the CSS variables in `assets/css/style.css`
- **Layout**: Adjust the grid and flexbox properties for different layouts
- **Content**: All text content is in HTML files for easy editing

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Feel free to fork this project and customize it for your own needs!
