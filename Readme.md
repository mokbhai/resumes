# Professional Resume Builder

A modern, responsive resume builder that generates a clean and professional-looking resume. Built with HTML, CSS, and vanilla JavaScript, this project offers multiple themes and color schemes while maintaining a professional appearance.

## 📺 Demo Video

Watch our demo video to see the Resume Builder in action:

[![Resume Preview](https://img.youtube.com/vi/o6feTekgDAc/0.jpg)](https://youtu.be/o6feTekgDAc)

## 🌟 Features

- **Multiple Themes**: Switch between different professionally designed layouts
- **Color Customization**: Change color schemes on the fly
- **Responsive Design**: Looks great on all devices
- **Print Friendly**: Optimized for PDF generation and printing
- **JSON-Driven**: Easy content updates through a JSON file
- **Modern Icons**: Uses SVG icons for crisp display at any size
- **No Dependencies**: Pure HTML, CSS, and JavaScript
- **Clean UI**: Professional and minimal interface

## 🚀 Quick Start

1. Clone the repository:

```bash
git clone https://github.com/mokbhai/resumes.git
```

2. Update your information in `src/data/resume.json`

3. Open `src/index.html` in a browser or serve using a local server:

```bash
# Using Python
python -m http.server 3000

# Using Node.js
npx serve src
```

## 📁 Project Structure

```
├── index.html          # Main HTML file
├── common.css          # First style file
├── data/
│   └── resume.json     # Your resume content
└── styles/
    ├── styles.css      # Primary theme
    └── styles2.css     # Alternative theme
```

## 🎨 Customization

### Changing Content

Edit `src/data/resume.json` to update your resume information. The structure includes:

- Basic Information
- Work Experience
- Education
- Projects
- Skills
- Achievements

### Changing Themes

Use the "Change Style" button to switch between available themes. Each theme maintains professional aesthetics while offering distinct visual styles.

### Color Schemes

Click the "Change Color" button to cycle through different color schemes. Colors are managed through CSS variables for consistent styling.

## 📱 Responsive Design

The resume is fully responsive and adapts to:

- Desktop screens
- Tablets
- Mobile devices
- Print/PDF format

## 🖨️ Printing

To generate a PDF:

1. Click the "Download PDF" button
2. Use your browser's print dialog
3. Select "Save as PDF"

The layout is optimized for both A4 and Letter paper sizes.

## 💻 Technical Details

- Uses CSS Grid for modern layouts
- CSS Variables for theming
- SVG icons for scalability
- Semantic HTML structure
- Mobile-first approach
- Print-specific styles

## 🤝 Contributors

We appreciate the contributions from the following individuals:

<a href="https://github.com/mokbhai">
  <img src="https://avatars.githubusercontent.com/mokbhai" alt="Mokshit Jain" width="50" height="50" style="border-radius: 50%;" />
</a>
<!-- Add more contributors as needed -->

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Icons from [Bootstrap Icons](https://icons.getbootstrap.com/)
- Color schemes inspired by modern design trends
- Font families from system defaults for optimal loading

## 📧 Contact

Your Name - [mokshitjain18@gmail.com](mailto:mokshitjain18@gmail.com)

Project Link: [https://github.com/mokbhai/resumes](https://github.com/mokbhai/resumes)
