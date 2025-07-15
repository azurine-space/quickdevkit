# JSON Formatter & Validator Tool

🚀 **A powerful, multilingual JSON formatting and validation tool with comment support**

[**Live Demo →**](https://your-username.github.io/json-tools)

## ✨ Features

### 🔧 **Core Functionality**
- **Real-time JSON validation** with precise error highlighting
- **Smart formatting** with proper indentation
- **Comment support** - Both `// single line` and `/* multi-line */` comments
- **One-click copy** and minify functions
- **Sample data loading** for quick testing

### 🌍 **Multilingual Support**
- **Auto-detection** based on browser language, timezone, and locale
- **4 Languages**: English, 한국어, 日本語, 中文
- **Localized samples** and error messages
- **Regional formatting** detection

### 🎨 **Modern UI/UX**
- **Dark/Light mode** toggle
- **Responsive design** for mobile and desktop
- **CodeMirror editor** with syntax highlighting
- **Professional interface** with smooth transitions

### 🧠 **Smart Detection**
- **Browser language** preferences
- **Timezone-based** region detection  
- **Currency and formatting** analysis
- **Intelligent fallbacks** to English

## 🚀 Quick Start

1. **Visit the tool**: [JSON Formatter](https://your-username.github.io/json-tools)
2. **Paste your JSON** in the left editor
3. **Add comments** if needed using `//` or `/* */`
4. **See formatted output** instantly in the right panel
5. **Copy the result** with one click

## 💡 Usage Examples

### Basic JSON Formatting
```json
{"name":"John","age":30,"city":"New York"}
```
↓ **Formats to:**
```json
{
  "name": "John",
  "age": 30,
  "city": "New York"
}
```

### JSON with Comments
```json
{
  // User information
  "name": "John Doe",
  "age": 30,
  
  /* Address details
     Multi-line comment support */
  "address": {
    "city": "New York", // City name
    "zip": "10001"     // ZIP code
  }
}
```

## 🌐 Supported Languages

| Language | Code | Auto-Detection |
|----------|------|----------------|
| English | `en` | Default fallback |
| 한국어 | `ko` | `ko-*`, Asia/Seoul timezone, KRW currency |
| 日本語 | `ja` | `ja-*`, Asia/Tokyo timezone, JPY currency |
| 中文 | `zh-CN` | `zh-*`, Asia/Shanghai timezone, CNY currency |

## 🛠️ Technical Features

- **CodeMirror 5** for professional code editing
- **Automatic language detection** using multiple methods:
  - `navigator.language` and `navigator.languages`
  - `Intl.DateTimeFormat` locale detection
  - Timezone-based region analysis
  - Currency and number formatting patterns
- **LocalStorage** for language preference persistence
- **Error-safe fallbacks** for all detection methods

## 📱 Browser Support

- ✅ Chrome/Chromium (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🔮 Upcoming Features

- 📄 **Markdown formatter**
- 🔐 **Base64 encoder/decoder**
- 🌈 **HTML formatter**
- 🔗 **URL encoder/decoder**
- 🔤 **Unicode converter**

## 🤝 Contributing

Found a bug or have a feature request? 

1. **Open an issue** with details
2. **Fork the repository**
3. **Submit a pull request**

## 📄 License

MIT License - feel free to use this tool for any purpose!

## 🌟 Show Your Support

If this tool helped you, please ⭐ **star this repository** and share it with other developers!

---

**Made with ❤️ for developers worldwide**

[Report Bug](https://github.com/your-username/json-tools/issues) • [Request Feature](https://github.com/your-username/json-tools/issues) • [View Source](https://github.com/your-username/json-tools)
