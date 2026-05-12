# life-app-os
A personal, zero-dependency dashboard designed to track, balance, and optimize five core life systems: **Health**, **Research &amp; Career**, **Grades**, **Spirituality**, and **Family &amp; Friends**.  
Built for a college student navigating a rigorous academic load, research commitments, and community leadership, this dashboard brings daily habits, weekly goals, and reflective logging into one beautiful, interactive interface.

🔗 **[Live Demo](https://nicholasmckayh29-art.github.io/life-app-os/)**

## ✨ Features
- 🎯 **5-System Navigation**: Tabbed interface with dynamic color theming per life domain
- 📊 **Smart Metrics**: Track sleep, lab hours, GPA, prayer, and community check-ins at a glance
- ✅ **Habit Tracking**: Daily checklist with smooth animations, progress bars, and auto-reset per week
- 📝 **Daily Logging**: Built-in textarea for quick notes, reflections, or progress dumps
- 🤖 **AI Integration**: One-click prompts to open tailored Claude conversations for each system
- 📱 **Fully Responsive**: Optimized for desktop, tablet, and mobile
- 🎨 **Zero Build Step**: Pure HTML/CSS/JS. Just open the file or deploy to GitHub Pages.

## 🛠️ How It Works
| File | Purpose |
|------|---------|
| `index.html` | Single-file app containing structure, styles, and logic |
| `README.md` | This file. Project documentation & setup guide |
| `LICENSE` | MIT License for open sharing |

### 🔄 How Weekly Reset Works
Habit keys are prefixed with the current ISO week number (`YYYY-wX`). When a new week starts, checkboxes automatically reset to unchecked while preserving your logs and AI prompts.

### 📦 Local Development
1. Clone the repository
2. Open `index.html` in any browser
3. No server, Node.js, or bundler required

## 🌐 Deploy to GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select `Deploy from a branch` → `main` → `/ (root)`
4. Click **Save**. Your dashboard will be live at `https://yourusername.github.io/nich-life-os/`

## 📚 Tech Stack
- **HTML5** / **CSS3** / **Vanilla JavaScript**
- [Tabler Icons](https://tabler-icons.io) (CDN)
- [Inter Font](https://fonts.google.com/specimen/Inter) (CDN)
- CSS Variables, Grid, Flexbox, `@keyframes` animations
- GitHub Pages hosting

## 💡 Customization Tips
- **Add a new system**: Duplicate an object in the `SYSTEMS` array in `script.js`
- **Change colors**: Update the `color`, `bg`, and `textColor` properties per system
- **Track different metrics**: Edit the `metrics` array inside any system object
- **Connect AI elsewhere**: Replace `sendPrompt()` with your preferred LLM API or web UI

## 📝 License
This project is licensed under the [MIT License](LICENSE) — feel free to fork, modify, and adapt it for your own life operating system.

---
*Built for focus, clarity, and sustainable growth. 🌱*
