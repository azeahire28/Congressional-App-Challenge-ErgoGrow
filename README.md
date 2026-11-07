# ErgoGrow

> **Your Very Own Desk Buddy**  
> An accessible, software-first desktop wellness companion designed to prevent sedentary desk strain, posture fatigue, and screen exhaustion for students and professionals.

---

## Problem Overview & Vision

Modern work and study environments force millions of individuals into prolonged, sedentary screen sessions. While corporate ergonomic tools often focus on expensive physical hardware, such as smart desks or specialized chairs, so everyday computer users lack an accessible and unified software solution. 

Most people suffer from musculoskeletal strain in silence and on their own by experiencing tech neck, lower back stiffness, wrist tension, and eye strain without proactive tools to build healthy movement habits early. Research shows that short, consistent, and incremental stretching periods throughout the day are far more effective at mitigating long-term discomfort than "sporadic" physical activity.

ErgoGrow bridges this gap by transforming a fragmented process into a single, cohesive desktop experience. Instead of juggling four separate tools, like standalone web timers, generic calendar alerts, YouTube search videos, and manual exercise logs, but ErgoGrow unifies productivity and wellness all in one seamless desktop application.

---

## Key Features

- **Customized Symptom Assessment**: Tailors wellness routines based on the specific physical focuses (eye strain, neck tension, back/posture stiffness, wrist strain, hip tightness, and tension headaches).
- **Adaptable Focus Timers**: Features flexible productivity intervals designed to support various working and learning styles, including:
  * Pomodoro (25-minute focus / 5-minute break)
  * 52/17 Rule
  * 90-Minute Cycles
  * Flowtime Technique
- **Guided Interactive Stretches**: Visual guides featuring live countdown timers, step-by-step instructions, and targeted exercise animations.
- **Localized Persistence**: Secure local authentication and state management to retain custom user preferences without forcing any cloud dependencies.
- **OS-Native Desktop Hub**: Built as a dedicated desktop window to live directly where desk work happens, providing frictionless notifications and overlay popups without clogging your browser tabs.

---

## Tech Stack & Architecture

- **Framework**: Electron (Desktop Application Runtime)
- **Runtime & Environment**: Node.js
- **Frontend UI**: HTML5, Modern CSS3, and Vanilla JavaScript
- **State & Storage**: Browser Local Storage and Asynchronous Timers
- **Media Assets**: Luma AI (Exercise Visualizations) and Custom UI Design

---

## Installation & Getting Started

To run ErgoGrow locally on your machine:

- **Clone the repository:**
  `git clone https://github.com/azeahire28/Congressional-App-Challenge-ErgoGrow.git`
- **Navigate to the project directory:**
  `cd Congressional-App-Challenge-ErgoGrow`
- **Install the dependencies:**
  `npm install`
- **Start the application:**
  `npm start`

---

## Version 2.0 Roadmap

While ErgoGrow currently provides a robust, fully functional desktop MVP, planned future updates include:

1. **Cloud Database Migration**: Transitioning from local storage to Supabase for cross-device synchronization (it'll include seamless switching between laptops and desktop setups).
​2. **OS-System Integration**: Running as a continuous background daemon that's capable of delivering native operating system notifications even when minimized.
3. **Webcam-Based Machine Learning Posture Detection**: Integrating computer vision libraries to analyze posture in real time, triggering the proactive alerts immediately when slouching or neck strain is detected.

---

## Submission Context

Developed for the **Congressional App Challenge (CAC)**.  
**Authors**: Aadhila Zeahire Irfaan Ahamed and Harita Dilip
