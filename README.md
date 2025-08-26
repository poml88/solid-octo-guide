# FLwatch Website

A multilingual Jekyll website for the FLwatch iOS and watchOS app, designed to be hosted on GitHub Pages.

## 🚀 Quick Setup

1. **Fork this repository** to your GitHub account
1. **Update configuration** in `_config.yml`:
- Replace `yourusername` in the `url` field with your GitHub username
- Update `app.github_url` with your actual repository URL
1. **Add your app icon** as `assets/images/app-icon.png` (120x120px recommended)
1. **Enable GitHub Pages** in your repository settings
1. **Your site will be live** at `https://yourusername.github.io/repository-name`

## 📁 Project Structure

```
├── _config.yml              # Jekyll configuration
├── _data/
│   └── translations.yml     # All translations for 6 languages
├── _layouts/
│   └── default.html         # Main layout template
├── assets/
│   └── images/
│       └── app-icon.png     # Your app icon (add this file)
├── index.md                 # English homepage
├── de/
│   └── index.md            # German homepage
├── fr/
│   └── index.md            # French homepage
├── es/
│   └── index.md            # Spanish homepage
├── ja/
│   └── index.md            # Japanese homepage
├── zh/
│   └── index.md            # Chinese homepage
├── Gemfile                 # Ruby dependencies
└── README.md               # This file
```

## 🌍 Supported Languages

- 🇺🇸 English (default)
- 🇩🇪 German (Deutsch)
- 🇫🇷 French (Français)
- 🇪🇸 Spanish (Español)
- 🇯🇵 Japanese (日本語)
- 🇨🇳 Chinese Simplified (中文)

## 🎨 Features

- **Responsive Design**: Works perfectly on desktop and mobile
- **Modern UI**: Glassmorphism design with smooth animations
- **App Store Integration**: Direct download button
- **GitHub Integration**: Link to your repository
- **SEO Optimized**: Built-in SEO tags and sitemap
- **Fast Loading**: Optimized for performance

## 🛠️ Customization

### Updating App Information

Edit `_config.yml`:

```yaml
app:
  name: "FLwatch"
  subtitle: "Glucose Sensor Graph"
  app_store_url: "https://apps.apple.com/us/app/flwatch-glukose-sensor-graph/id6670172928"
  github_url: "https://github.com/yourusername/flwatch"
  icon: "/assets/images/app-icon.png"
```

### Adding/Modifying Translations

Edit `_data/translations.yml` to modify existing translations or add new languages.

### Styling

The CSS is embedded in `_layouts/default.html` for simplicity. You can:

- Move it to a separate file in `assets/css/`
- Customize colors, fonts, and layout
- Add new components

## 📱 App Icon Requirements

Place your app icon at `assets/images/app-icon.png`:

- **Size**: 120x120px minimum (higher resolution recommended)
- **Format**: PNG with transparency support
- **Style**: Should match your actual app icon

## 🚀 Deployment

### GitHub Pages (Recommended)

1. Push your code to GitHub
1. Go to repository Settings → Pages
1. Select source: “Deploy from a branch”
1. Select branch: `main` or `master`
1. Your site will be available at `https://yourusername.github.io/repository-name`

### Local Development

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# Visit http://localhost:4000
```

## 📧 Support

If you need help with setup or customization:

- Check the [Jekyll documentation](https://jekyllrb.com/docs/)
- Review [GitHub Pages documentation](https://docs.github.com/en/pages)
- Open an issue in this repository

## 📄 License

This website template is open source. Feel free to use it for your own app website.

-----

Built with ❤️ for the FLwatch app community
