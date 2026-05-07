# 🧬 CBC Lab Pro Dashboard

[![GitHub](https://img.shields.io/badge/GitHub-rajveer--singh--hub-blue?logo=github)](https://github.com/rajveer-singh-hub)

A modern, feature-rich **Progressive Web Application (PWA)** for managing CBC (Complete Blood Count) laboratory data with an intuitive dashboard interface.

## ✨ Features

- **📊 Professional Dashboard UI** - Clean, dark-themed interface with real-time data visualization
- **🔴 Progressive Web App (PWA)** - Install as a native app on any device
- **📱 Fully Responsive** - Works seamlessly on desktop, tablet, and mobile
- **⚡ Offline Support** - Service worker enables offline access to cached data
- **📁 Excel Integration** - Read and write Excel files directly from the browser (SheetJS)
- **⚙️ React-Powered** - Fast, dynamic UI with modern React library
- **🚀 No Build Required** - CDN-based dependencies for instant setup
- **💾 Smart Caching** - Automatic cache management for optimal performance

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **React 18** | Dynamic UI framework |
| **Babel** | JSX compilation in the browser |
| **SheetJS** | Excel file reading and writing |
| **Service Workers** | Offline functionality & caching |
| **PWA Manifest** | Installation and app metadata |

## 📦 Project Structure

```
project/
├── index.html              # Main application interface
├── manifest.json          # PWA configuration
├── service-worker.js      # Offline caching logic
└── temp_test/             # Testing directory
```

## 🚀 Getting Started

### Option 1: Direct Browser Access
1. Clone the repository:
   ```bash
   git clone https://github.com/rajveer-singh-hub/project.git
   cd project
   ```
2. Open `index.html` in your browser

### Option 2: Local Server (Recommended for PWA testing)
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```
Then visit `http://localhost:8000`

## 🌐 Install as App

1. Open the application in your browser
2. Click the **"Install"** button (or address bar prompt)
3. Use as a native application on your device

## 💡 How to Use

- **View Lab Data** - Display and organize CBC test results
- **Export to Excel** - Download data in Excel format
- **Import Data** - Load data from Excel files
- **Offline Mode** - Access cached data without internet
- **Print Reports** - Generate printable lab reports

## 🔒 Privacy & Security

- ✅ All processing happens locally in your browser
- ✅ No data sent to external servers
- ✅ Completely offline-capable
- ✅ Safe for sensitive medical data handling

## 📝 Browser Requirements

- Modern browser with ES6 support
- Service Worker support (Chrome, Firefox, Safari, Edge)
- Local storage for caching

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report issues
- Submit pull requests
- Suggest improvements

## 👨‍💻 Author

**Rajveer Singh**
- GitHub: [@rajveer-singh-hub](https://github.com/rajveer-singh-hub)
- Portfolio: [Visit GitHub Profile](https://github.com/rajveer-singh-hub)

## 📄 License

MIT License - Feel free to use this project in your own applications!

## 🙌 Support

If you found this project helpful, please consider:
- ⭐ Starring the repository
- 🐛 Reporting bugs
- 💬 Sharing feedback

---

**Made with ❤️ by [Rajveer Singh](https://github.com/rajveer-singh-hub)**
