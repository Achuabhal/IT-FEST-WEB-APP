# IT Fest Quiz Application 🎯

An interactive quiz application built for college tech fest competitions. This application provides an engaging quiz experience with timer-based questions, animated transitions, and particle effects.

## 🌟 Features

- **Timer-Based Questions**: 10-second countdown timer for each question with visual and audio feedback
- **Multi-Team Support**: Ability to manage questions for multiple teams during the fest
- **Interactive UI**: Smooth animations using Framer Motion for question transitions
- **Particle Background**: Eye-catching particle effects powered by react-tsparticles
- **Answer Reveal System**: Show/hide answer functionality for quiz masters
- **Audio Feedback**: Timer ticking sound and end buzzer for enhanced user experience
- **Question Navigation**: Navigate between previous and next questions seamlessly
- **Randomized Questions**: Questions are shuffled for each team to ensure variety
- **Material-UI Components**: Modern UI with circular progress indicator

## 🛠️ Tech Stack

- **Frontend Framework**: React 18.3.1
- **Build Tool**: Vite 5.4.1
- **UI Library**: Material-UI (MUI) v6.1.1
- **Animation**: Framer Motion 11.5.4
- **Particle Effects**: react-tsparticles 2.12.2
- **Styling**: Emotion (CSS-in-JS)
- **Code Quality**: ESLint with React plugins

## 📂 Project Structure

```
IT-FEST-ROUND/
├── Quiz/
│   ├── src/
│   │   ├── App.jsx              # Main quiz application logic
│   │   ├── App.css              # Application styles
│   │   ├── timer.jsx            # Timer component
│   │   ├── main.jsx             # Application entry point
│   │   ├── index.css            # Global styles
│   │   └── assets/
│   │       ├── data.js          # Quiz questions data
│   │       ├── StartPage.jsx   # Quiz start screen
│   │       ├── ParticleBackground.jsx  # Particle effects
│   │       ├── timer-sound.mp3 # Timer ticking sound
│   │       └── end.mp3         # Timer end buzzer
│   ├── public/                  # Static assets
│   ├── package.json            # Dependencies
│   ├── vite.config.js          # Vite configuration
│   ├── eslint.config.js        # ESLint configuration
│   └── index.html              # HTML template
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Achuabhal/IT-FEST-ROUND.git
cd IT-FEST-ROUND/Quiz
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
```

The optimized production build will be created in the `dist` folder.

### Preview Production Build

```bash
npm run preview
```

## 📝 Usage

1. **Starting the Quiz**: Click the start button on the landing page
2. **Timer Controls**:
   - Play/Pause: Click the play/pause button
   - Reset: Click the reset button to restart the 10-second timer
3. **Navigation**:
   - Next: Move to the next question
   - Back: Return to the previous question
4. **Answer Display**: Click "Show" to reveal the answer, "Hide" to conceal it
5. **Team Selection**: Switch between different teams using team buttons

## 🎨 Customization

### Adding Questions

Edit the `src/assets/data.js` file to add or modify questions:

```javascript
export default {
  team1: [
    {
      question: "Your question here?",
      answer: "Your answer here"
    },
    // Add more questions
  ],
  team2: [
    // Team 2 questions
  ]
}
```

### Adjusting Timer Duration

Modify the timer duration in `App.jsx`:

```javascript
const [seconds, setSeconds] = useState(10); // Change 10 to desired seconds
```

### Styling

Customize the appearance by editing:
- `App.css` - Main application styles
- `index.css` - Global styles

## 🎯 Use Cases

- College technical fest quiz competitions
- Inter-departmental quiz events
- Team-based quiz competitions
- Educational quiz sessions
- Tech trivia events

## 📜 Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint for code quality

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available for college fest use.

## 👨‍💻 Author

**Achuabhal**
- GitHub: [@Achuabhal](https://github.com/Achuabhal)

## 🙏 Acknowledgments

- Built with React and Vite for optimal performance
- UI components from Material-UI
- Animations powered by Framer Motion
- Particle effects by tsparticles

---

**Made with ❤️ for Tech Fest Competitions**