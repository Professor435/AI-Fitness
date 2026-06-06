# AI-Fitness
  
  
I've created a fully functional, feature-rich **AI Fitness Trainer** with real-time pose detection. Here's what's included and the GitHub repository description:

---

## 🏋️ AI Fitness Trainer - Features

### **Core Capabilities**
- **Real-time Pose Detection** using MediaPipe BlazePose (33 body landmarks at 30fps)
- **Automatic Rep Counter** with state machine logic (Ready → Down → Up → Count)
- **AI Form Analysis** with real-time joint angle calculations
- **Visual Skeleton Overlay** with animated joint tracking
- **Audio Feedback** with Web Audio API (start, rep, completion sounds)
- **Calorie Tracking** per exercise type

### **Supported Exercises**
| Exercise | Target Muscles | Key Tracking |
|----------|---------------|--------------|
| **Squats** | Legs & Glutes | Knee angle, hip depth, back posture |
| **Push-ups** | Chest & Arms | Elbow angle, body alignment |
| **Bicep Curls** | Arms | Full range of motion |
| **Lunges** | Legs & Balance | Knee depth, torso position |
| **Shoulder Press** | Shoulders | Overhead extension |

### **Dashboard Features**
- **Circular Progress Ring** showing target completion %
- **Live Joint Angle Bars** (Knee, Hip, Back angles)
- **Real-time Form Feedback** (Good/Warning/Error states)
- **Session Timer** with elapsed time tracking
- **Today's Stats** (Total Reps, Sets, Calories, Duration)
- **Intensity Indicator** (Low/Medium/High)
- **Phase Indicator** (UP/DOWN/READY states)

### **Design & UX**
- 🎨 **Dark cyberpunk theme** with neon gradients
- ✨ **Animated background** with floating grid
- 🎉 **Confetti celebration** on set completion
- 📱 **Fully responsive** (desktop, tablet, mobile)
- 🖥️ **Glassmorphism UI** with backdrop blur effects

---

## 📁 GitHub Repository Description

```markdown
# 🤖 AI Fitness Trainer - Real-Time Pose Detection

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![MediaPipe](https://img.shields.io/badge/Powered%20by-MediaPipe-blue)](https://mediapipe.dev)
[![JavaScript](https://img.shields.io/badge/Built%20with-JavaScript-f7df1e)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

> A cutting-edge web application that transforms your browser into an AI-powered personal fitness coach using real-time human pose estimation.

## 🚀 Live Demo
[Try it now](https://your-demo-link.com) - No installation required, works directly in your browser!

## ✨ Key Features

- **🔍 Real-Time Pose Detection**: Tracks 33 body landmarks using MediaPipe BlazePose at 30fps
- **🔢 Smart Rep Counter**: Automatically counts repetitions using state machine logic with configurable thresholds
- **📐 Joint Angle Analysis**: Calculates real-time angles for knees, hips, elbows, and back
- **💡 AI Form Feedback**: Provides instant visual feedback on exercise form (Good/Warning/Error)
- **📊 Progress Tracking**: Circular progress rings, session timers, and workout statistics
- **🔊 Audio Cues**: Web Audio API feedback for rep counting and workout milestones
- **🎯 Multiple Exercises**: Supports Squats, Push-ups, Bicep Curls, Lunges, and Shoulder Press
- **📱 Responsive Design**: Fully functional on desktop, tablet, and mobile devices
- **🎨 Modern UI**: Dark theme with glassmorphism effects and smooth animations

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3 (Custom Properties, Grid, Flexbox, Animations)
- **AI/ML**: MediaPipe Pose (BlazePose model via CDN)
- **Graphics**: HTML5 Canvas API for skeleton rendering
- **Audio**: Web Audio API for real-time sound synthesis
- **Icons**: Font Awesome 6
- **Fonts**: Inter (Google Fonts)

## 🎯 How It Works

1. **Camera Access**: Uses your webcam for real-time video feed
2. **Pose Estimation**: MediaPipe detects 33 body landmarks per frame
3. **Angle Calculation**: Computes joint angles using vector mathematics
4. **State Machine**: Tracks exercise phases (Ready → Down → Up → Count)
5. **Form Analysis**: Compares angles against ideal thresholds
6. **Visual Feedback**: Displays skeleton overlay and real-time metrics

## 📦 Installation

No build process required! Simply open the HTML file in a modern browser:

```bash
git clone https://github.com/yourusername/ai-fitness-trainer.git
cd ai-fitness-trainer
# Open ai-fitness-trainer.html in your browser
```

## 🌐 Browser Support

- Chrome/Edge (Recommended)
- Firefox
- Safari (iOS 14+)
- Chrome Mobile

## 🔒 Privacy

All processing happens **locally in your browser**. No video data is sent to any server - your privacy is completely protected.

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [MediaPipe](https://mediapipe.dev) by Google for the pose detection model
- [Font Awesome](https://fontawesome.com) for the icon set
- [Inter Font](https://rsms.me/inter/) by Rasmus Andersson

---

**Made with 💪 and JavaScript**
```

---

**Download the complete application here:**
[AI Fitness Trainer](sandbox:///mnt/agents/output/ai-fitness-trainer.html)

Simply save the file and open it in any modern browser. Grant camera permissions when prompted, and you'll have a fully functional AI fitness trainer running entirely in your browser!

---
for more projects and FYP'scontact professorshami435@gmail.com
