# 🧮 Fraction Tutor – Visual Fraction Calculator

![Fraction Tutor Banner](https://img.shields.io/badge/Math-Education-blue?style=for-the-badge) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

**An interactive, educational fraction calculator with step-by-step visual explanations designed to help students truly understand how fractions work.**

🌐 **[Live Demo]([https://marcingwara.github.io/Fraction-Tutor/])** | 📱 **Mobile Friendly** | 🌍 **5 Languages**

---

## ✨ Features

### 🎨 **Beautiful Visual Explanations**
- **Colorful pie charts** showing fraction values
- **Step-by-step visual breakdown** of every operation
- **Animated fraction displays** with color-coded numerators and denominators
- **Child-friendly explanations** using real-world examples (pizza slices!)

### 📊 **Four Core Operations**
- ➕ **Addition** – Learn about common denominators
- ➖ **Subtraction** – See how to align different fractions
- ✖️ **Multiply** – Understand numerator × numerator
- ➗ **Division** – Master the "flip and multiply" trick

### 🌍 **Multilingual Support**
Works in **5 languages** with full translations:
- 🇵🇱 Polish (Polski)
- 🇬🇧 English
- 🇩🇪 German (Deutsch)
- 🇹🇷 Turkish (Türkçe)
- 🇷🇺 Russian (Русский)

### 📱 **Mobile & Tablet Ready**
- Optimized for iOS (iPhone & iPad)
- Responsive design for all screen sizes
- Touch-friendly interface
- Retina display support

### 🎯 **Educational Design**
- **Explains WHY**, not just HOW
- Visual step-by-step breakdowns
- Real-world analogies (pizza slices, boxes)
- No assumptions – explains every step

---

## 🚀 Quick Start

### Option 1: Use Online
Just visit the [live demo](https://marcingwara.github.io/Fraction-Tutor/) – no installation needed!

### Option 2: Run Locally
1. Download `fraction-tutor-visual.html`
2. Open it in any modern browser
3. That's it! No dependencies, no build process.

```bash
# Or clone the repo
git clone https://github.com/your-username/fraction-tutor.git
cd fraction-tutor
# Open fraction-tutor-visual.html in your browser
```

---

## 📖 How It Works

### Input Examples
- **Simple fractions**: `3/4`
- **Whole numbers**: `5`
- **Mixed numbers**: `2 1/3` (note the space!)

### Example Calculation

**Input:** `1/2 + 1/3`

**Visual Explanation:**
1. 🤔 **Why common denominator?** – Different piece sizes (1/2 vs 1/3)
2. 🔍 **Find LCM** – LCM(2, 3) = 6
3. ✨ **Convert fractions**:
   - 1/2 × 3/3 = 3/6
   - 1/3 × 2/2 = 2/6
4. 🧮 **Calculate** – 3/6 + 2/6 = 5/6

**Result:** `5/6` (also shown as mixed number if applicable)

---

## 🎓 Educational Benefits

✅ **Visual Learning** – Pie charts make abstract concepts concrete  
✅ **Step-by-Step** – No "magic jumps" in logic  
✅ **Multiple Representations** – Shows improper fractions AND mixed numbers  
✅ **Real Examples** – Uses pizza, boxes, and everyday objects  
✅ **Self-Paced** – Students can try unlimited examples  
✅ **Instant Feedback** – Results appear immediately with full explanations

---

## 🛠️ Technical Details

### Built With
- **Pure HTML/CSS/JavaScript** – No frameworks, no dependencies
- **BigInt** – Handles large numerators/denominators without precision loss
- **Canvas API** – Crisp pie chart visualizations
- **CSS Grid & Flexbox** – Responsive layouts
- **localStorage** – Remembers your language preference

### Browser Support
- ✅ Chrome 67+ (2018)
- ✅ Firefox 68+ (2019)
- ✅ Safari 14+ (iOS 14+)
- ✅ Edge 79+

**Note:** Requires BigInt support (iOS 14+ / 2020 browsers)

### Key Features
- **Single file** – Everything in one HTML file for easy distribution
- **No build process** – Just open and use
- **Offline-ready** – Works without internet after first load
- **Lightweight** – ~100KB total (including all languages)

---

## 🎨 Screenshots

### Main Calculator
![Main Interface](screenshot-main.png)

### Visual Explanation – Addition
![Addition Steps](screenshot-addition.png)

### Visual Explanation – Division
![Division Steps](screenshot-division.png)

### Mobile View
![Mobile Interface](screenshot-mobile.png)

---

## 🌟 Use Cases

### For Students
- Homework help with detailed explanations
- Visual learning for better understanding
- Practice unlimited problems
- See fractions as real objects (pizza slices)

### For Teachers
- Classroom demonstration tool
- Assign as practice resource
- Show on projector during lessons
- Multi-language for diverse classrooms

### For Parents
- Help kids with homework
- Visual aid for home tutoring
- No sign-up or accounts needed
- Works offline

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. 🐛 **Report bugs** – Open an issue
2. 💡 **Suggest features** – Share your ideas
3. 🌍 **Add translations** – Help make it accessible
4. 📝 **Improve docs** – Better explanations help everyone

### Adding a New Language

1. Add language option to `<select>`:
```html
<option value="XX">XX</option>
```

2. Add translation object to `T` in JavaScript:
```javascript
XX: {
  title: "Your translated title",
  subtitle: "Your translated subtitle",
  // ... (copy structure from existing language)
}
```

3. Test thoroughly and submit a PR!

---

## 📄 License

**MIT License** – Free to use, modify, and distribute.

See [LICENSE](LICENSE) file for full details.

---

## 👨‍💻 Author

**Marcin Gwara**

Educational math project • 2024

---

## 🙏 Acknowledgments

- Inspired by the need for better visual math education
- Thanks to all teachers providing feedback
- Built with ❤️ for students struggling with fractions

---

## 📞 Support

Found this helpful? ⭐ **Star this repo** to show your support!

Have questions? 💬 **Open an issue** – I'm here to help!

Want to contribute? 🤝 **Pull requests welcome!**

---

<div align="center">

**Made with ❤️ for math education**

[⬆ Back to Top](#-fraction-tutor--visual-fraction-calculator)

</div>
