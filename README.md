# Age Calculator Tool

A beautiful, responsive, and feature-rich Age Calculator built with HTML, Tailwind CSS, and JavaScript. Calculate your exact age or the time difference between any two dates with precision down to seconds.

🔗 **Live Demo**: [https://webdevservices.in/age-calculator-tool/](https://webdevservices.in/age-calculator-tool/)

![Age Calculator Screenshot](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

- **Precise Age Calculation**: Calculate age in years, months, weeks, days, hours, minutes, and seconds
- **Dual Date Selection**: Choose any two dates to calculate the time difference
- **Beautiful UI**: Modern, responsive design using Tailwind CSS
- **Smooth Animations**: Typing effect for results display with fade-in animations
- **Local Storage**: Automatically saves your last calculation for convenience
- **Input Validation**: Smart validation with user-friendly error messages using SweetAlert2
- **Mobile Responsive**: Works perfectly on all devices
- **SEO Optimized**: Proper meta tags and semantic HTML structure

## 🚀 Quick Start

### Option 1: Direct Use

Simply download `index.html` and open it in any modern web browser. No installation or build process required!

### Option 2: Clone the Repository

```bash
git clone https://github.com/MrPawanMall/Age-Calculator.git
cd Age-Calculator
```

Then open `index.html` in your browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Visit `http://localhost:8000` in your browser.

## 📖 How to Use

### Step 1: Enter Your Date of Birth

Select your **Date of Birth** using the date picker. This will be the starting point for calculating your age.

### Step 2: Select the Reference Date

Choose the **reference date** for which you want to know your age. This could be:

- Today's date (to know your current age)
- A future date (to know how old you'll be)
- A past date (to know how old you were)

### Step 3: Calculate Your Age

Click the **"Calculate"** button to instantly get the result, displayed in:

- Years, months, and days
- Total months
- Total weeks
- Total days
- Total hours
- Total minutes
- Total seconds

### Step 4: Start Again

Click the **"Start Again"** button to:

- Clear the results
- Reset the date fields to today's date
- Remove saved data from local storage

## 🎯 Use Cases

- **Personal**: Calculate your exact age for official documents
- **Events**: Find out how many days until your birthday or anniversary
- **Historical**: Calculate time elapsed since historical events
- **Professional**: Age verification for legal or medical purposes
- **Educational**: Teaching time calculations and date arithmetic

## 🛠️ Technical Details

### Technologies Used

- **HTML5**: Semantic markup structure
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **JavaScript (ES6+)**: Modern vanilla JavaScript
- **SweetAlert2**: Beautiful alert/modal library
- **LocalStorage API**: Client-side data persistence

### Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

### Key Features Implementation

#### Age Calculation System

The calculator uses the **Gregorian calendar** system (most common in Western countries):

- Age increases by one year on each birthday
- Months are calculated using an average of 30.44 days
- Handles leap years and varying month lengths

#### Cultural Considerations

While this tool uses the standard Western age system, it's worth noting that age calculation varies across cultures:

- **Chinese Age System**: People are born at age 1, and age increases on Chinese New Year
- **Korean Age System**: Similar to Chinese, with variations
- This calculator provides the internationally recognized standard

#### Data Persistence

- Automatically saves the last calculation to `localStorage`
- Persists across page refreshes
- Can be cleared with the "Start Again" button

## 📁 Project Structure

```
Age-Calculator/
│
├── index.html          # Main application file (self-contained)
├── README.md           # Project documentation
└── LICENSE             # MIT License
```

## 🎨 Customization

### Changing Colors

The project uses Tailwind CSS. You can customize colors by modifying the class names in `index.html`:

```html
<!-- Primary button color -->
<button class="bg-blue-500 hover:bg-blue-600">Calculate</button>

<!-- Result background -->
<div class="bg-blue-50 text-blue-700">Result content here</div>
```

### Modifying Animations

Adjust the typing effect speed by changing the timeout value:

```javascript
setTimeout(typeWriter, 500); // Change 500 to your preferred milliseconds
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a new branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Ideas for Contributions

- Add more language support (i18n)
- Implement different age calculation systems (Chinese, Korean, etc.)
- Add export functionality (PDF, image)
- Create a dark mode toggle
- Add more date format options

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Web Dev Services & News**

- Website: [https://webdevservices.in](https://webdevservices.in)
- Demo: [Age Calculator Tool](https://webdevservices.in/age-calculator-tool/)

## 🙏 Acknowledgments

- [Tailwind CSS](https://tailwindcss.com/) for the amazing utility-first CSS framework
- [SweetAlert2](https://sweetalert2.github.io/) for beautiful alert modals
- The open-source community for inspiration and support

## 📊 Stats

![GitHub stars](https://img.shields.io/github/stars/MrPawanMall/Age-Calculator?style=social)
![GitHub forks](https://img.shields.io/github/forks/MrPawanMall/Age-Calculator?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/MrPawanMall/Age-Calculator?style=social)

## 🐛 Known Issues

None at the moment! If you find a bug, please [open an issue](https://github.com/MrPawanMall/Age-Calculator/issues).

## 📮 Support

If you have any questions or need help, feel free to:

- Open an issue on GitHub
- Visit our website at [webdevservices.in](https://webdevservices.in)

---

**Made with ❤️ by Web Dev Services & News**

⭐ Star this repository if you find it helpful!
