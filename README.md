# Yahya Izadi's Blog

A personal blog built with [Quarto](https://quarto.org), featuring articles about programming, data science, and technology.

## 🚀 Features

- **Modern Design**: Built with Quarto's powerful web publishing system
- **Responsive Layout**: Works seamlessly on desktop and mobile devices
- **Dark/Light Theme**: Automatic theme switching with Cosmo (light) and Superhero (dark) themes
- **RSS Feed**: Subscribe to get updates on new posts
- **Category Filtering**: Browse posts by topic
- **Custom Extension**: Uses Purple Fox extension for enhanced styling

## 📝 Recent Posts

- **Getting Started with Python**: A beginner's guide to Python programming

## 🛠️ Technologies

- [Quarto](https://quarto.org) - Open-source scientific and technical publishing system
- [Bootstrap](https://getbootstrap.com) - For responsive design
- Custom SCSS styling
- Obsidian-style callouts

## 🏗️ Project Structure

```
.
├── _quarto.yml           # Quarto configuration
├── index.qmd            # Home page with post listings
├── about.qmd            # About page
├── posts/               # Blog posts directory
│   ├── _metadata.yml    # Posts metadata
│   └── python-basics/   # Individual post folders
├── _extensions/         # Quarto extensions
└── _site/              # Generated site (not in git)
```

## 🚦 Getting Started

### Prerequisites

- [Quarto](https://quarto.org/docs/get-started/) installed on your system
- A text editor or IDE

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd "blog test"
   ```

2. Preview the site locally:
   ```bash
   quarto preview
   ```

3. Render the site:
   ```bash
   quarto render
   ```

## 📄 Creating New Posts

1. Create a new folder under `posts/`:
   ```bash
   mkdir posts/my-new-post
   ```

2. Add an `index.qmd` file with front matter:
   ```yaml
   ---
   title: "Your Post Title"
   author: "Yahya Izadi"
   date: "2025-11-18"
   categories: [category1, category2]
   ---
   ```

3. Write your content using Markdown or Quarto features

4. Preview or render to see your changes

## 🎨 Customization

- Edit `_quarto.yml` to change site settings, theme, or navigation
- Modify `styles.css` for custom styling
- Update `about.qmd` to personalize your about page

## 📦 Deployment

The site can be deployed to:
- [GitHub Pages](https://quarto.org/docs/publishing/github-pages.html)
- [Netlify](https://quarto.org/docs/publishing/netlify.html)
- [Quarto Pub](https://quarto.org/docs/publishing/quarto-pub.html)
- Any static site hosting service

## 🔗 Connect

- [LinkedIn](https://www.linkedin.com/in/yahya-izadi/)
- [GitHub](https://github.com/yahaiz)

## 📝 License

This project is open source and available for personal and educational use.

## 🙏 Acknowledgments

- Built with [Quarto](https://quarto.org)
- Purple Fox extension for enhanced styling
- Bootstrap for responsive design

---

**Note**: Remember to update `site-url` in `_quarto.yml` before deploying to production for proper RSS feed functionality.
