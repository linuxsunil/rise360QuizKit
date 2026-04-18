# 🧩 Rise 360 Quiz Kit (KC Builder)

> **Transform raw text into interactive, brand-aligned Knowledge Checks for Articulate Rise 360 in seconds.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Articulate Rise 360](https://img.shields.io/badge/Articulate-Rise%20360-blue)
![AI Powered](https://img.shields.io/badge/AI-Gemini%20|%20Claude%20|%20GPT-orange)

Articulate Rise 360 is great, but manual entry for complex Multiple-Response (MMCQ) questions is tedious. **Rise 360 Quiz Kit** is a "non-techie" friendly bridge that allows you to bulk-paste questions, preview them in a live QA sandbox, and export a single block of code ready for the Rise Embed block.

---

## 🚀 Live Demo
**[Launch the Tool Here](https://linuxsunil.github.io/rise360QuizKit/)**

---

## ✨ Key Features

* ⚡ **Bulk Parsing:** Paste up to 500 questions at once using simple markdown-style notation.
* 🤖 **AI Question Generator:** Integrated API support for **Gemini 2.0 Flash**, **Claude 3.5**, and **GPT-4o** to brainstorm questions instantly.
* 🧪 **Granular QA Control (Game Changer):** Test and reset individual questions on the fly. No need to run the entire batch or restart the quiz to verify a single fix.
* 🎯 **Word-for-Word Mapping:** Perfectly align your source content with the tool by verifying each question stem and feedback loop independently during the QA phase.
* 🎨 **Brand Customization:** Real-time UI updates for primary and accent colors to match your corporate branding.
* 📦 **One-Click Export:** Generates a single, optimized HTML file for the Rise 360 Multimedia Embed block.
* 📥 **SME Review Export:** Download a standalone "QA HTML" file to send to Subject Matter Experts for review without giving them Rise access.

---

## 📖 How to Use

### 1. Paste Your Content
Use the **Format Guide** tab to see how to structure your text. 
* Use `*` to mark correct answers.
* Put `Feedback:` on the line below an option.

### 2. Preview & QA
Switch to the **QA Preview** tab. Here you can actually take the quiz.
* **Instant Validation:** Submit a question to see how the feedback renders.
* **Individual Reset:** If you spot a typo, you can reset just that specific question to test the logic again immediately without losing your progress on the rest of the batch.

### 3. Embed in Rise 360
1. Go to the **Rise HTML** tab and click **"Copy HTML for Rise 360"**.
2. In Articulate Rise, add a **Multimedia > Embed** block.
3. Click **Edit** > **Change Embed Code**.
4. Paste the code and save.

---

## 🛠️ Roadmap & Seeking Improvements
I am actively looking for feedback to evolve this tool. If you are an Instructional Designer or Developer, I’d love your input on:

* **Instructional Logic:** Are there specific "Partially Correct" or "Negative Scoring" models you'd like to see for MMCQs?
* **Action Mapping Filter:** I'm planning a feature to flag purely informational questions and suggest action-oriented alternatives.
* **Accessibility (a11y):** Help me ensure the generated HTML meets WCAG 2.1 standards for screen readers and keyboard navigation.
* **Feature Ideas:** Should we add support for Likert scales, drag-and-drop, or more complex scenario-based branching?

If you have ideas, please **Open an Issue** on GitHub or join the discussion in [IMPROVEMENTS.md](./IMPROVEMENTS.md).

---

## 👨‍💻 About the Developer
**I am** a Senior Instructional Designer working in the e-learning industry.

* **Philosophy:** I advocate for **Performance-First** instructional design and action mapping over traditional information-heavy courses.
* **The "Non-Techie" Coder:** While I identify as a non-coder, I build complex AI-integrated tools to solve real-world delivery bottlenecks.
* **Other Projects:** Developer of [Vyapar Lite](https://github.com/linuxsunil/Vyapar-Lite), [MCQ Studio](https://github.com/linuxsunil/MCQ-Studio), and the [Bharat Snack Index](https://github.com/linuxsunil/Bharat-Snack-Index).

---

## 🤝 Feedback & Contributions
This is an open-source project. If you have suggestions to improve the parsing logic or UI, please:
1. **Open an Issue** on GitHub.
2. **Submit a Pull Request** with your improvements.
3. Reach out on [LinkedIn](https://www.linkedin.com/in/sunil-iyer-b545964/) to discuss agentic AI workflows in L&D.

---

## 📜 License
Distributed under the **MIT License**. See `LICENSE` for more information.