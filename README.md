# 📚 Tamil Archaic Word Dictionary

> A single-purpose web application that solves the problem of understanding complex Tamil literary and archaic words by providing simple modern Tamil meanings and English equivalents.

<img width="938" height="817" alt="image" src="https://github.com/user-attachments/assets/140e1c5c-7b52-4a18-9f4a-c2f47877dc26" />


## 🎯 Problem Statement

Tamil literature is rich with archaic and formal words that are difficult for modern readers to understand. Students, researchers, and Tamil language enthusiasts often struggle to find simple, accessible meanings for these classical terms. Existing dictionaries are either too complex, not digitized, or lack modern Tamil explanations.

## ✨ Solution

A clean, intuitive web application that:
- Provides instant translations of archaic Tamil words to modern Tamil and English
- Includes a virtual Tamil keyboard for easy input
- Searches online databases when words aren't found locally
- Shows usage examples and etymology for better understanding
- Works on all devices with a responsive design

## 🚀 Features

### 1. **Virtual Tamil Keyboard**
- Full Tamil character support (vowels, consonants, combinations)
- No need for Tamil keyboard installation
- Works on any device or operating system

### 2. **Dual Dictionary System**
- **Local Dictionary**: 30+ pre-loaded archaic words for instant results
- **Online Search**: Automatic fallback to Wiktionary and translation APIs

### 3. **Comprehensive Word Information**
- Word type classification (verb, noun, participle, etc.)
- Simple modern Tamil meaning
- English translation
- Usage examples with context
- Etymology and word history

### 4. **User-Friendly Interface**
- Clean, modern design with gradient backgrounds
- Quick example buttons for testing
- Mobile-responsive layout
- Smooth animations and transitions

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **APIs**: 
  - Wiktionary REST API
  - MyMemory Translation API
- **Design**: Responsive CSS Grid & Flexbox
- **No Dependencies**: Pure vanilla implementation

## 📦 Installation & Setup

### Local Development

1. **Download or Clone**
```bash
# Download ZIP from GitHub and extract
# OR clone the repository:
git clone https://github.com/yourusername/tamil-archaic-dictionary.git
cd tamil-archaic-dictionary
```

2. **Open in browser**
```bash
# Simply open index.html in your browser
# Or use a local server:
python -m http.server 8000
# Then visit: http://localhost:8000
```

### GitHub Pages Deployment

1. Upload all files to your GitHub repository
2. Go to repository **Settings** → **Pages**
3. Under "Source", select **main** branch
4. Click **Save**
5. Your site will be live at: `https://yourusername.github.io/tamil-archaic-dictionary`
6. Wait 2-3 minutes for deployment

## 📖 Usage Guide

### Basic Search
1. Type or use the virtual keyboard to enter a Tamil word
2. Click "தேடு" (Search) or press Enter
3. View the meaning, examples, and etymology

### Virtual Keyboard
1. Click the keyboard icon (⌨️) to open
2. Click Tamil characters to insert them
3. Use Backspace, Clear, or Space controls
4. Close when done

### Online Search
- Toggle "Search online if not found locally" to enable/disable
- When enabled, searches external APIs automatically
- Shows source badge indicating where the result came from

## 🤖 Built with Kiro AI

This project was developed with significant assistance from Kiro AI, which accelerated development by:

- **Rapid Prototyping**: Generated initial HTML/CSS/JS structure in minutes
- **Feature Implementation**: Added Tamil keyboard and API integration quickly
- **Code Quality**: Ensured clean, maintainable code with proper structure
- **Problem Solving**: Helped debug API integration and responsive design issues
- **Documentation**: Assisted in creating comprehensive README and blog post

### Development Timeline
- **Initial Setup**: 10 minutes (with Kiro)
- **Tamil Keyboard**: 15 minutes (with Kiro)
- **API Integration**: 20 minutes (with Kiro)
- **Total Development Time**: ~1 hour (would have taken 6-8 hours manually)

## 📝 Dictionary Coverage

### Current Local Dictionary (30+ words)
- Verbs: அடியும், கண்டீர், செய்யும், வருக, படிக்கும், பேசும், etc.
- Participles: கொண்டு, செய்து, வந்து, போய்
- Common words: உண்டு, இல்லை, நினைவு

### Online Coverage
- Thousands of additional words via Wiktionary
- Translation support for modern Tamil words

## 🔮 Future Enhancements

- [ ] Voice input for Tamil words
- [ ] Save favorite words
- [ ] Word of the day feature
- [ ] Expand local dictionary to 500+ words
- [ ] Add pronunciation guide
- [ ] Tamil-to-Tamil dictionary mode
- [ ] Export word lists
- [ ] Dark mode theme

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Add More Words**: Expand the dictionary in `script.js`
2. **Improve UI/UX**: Enhance the design and user experience
3. **Add Features**: Implement items from the future enhancements list
4. **Fix Bugs**: Report and fix any issues you find

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request




---

**Built with ❤️ for Tamil language enthusiasts**

**Part of AI for Bharat - Week 1: Micro-Tools Challenge**
