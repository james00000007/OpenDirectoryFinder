# 🔍 Open Directory Finder

A modern, responsive web application for searching publicly indexed files and directories across multiple search engines. Built with vanilla HTML, CSS, and JavaScript with a beautiful dark/light mode interface.

[![GitHub stars](https://img.shields.io/github/stars/expde/OpenDirectoryFinder?style=for-the-badge&logo=github)](https://github.com/expde/OpenDirectoryFinder)
[![GitHub forks](https://img.shields.io/github/forks/expde/OpenDirectoryFinder?style=for-the-badge&logo=github)](https://github.com/expde/OpenDirectoryFinder)
[![GitHub issues](https://img.shields.io/github/issues/expde/OpenDirectoryFinder?style=for-the-badge&logo=github)](https://github.com/expde/OpenDirectoryFinder/issues)
[![GitHub license](https://img.shields.io/github/license/expde/OpenDirectoryFinder?style=for-the-badge&logo=github)](https://github.com/expde/OpenDirectoryFinder/blob/main/LICENSE)

## 🌟 Features

- **🔍 Multi-Engine Search**: Search across Google, Startpage, Searx, and FilePursuit
- **📁 Category-Based**: Organized search templates for different file types
- **🌙 Dark/Light Mode**: Beautiful, modern interface with smooth transitions
- **📱 Mobile Responsive**: Optimized for all device sizes
- **⚡ Fast & Lightweight**: Pure vanilla JavaScript, no frameworks
- **🎨 Modern UI**: Professional design with Tailwind CSS
- **💾 Persistent Settings**: Remembers your theme preference
- **🔒 Privacy-Focused**: No data collection, client-side only

## 🚀 Live Demo

**[View Live Demo](https://expde.github.io/OpenDirectoryFinder)**

## 📋 Supported Categories

| Category | File Types | Description |
|----------|------------|-------------|
| 🎬 **TV/Movies/Video** | mkv, mp4, avi, mov, mpg, wmv, divx, mpeg | Movies, TV shows, video content |
| 📚 **Books** | pdf, epub, mobi | E-books and digital publications |
| 🎵 **Music** | mp3 | Audio files and music |
| 💾 **Software** | iso, dmg, exe, zip, rar | Software, games, and archives |
| 🖼️ **Images** | jpg, png, jpeg, gif | Image files and graphics |
| 📁 **Other** | All types | General file search |

## 🔧 Supported Search Engines

- **Google** - Most comprehensive results
- **Startpage** - Privacy-focused Google proxy
- **Searx** - Open-source metasearch engine
- **FilePursuit** - Specialized file search

## 🛠️ Installation

### Option 1: Direct Download
1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No build process required.

### Option 2: GitHub Pages
1. Fork this repository
2. Go to Settings > Pages
3. Select source as "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Your site will be available at `https://yourusername.github.io/OpenDirectoryFinder`

### Option 3: Local Development
```bash
# Clone the repository
git clone https://github.com/expde/OpenDirectoryFinder.git

# Navigate to the directory
cd OpenDirectoryFinder

# Open in your browser
open index.html
# or
start index.html
# or
xdg-open index.html
```

## 📖 Usage

1. **Select Category**: Choose the type of files you're looking for
2. **Choose Engine**: Pick your preferred search engine
3. **Enter Search Term**: Type what you're looking for
4. **Click Search**: Get redirected to search results
5. **Use Keywords**: Click on popular keywords to add them to your search

### Example Searches
- `1080p movie name` - Find high-quality movies
- `pdf book title` - Search for e-books
- `mp3 artist song` - Find music files
- `iso software name` - Look for software downloads

## 🎨 Customization

### Adding New Search Engines
Edit the `ENGINES` object in the JavaScript section:

```javascript
const ENGINES = {
  google: 'https://www.google.com/search?q=',
  startpage: 'https://www.startpage.com/sp/search?q=',
  searx: 'https://searx.org/search?q=',
  filepursuit: 'https://filepursuit.io/search?q=',
  // Add your custom engine here
  custom: 'https://your-search-engine.com/search?q='
};
```

### Adding New Categories
Edit the `TEMPLATES` object:

```javascript
const TEMPLATES = {
  // ... existing templates
  documents: 'intitle:index.of +(doc|docx|txt|rtf) -inurl:(jsp|pl|php|html)',
  // Add your custom template here
};
```

### Styling
The app uses Tailwind CSS. You can customize colors, spacing, and other styles by modifying the CSS classes in the HTML file.

## 🔒 Privacy & Security

- **No Data Collection**: This tool doesn't collect or store any user data
- **Client-Side Only**: All processing happens in your browser
- **No Tracking**: No analytics or tracking scripts
- **Open Source**: Full source code is available for review

## ⚠️ Legal Notice

This tool is for educational and research purposes only. Users are responsible for:
- Complying with local laws and regulations
- Respecting copyright and intellectual property rights
- Using search results responsibly
- Not accessing unauthorized content

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### How to Contribute
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Tailwind CSS](https://tailwindcss.com/) for the beautiful styling framework
- [Lucide Icons](https://lucide.dev/) for the clean icon set
- [GitHub](https://github.com/) for hosting and collaboration
- The open-source community for inspiration and support

## 📞 Support

If you have any questions or need help, please:
- Open an [issue](https://github.com/expde/OpenDirectoryFinder/issues)
- Contact [@expde](https://github.com/expde)

## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=expde/OpenDirectoryFinder&type=Date)](https://star-history.com/#expde/OpenDirectoryFinder&Date)

---

<div align="center">
  <p>Made with ❤️ by <a href="https://github.com/expde">@expde</a></p>
  <p>⭐ Star this repository if you found it helpful!</p>
</div>
