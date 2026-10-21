# 🇬🇧 CAE Exam Prep (C1 Advanced)

A lightweight, interactive web application designed to help students prepare for the Cambridge C1 Advanced (CAE) English exam. Built with Vanilla JavaScript and Tailwind CSS, it uses dynamic JSON files to load study materials and mock exams.

## 🚀 Features

* **📚 Study Mode (Flashcards):** Interactive flip-cards to study Topic Vocabulary, Phrasal Verbs, Idioms, Collocations, and Word Formation.
* **⏱️ Exam Mode:** Select multiple topics and generate a randomized 30-question mock test with immediate correct/incorrect feedback and explanations.
* **⚡ Fully Dynamic:** Content is completely decoupled from the logic. Add new units simply by dropping a new JSON file into the project.
* **📱 Responsive Design:** Styled with Tailwind CSS to work flawlessly on both desktop and mobile devices.

## 🛠️ Tech Stack

* **HTML5**
* **Vanilla JavaScript** (ES6+)
* **Tailwind CSS** (via CDN)
* **JSON** (Data storage)

## 📂 Project Structure

```text
├── index.html        # Main application file (UI and Logic)
├── data/             # Folder containing all JSON data files
│   ├── temas.json    # Master index catalog of all available units
│   └── unit1.json    # Content file for Unit 1 (Study cards & Test questions)
└── README.md         # Project documentation
```

