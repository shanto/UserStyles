# 🎨 Shaan's UserStyles

A curated collection of custom CSS styles to enhance my daily browsing experience. These UserStyles improve the visual appearance and usability of various websites.

## 📋 Table of Contents

- [What are UserStyles?](#what-are-userstyles)
- [Installation](#installation)
- [Available Styles](#available-styles)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## 🤔 What are UserStyles?

UserStyles are custom CSS stylesheets that modify the appearance of websites. They allow you to personalize your browsing experience by changing colors, fonts, layouts, and other visual elements of web pages.

## 🚀 Installation

To use these UserStyles, you'll need a browser extension that supports custom CSS:

### Recommended Extensions:
- **Stylus** (Recommended) - [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) | [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)
- **Stylish** - [Chrome](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe) | [Firefox](https://addons.mozilla.org/en-US/firefox/addon/stylish/)

### Installation Steps:
1. Install one of the browser extensions above
2. Click on the raw CSS file link for the style you want
3. The extension should automatically detect the UserStyle and prompt you to install it
4. Alternatively, copy the CSS content and create a new style manually in your extension

## 📚 Available Styles

### 🌙 AutoHotkey Docs: Dark
**File:** [`autohotkey.com-docs.css`](src/autohotkey.com-docs.css)

- **Description:** Forces dark mode in the AutoHotkey documentation section
- **Target Site:** autohotkey.com/docs/*
- **Version:** 1.0.0
- **Features:**
  - Automatically applies dark theme to AutoHotkey documentation
  - Respects system dark mode preference
  - Improves readability during night-time coding sessions

**Install:** [📥 Direct Install](https://raw.githubusercontent.com/shanto/UserStyles/main/src/autohotkey.com-docs.css)

## 💡 Usage

1. **Browse to the target website** - Each UserStyle is designed for specific websites
2. **Automatic activation** - Styles will automatically apply when you visit the target sites
3. **Toggle on/off** - Use your UserStyle extension to enable/disable styles as needed
4. **Customize** - Feel free to modify the styles to suit your preferences

## 🛠️ Development

### File Structure
```
UserStyles/
├── README.md
└── src/
    └── autohotkey.com-docs.css
```

### Adding New Styles
1. Create a new `.css` file in the `src/` directory
2. Include proper UserStyle metadata headers
3. Test thoroughly on the target website
4. Update this README with the new style information

### UserStyle Metadata Format
```css
/* ==UserStyle==
@name           Style Name
@namespace      github.com/shanto
@version        1.0.0
@description    Brief description of what the style does
@author         Shaan
@homepageURL    https://github.com/shanto/UserStyles
@updateURL      https://raw.githubusercontent.com/shanto/UserStyles/main/src/filename.css
==/UserStyle== */
```

## 🤝 Contributing

Found a bug or have a suggestion? Feel free to:
- Open an issue for bug reports or feature requests
- Submit a pull request with improvements
- Share your own UserStyles that might benefit others

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Useful Links

- [Stylus Documentation](https://github.com/openstyles/stylus/wiki)
- [UserCSS Format](https://github.com/openstyles/stylus/wiki/UserCSS)
- [CSS Selectors Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)

---

⭐ **Star this repository** if you find these styles useful!

*Last updated: June 2025*
