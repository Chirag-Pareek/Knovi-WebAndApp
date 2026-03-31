# 🐾 Knovi — AI-Powered Interview Simulator

Knovi is an AI-powered interview simulation platform designed to evaluate real-world knowledge through structured, topic-based assessments. Instead of relying on traditional multiple-choice quizzes, Knovi focuses on long-form thinking, problem-solving ability, and clarity of explanation — closely mimicking real technical and conceptual interviews.

The goal of Knovi is simple: **measure how well someone understands a topic, not just how well they can guess answers.**

---

## 🧠 What Makes Knovi Different

Most assessment platforms rely heavily on MCQs, which often test recognition rather than understanding. Knovi takes a different approach by combining AI-generated questions with detailed answer evaluation.

Each test is dynamically generated based on the selected topic and includes a mix of:

* Objective questions for quick validation
* Long-form questions that require explanation, reasoning, and depth

The system evaluates not only correctness but also **how well the user communicates their knowledge**.

---

## ⚡ How the Platform Works

The user experience is designed to be simple, fast, and immersive.

A user begins by entering their name and selecting a topic of interest. Once the test starts, the system generates ten questions using AI. These questions are structured to simulate a real interview environment.

During the test:

* A timer runs continuously
* Users answer both MCQs and long-form questions
* A rich text editor allows structured answers

After submission, the answers are processed by the backend, where AI evaluates each response. The user is then presented with a complete results dashboard including:

* Final score out of 100
* Per-question scoring
* Detailed feedback
* Performance breakdown

---

## 🎯 Scoring Philosophy

Each long-form answer is evaluated based on four key dimensions:

* **Accuracy (0–4):** Whether the answer is technically correct
* **Depth (0–2):** Level of explanation and understanding
* **Relevance (0–2):** Focus on the actual question
* **Clarity (0–2):** Communication and structure

This creates a scoring model that rewards not just correctness, but **quality of thinking and explanation**.

---

## ✨ Feature Overview

### AI-Generated Assessments

Every test is generated dynamically using AI. This ensures that:

* Questions are not repetitive
* Difficulty can scale from beginner to expert
* The system remains flexible across topics

---

### Rich Answering Experience

Instead of plain text boxes, Knovi provides a structured input system similar to writing tools. Users can:

* Write detailed answers
* Organize thoughts clearly
* Focus on explanation rather than guessing

---

### Live Feedback and Results

Once the test is completed, users receive:

* A final score out of 100
* A breakdown of performance across questions
* AI-generated feedback explaining strengths and weaknesses

---

### Gamified User Experience (Live Cat System)

Knovi introduces a unique visual system where each completed test is represented by an animated “cat” on the home screen.

Each cat represents a real user session and displays:

* Name
* Topic
* Score
* Time of completion

This creates a dynamic and engaging environment that reflects real activity on the platform.

---

### Leaderboard System

A global leaderboard tracks high-performing users across topics. It provides:

* Competitive motivation
* Visibility of top scores
* Historical performance tracking

---

### Anti-Cheating Mechanisms

To ensure fairness and integrity of results, Knovi includes strict anti-cheat measures:

* Detects tab switching or app minimization
* Automatically resets the test if the user leaves the screen
* Disables paste in answer fields

These measures ensure that results reflect genuine effort.

---

## 🎨 Design and User Experience

Knovi combines a retro pixel aesthetic with modern UI/UX principles.

The interface is designed to feel:

* Lightweight and responsive
* Visually engaging
* Intuitive for both technical and non-technical users

Animations, transitions, and micro-interactions are used intentionally to make the experience feel alive without being distracting.

---

## 🧱 Technology Stack

Knovi is built using a hybrid architecture to support both web and mobile platforms.

### Frontend

* **Web:** React (Vite)
* **Mobile:** Flutter

### Backend

* Supabase (PostgreSQL database + Edge Functions)

### AI Layer

* Groq API for:

  * Question generation
  * Answer evaluation

This setup allows a single backend to power both platforms efficiently.

---

## 🗄️ Data Architecture

The system is structured around four primary entities:

**Tests** store user sessions and overall scores.
**Questions** store generated questions for each test.
**Answers** store user responses along with evaluation results.
**Leaderboard** tracks top scores across users.

This separation ensures scalability and clean data flow.

---

## 📁 Project Structure

The project is divided into three main parts:

* Web application (React)
* Mobile application (Flutter)
* Backend services (Supabase)

Each layer is designed to be modular, making it easier to scale or modify independently.

---

## 🚀 Getting Started

To run the project locally:

1. Clone the repository
2. Set up environment variables for Supabase and Groq
3. Run the web or mobile app independently

This allows developers to work on either platform without dependency conflicts.

---

## 🧪 Current Status

The project is currently in MVP development phase.

Completed:

* Full UI/UX system
* Test flow design
* Core interaction patterns

In progress:

* AI integration
* Backend logic
* Real-time leaderboard
* Live user system

---

## 🎯 Vision

Knovi aims to evolve into a complete interview preparation ecosystem.

Future directions include:

* Personalized interview simulations
* AI interviewer personalities
* Voice-based answers
* Resume-driven question generation

The long-term goal is to build a platform that helps users improve not just answers, but **how they think and communicate**.

---

## 🧠 Philosophy

Knovi is built on a simple idea:

> Good answers are not enough. Clear thinking is what matters.

---

## 🤝 Contributing

Contributions are welcome.
Feel free to fork the repository and submit improvements or new features.

---

## 📄 License

MIT License

---

## ⭐ Support

If you find this project useful, consider giving it a star on GitHub.
It helps the project grow and reach more users.
