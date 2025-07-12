# 🐧 Linux Desktop Dashboard

A beautiful, modern Linux desktop dashboard built with HTML, CSS (Tailwind), and JavaScript. This dashboard provides a sleek interface for monitoring system resources, playing music, and managing your desktop environment.

## ✨ Features

### 🎨 Modern UI Design
- **Dark Theme**: Elegant dark color scheme with blue accents
- **Responsive Layout**: Grid-based layout that adapts to different screen sizes
- **Smooth Animations**: Hover effects and transitions for better user experience
- **Glass Morphism**: Subtle borders and shadows for a modern look

### 📊 System Monitoring
- **Real-time CPU Usage**: Live CPU monitoring with animated progress bars
- **Memory Usage**: RAM usage tracking with visual indicators
- **Disk Usage**: Storage monitoring with percentage displays
- **Network Status**: Connection status and IP address display

### 🎵 Music Player
- **Now Playing**: Current track information display
- **Playback Controls**: Play, pause, skip forward/backward buttons
- **Progress Bar**: Visual track progress indicator

### 🎯 Quick Access
- **Application Launcher**: Sidebar with quick access to applications
- **System Controls**: Settings, power, and system management
- **Social Links**: GitHub, Twitter, and email integration

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/BNB2006/Dashboard.git
   cd Dashboard
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Build the CSS**
   ```bash
   npm run build
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:3000`

## 🛠️ Development

### Project Structure
```
Dashboard/
├── assets/
│   └── rakun.jpg          # Profile picture
├── src/
│   ├── input.css          # Tailwind CSS input
│   └── output.css         # Compiled CSS (generated)
├── index.html             # Main dashboard file
├── package.json           # Project configuration
└── README.md             # This file
```

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build production CSS
- `npm test` - Run tests (placeholder)

### Customization

#### Colors
The dashboard uses a blue-based color scheme. You can customize colors by modifying the Tailwind classes in `index.html`:

- Primary: `blue-300`, `blue-400`, `blue-500`
- Background: `gray-800`, `gray-900`
- Accents: `green-500`, `orange-500`, `cyan-500`

#### Widgets
Each widget is a separate card that can be easily modified or replaced. The layout uses CSS Grid for flexible positioning.

#### System Monitoring
The JavaScript in `index.html` simulates real system monitoring. In a real implementation, you would connect to your system's monitoring APIs.

## 🎨 Design Features

### Layout
- **Left Sidebar**: Application launcher with icons
- **Main Grid**: 5x3 grid layout for widgets
- **Right Sidebar**: Additional system controls

### Widgets
1. **Profile Card**: User information and social links
2. **CPU Widget**: Real-time CPU usage monitoring
3. **Memory Widget**: RAM usage with progress bar
4. **Music Player**: Now playing with controls
5. **Network Widget**: Connection status
6. **Disk Widget**: Storage usage monitoring
7. **Quote Card**: Inspirational quotes
8. **Weather Widget**: Current weather information
9. **System Status**: Detailed system information

### Animations
- Hover effects on all interactive elements
- Smooth transitions for color changes
- Scale animations on social media links
- Progress bar animations

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework
- **JavaScript**: Interactive features and animations
- **Font Awesome**: Icon library

### Browser Support
- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge

### Performance
- Optimized CSS with Tailwind's purge
- Minimal JavaScript for smooth performance
- Efficient DOM updates

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Tailwind CSS** for the amazing utility-first CSS framework
- **Font Awesome** for the beautiful icons
- **Henri Poincaré** for the inspirational quote

## 📞 Contact

Balaji Bandgar - [@yourtwitter](https://twitter.com/yourtwitter) - your@email.com

Project Link: [https://github.com/BNB2006/Dashboard](https://github.com/BNB2006/Dashboard)

---

⭐ Star this repository if you found it helpful!