#HTML Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS (Tailwind CSS), and JavaScript. This portfolio showcases projects, writing, and professional information with a sleek dark/light theme toggle.

## 🌟 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Dark/Light Mode**: Theme toggle with smooth transitions
- **Modern UI**: Clean, professional design using Tailwind CSS and custom fonts (Orbitron, Inter, Crimson Text)
- **Multiple Pages**: 
  - Home/Landing page
  - About page
  - Projects showcase
  - Writing/Publications page
- **Social Integration**: Direct links to GitHub, LinkedIn, Kaggle, and email

## 📁 Project Structure

```
Portfolio/
├── index.html           # Main landing page
├── about.html          # About me page
├── projects.html       # Projects showcase page
├── writing.html        # Writing and publications page
├── EOSD_cover.jpg      # Book cover image for writing page
├── CNAME               # Custom domain configuration for GitHub Pages
├── README.md           # Project documentation (this file)
├── LICENSE             # GNU GPL 3.0 License
└── .github/
    └── workflows/      # GitHub Actions for deployment
        ├── jekyll-gh-pages.yml
        └── static.yml
```

## 🎨 Files Description

### HTML Files

- **index.html**: The landing page featuring a hero section with profile picture, introduction, and call-to-action buttons. Uses Orbitron font for a modern tech aesthetic.

- **about.html**: Personal information presented in a notebook-style design with floating profile picture animation. Uses Crimson Text font for a literary feel.

- **projects.html**: Showcases technical projects with category badges, technology tags, and links to GitHub repositories. Features hover effects on project cards.

- **writing.html**: Displays published works with book covers, descriptions, and purchase links. Includes floating animation effects for visual appeal.

### Styling & Assets

- **Tailwind CSS**: Loaded via CDN for rapid UI development
- **Google Fonts**: 
  - Orbitron: Modern, tech-inspired font
  - Inter: Clean, readable sans-serif
  - Crimson Text: Elegant serif for literary content
- **Custom CSS**: Embedded in each HTML file for theme management and animations
- **EOSD_cover.jpg**: Book cover image (10.7 KB)

### Configuration Files

- **CNAME**: Contains custom domain configuration for GitHub Pages deployment
- **.github/workflows/**: GitHub Actions workflows for automatic deployment

## 🚀 How to Use This as Your Portfolio Template

### Prerequisites
- A GitHub account
- Basic knowledge of HTML/CSS
- (Optional) A custom domain for your portfolio

### Setup Instructions

1. **Fork or Clone This Repository**
   ```bash
   git clone https://github.com/metrinaveen08/Portfolio.git
   cd Portfolio
   ```

2. **Customize the Content**
   
   Update the following in all HTML files:
   
   - **Personal Information**:
     - Replace "Naveen Metri" with your name
     - Update the profile picture URLs (currently using GitHub avatar)
     - Change the tagline and description to match your profile
   
   - **index.html**:
     - Update hero text and introduction
     - Modify social media links in the header
     - Change the favicon URL
   
   - **about.html**:
     - Edit the personal bio and background
     - Update the profile image
     - Customize the writing style and content
   
   - **projects.html**:
     - Add your own projects
     - Update category badges, descriptions, and tech stack
     - Link to your GitHub repositories
   
   - **writing.html**:
     - Replace with your publications, blog posts, or remove if not applicable
     - Update book covers and links

3. **Update Social Links**
   
   Replace these links in all HTML files:
   - GitHub: `https://github.com/metrinaveen08`
   - LinkedIn: `https://linkedin.com/in/metri-naveen-kumar`
   - Kaggle: `https://www.kaggle.com/metrinaveen`
   - Email: `metrinaveen08@gmail.com`

4. **Customize Colors and Styling**
   
   Each HTML file has embedded CSS. Key color variables:
   - Gold/accent color: `#FFD700` (dark mode) and `#d4a500` (light mode)
   - Background: `#000000` (dark) and `#f9f7f1` (light)
   - Modify these values to match your personal brand

5. **Deploy to GitHub Pages**
   
   a. Push your changes to GitHub:
   ```bash
   git add .
   git commit -m "Customize portfolio with my information"
   git push origin main
   ```
   
   b. Enable GitHub Pages:
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select source: "Deploy from a branch"
   - Choose branch: `main` and folder: `/ (root)`
   - Save and wait for deployment

6. **Add Custom Domain (Optional)**
   
   - Update the `CNAME` file with your domain
   - Configure DNS settings with your domain provider
   - Add a CNAME record pointing to `yourusername.github.io`

7. **Test Your Site**
   
   - Visit `https://yourusername.github.io/Portfolio/`
   - Or your custom domain if configured
   - Test on multiple devices and browsers
   - Verify all links work correctly

## 🎯 Customization Tips

### Changing Fonts
Replace the Google Fonts import in the `<head>` section:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@400;700&display=swap" rel="stylesheet">
```

### Adding More Pages
1. Create a new HTML file (e.g., `contact.html`)
2. Copy the header and footer from existing pages
3. Add a navigation link in all other pages
4. Maintain consistent styling

### Modifying Theme Toggle
The theme toggle is implemented in JavaScript at the bottom of each HTML file. You can customize:
- Toggle button appearance
- Color schemes
- Transition effects

## 📜 License & Attribution

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

### Using This Template

You are free to:
- ✅ Use this template for your personal portfolio
- ✅ Modify and customize it to your needs
- ✅ Deploy it on your own domain or GitHub Pages

**Attribution Requirement:**
If you use this template, please provide credit by:
1. Adding a mention in your website footer (e.g., "Portfolio template based on [Naveen Metri's Portfolio](https://github.com/metrinaveen08/Portfolio)")
2. OR keeping a link to this repository in your README
3. OR mentioning it in your website's about/credits page

Example footer attribution:
```html
<footer>
    <p>© 2024 Your Name. Portfolio design inspired by 
    <a href="https://github.com/metrinaveen08/Portfolio">Naveen Metri</a>.</p>
</footer>
```

## 🤝 Contributing

While this is a personal portfolio, suggestions and improvements are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request with your improvements

## 📧 Contact

**Naveen Metri**
- GitHub: [@metrinaveen08](https://github.com/metrinaveen08)
- LinkedIn: [metri-naveen-kumar](https://linkedin.com/in/metri-naveen-kumar)
- Email: metrinaveen08@gmail.com
- Kaggle: [@metrinaveen](https://www.kaggle.com/metrinaveen)

## 🙏 Acknowledgments

- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Google Fonts](https://fonts.google.com/) for beautiful typography
- [Feather Icons](https://feathericons.com/) for clean SVG icons (used via inline SVG)
- GitHub Pages for free hosting

---

⭐ If you found this template helpful, please consider giving it a star on GitHub!
