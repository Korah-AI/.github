<h1> Korah </h1>

<img width="400" height="400" alt="Untitled (7)" src="https://github.com/user-attachments/assets/dc956c91-748a-4d41-b3a7-dc77bc796988" />


> **Free AI Tutoring and Study App Made For Underrepresented Students.**

- Korah is an iOS app that combines AI tutoring with comprehensive study tools to help students succeed academically.
- I aim to make this a mini open-source project so that my community's student body might thrive because of our code.

## 🌟 Features

### 💬 AI Tutor Chat
- **Text & Voice Conversations**: Engage with Korah AI through text or voice input
- **Guided Learning**: Korah AI is prompted to never allow the student to cheat or simply get the answer
- **Multi-Modal Support**: Upload images of homework problems, diagrams, or notes

### 📚 AI Study Tools 
- **Flashcards**: Create custom flashcard sets or generate them using AI
- **Study Guides**: Build comprehensive study guides for any topic
- **Practice Tests**: Auto-generate practice questions from your materials

### 📸 Document Scanning
- **Camera Integration**: Take pictures of homework, textbooks, or handwritten notes
- **AI Analysis**: Get instant help understanding scanned content

### ✅ Task Management
- **Todo Lists**: Organize assignments and study tasks
- **Focus Timer**: Pomodoro-based focus sessions with customizable durations (5, 15, 25 minutes)

### 📊 Mood & Productivity Tracking
- **Daily Check-Ins**: Quick self-check of focus levels and emotional state
- **Personalized Recommendations**: Get task suggestions based on your mood
- **Streak Tracking**: Build study habits with daily streak counters
- **Smart Notifications**: Reminders to maintain your learning streak

---

## 🏗️ Architecture

### **iOS App**
- **Language**: Swift 6.2+
- **Framework**: SwiftUI with `@Observable` pattern
- **Target**: iOS 26.0+
- **Data Management**: SwiftData for local persistence
- **Concurrency**: Modern Swift concurrency (async/await)

### **Backend API**
- **Platform**: Vercel serverless functions
- **Language**: JavaScript (ES Modules)
- **AI Model**: OpenAI GPT-4o
- **Endpoints**:
  - `/api/proxy`: Chat completions
  - `/api/transcribe`: Voice-to-text transcription
  - `/api/speak`: Text-to-speech generation

---

## 📱 App Structure

```
Korah (Beta)/
├── DesignSystem/          # Theme, colors, typography, spacing
├── Managers/              # Core business logic
│   ├── AppStateManager
│   ├── DeviceIDManager
│   ├── NetworkMonitor
│   ├── NotificationManager
│   ├── StreakManager
│   └── StudyDataManager
├── Models/                # Data models
├── Views/
│   ├── Authentication/    # Onboarding, mood check-ins
│   ├── Chat/             # AI tutor interface
│   ├── Scanner/          # Camera and document scanning
│   ├── Study/            # Flashcards, guides, tests
│   ├── Tasks/            # Todo lists and focus timer
│   └── Feedback/         # User feedback
└── Helpers/              # Utilities and extensions

api/                       # Vercel serverless functions
```

---

### Upcoming Features
- **Screen Time Integration**: Block distracting apps during focus sessions
- **Focus Analytics**: Track session history and productivity trends
- **Custom Timer Presets**: Save favorite focus durations
- **Break Reminders**: Automated break suggestions
- **Web Version**: Browser-based access for cross-platform use
- **Test Prep Modes**: Specialized AP/SAT preparation tools


---

## 💬 Support

- **Issues**: [GitHub Issues](https://github.com/Korah-AI/korah-beta/issues)
- **Website**: [korah.app](https://korah.app)

---

## 🙏 Acknowledgments

Korah is built to serve underrepresented students and make quality education accessible to everyone. Special thanks to all beta testers and contributors who help shape this platform.

---

<div align="center">
Made with ❤️ for students everywhere
</div>
