# Story Cubes AI 🎲✨

A modern SPA (Single Page Application) that brings the classic Rory's Story Cubes experience to your browser with AI-powered storytelling assistance. Create unique stories using random symbols, get AI suggestions, and train your own neural network to improve creativity.

🚀 Live Demo

Try it here! (Replace with your GitHub Pages URL)

🎯 Features

🎲 Interactive Story Cubes

· 9 virtual dice with 54 unique symbols from Rory's Story Cubes
· Smooth animations with prefers-reduced-motion support
· Single or batch rolling - roll individual dice or all at once
· Responsive grid that works on all devices

🤖 AI Assistant

· Brain.js neural network for intelligent story prompts
· Learning capabilities - AI trains on your stories for better suggestions
· Customizable difficulty - adjust AI complexity from 1 to 10
· Real-time prompt generation - get creative story ideas instantly

✍️ Story Creation

· Built-in editor with word/character counter
· Story rating system - rate coherence from 1 to 5 stars
· Auto-save functionality - stores stories in browser's local storage
· History panel - browse and load previous stories

🎨 Modern UI/UX

· Dark/Light theme with system preference detection
· Glass morphism design with modern CSS gradients
· Responsive layout - optimized for mobile, tablet, and desktop
· Smooth animations using CSS transitions and transforms
· Accessibility features - proper focus states and ARIA attributes

⚙️ Customization

· Theme toggle - dark, light, or system preference
· Sound effects - toggle dice rolling sounds
· Animation controls - enable/disable animations
· AI assistant - turn AI suggestions on/off
· Training mode - train the neural network with your stories

🛠️ Technologies

· Alpine.js - Lightweight JavaScript framework for reactivity
· Brain.js - Neural networks in the browser
· Font Awesome - Icon library
· Google Fonts - Inter typeface
· Modern CSS - CSS Variables, Grid, Flexbox, Custom Properties
· Vanilla JavaScript - No build tools required

📦 Installation & Usage

Option 1: Run Locally (Easiest)

1. Download the index.html file
2. Open it directly in any modern browser
3. Start creating stories!

Option 2: Deploy to GitHub Pages

1. Fork this repository
2. Enable GitHub Pages in repository settings
3. Set source to main branch
4. Your app will be live at https://your-username.github.io/repo-name/

Option 3: Self-Host

1. Clone the repository:

```bash
git clone https://github.com/your-username/story-cubes-ai.git
```

1. Serve the files using any web server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js with http-server
npx http-server -p 8000

# Using PHP
php -S localhost:8000
```

1. Open http://localhost:8000 in your browser

🎮 How to Use

Getting Started

1. Roll the dice - Click "Бросить все кубики" to generate random symbols
2. Get AI suggestions - Click "AI Подсказка" for creative story ideas
3. Write your story - Use the text editor to craft your narrative
4. Save your work - Click "Сохранить историю" to add it to your collection

Advanced Features

· Train the AI - The neural network learns from your saved stories
· Toggle themes - Switch between dark/light mode in settings
· Adjust AI difficulty - Control how creative the AI suggestions are
· Export/Import - All data is saved locally in your browser

Tips for Better Stories

· Use the dice numbers (1-9) as a suggested story structure
· Combine unexpected symbols for creative twists
· Let the AI generate multiple prompts until you find inspiration
· Rate your stories to help the AI learn your preferences

📁 Project Structure

```
story-cubes-ai/
│
├── index.html          # Complete application (HTML, CSS, JS)
├── README.md           # This documentation
├── screenshot.png      # App screenshot (optional)
└── LICENSE             # License file
```

🧠 How the AI Works

The application uses Brain.js for two main purposes:

1. Neural Network Training
   · LSTM (Long Short-Term Memory) network
   · Trained on story patterns and symbol combinations
   · Learns from user-created stories for personalized suggestions
2. Real-time Suggestions
   · Analyzes current dice symbols
   · Generates context-aware prompts
   · Adapts to user's writing style over time

🌐 Browser Compatibility

· ✅ Chrome 80+
· ✅ Firefox 75+
· ✅ Safari 13.1+
· ✅ Edge 80+
· ✅ Opera 67+

📱 Responsive Design

· Desktop (≥1200px): Full two-column layout
· Tablet (768px-1199px): Optimized single column
· Mobile (<768px): Touch-friendly controls
· Accessibility: Supports screen readers and keyboard navigation

🔧 Customization Options

Themes

```css
/* Three built-in themes */
.theme-dark     /* Default dark theme */
.theme-light    /* Light theme */
.theme-emerald  /* Emerald accent theme */
.theme-sunset   /* Sunset accent theme */
```

CSS Variables

You can customize the app by modifying CSS variables in the <style> section:

```css
:root {
    --bg: #0f1724;           /* Background color */
    --accent: #10b981;       /* Primary accent */
    --radius: 10px;          /* Border radius */
    /* ... and more */
}
```

🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Report bugs - Open an issue with detailed steps to reproduce
2. Suggest features - Share your ideas for improving the app
3. Submit pull requests - Fork the repo and submit improvements
4. Improve documentation - Help make this README even better

Development Setup

```bash
# Clone the repository
git clone https://github.com/your-username/story-cubes-ai.git

# No build process needed!
# Just edit index.html and test in browser
```

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments

· Rory's Story Cubes for the original game concept
· Alpine.js team for the lightweight framework
· Brain.js developers for making neural networks accessible
· Font Awesome for the beautiful icons
· Google Fonts for the Inter typeface

🐛 Known Issues & Limitations

· Local storage limit - Limited to ~5MB per domain
· AI training time - Can be slow with many stories
· Offline functionality - Limited to saved stories only
· Browser compatibility - Some older browsers may not support all features

📈 Future Plans

· Multiplayer mode for collaborative storytelling
· Export stories as PDF or text files
· Additional dice sets (fantasy, sci-fi, mystery)
· Voice-to-text input for stories
· Social sharing features
· Cloud sync for stories across devices
· Advanced AI models with GPT integration

💬 Support

If you need help or have questions:

1. Check the Issues page
2. Create a new issue if your problem isn't already documented
3. Email: your-email@example.com (optional)

---

<div align="center">
Made with ❤️ and JavaScript<br>
Enjoy creating amazing stories! 📖✨
</div>
