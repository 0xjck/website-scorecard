# Website Scorecard

A visual comparison tool that showcases website transformations with interactive before/after reveals. Perfect for demonstrating the impact of website redesigns and improvements.

## 🌟 Features

- **Interactive Before/After Slider** - Smooth wipe-away effect to reveal transformation
- **Responsive Design** - Works perfectly on desktop and mobile devices  
- **Auto-Reveal Animation** - 3-second smooth transition with manual override
- **Detailed Metrics Comparison** - SEO, Performance, Accessibility, Design, and Technical scores
- **Expandable Details** - Click any metric for business-friendly explanations
- **Password Protection** - Simple access control for client presentations
- **Touch Support** - Full mobile gesture support

## 🚀 Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/website-scorecard.git
   cd website-scorecard
   ```

2. **Start a local server:**
   ```bash
   python3 -m http.server 8080
   ```

3. **Open in browser:**
   ```
   http://localhost:8080
   ```

4. **Login:**
   - Password: `demo123`

## 📸 Adding Your Own Screenshots

1. **Generate Screenshots:**
   - Open `capture-with-previews.html` in your browser
   - Use the screenshot generator to create `old-website.png` and `new-website.png`
   - Or replace with your own website screenshots (1200x800px recommended)

2. **Update Links:**
   - Replace `old-website.html` and `new-website.html` with your actual websites
   - Or update the links in `index.html` to point to your live sites

## 🎯 Customization

### Change Password
Edit the password in `index.html`:
```javascript
const CORRECT_PASSWORD = 'your-new-password';
```

### Update Metrics
Modify the comparison data in the detailed sections of `index.html` to reflect your actual improvements.

### Styling
The design uses Tailwind CSS classes. Customize colors, spacing, and layout by modifying the HTML classes.

## 📱 Browser Support

- ✅ Chrome/Edge (recommended)
- ✅ Firefox  
- ✅ Safari
- ✅ Mobile browsers with touch support

## 🛠️ Technical Details

- **Frontend:** HTML5, CSS3 (Tailwind), Vanilla JavaScript
- **Images:** PNG format, responsive scaling
- **Animation:** CSS transforms with JavaScript control
- **Touch:** Full gesture support for mobile devices

## 📄 File Structure

```
website-scorecard/
├── index.html              # Main scorecard application
├── old-website.html         # Example old website
├── new-website.html         # Example new website  
├── capture-with-previews.html # Screenshot generation tool
├── old-website.png          # Before screenshot
├── new-website.png          # After screenshot
└── README.md               # This file
```

## 🔒 Security Note

This tool includes basic password protection suitable for client presentations. For production use with sensitive data, implement proper authentication and HTTPS.

## 📧 Support

For questions or issues, please open a GitHub issue or contact the development team.

---

**Built for showcasing website transformations with maximum visual impact** 🎨