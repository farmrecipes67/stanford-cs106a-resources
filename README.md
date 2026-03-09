# 📚 Stanford CS106A - Programming Methodology Resources

![CS106A Overview](https://drive.google.com/uc?export=view&id=1Li_cW3vDSDh28f1ma-TBV026OmWWT5LS)

> **Educational resources matching Stanford CS106A** — auto-generated with recursive AI for the culture ✨

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🎯 What's Inside

This repository contains comprehensive educational resources for **Stanford CS106A: Programming Methodology** (Java). Everything is stored in structured JSON format for easy integration into apps, study tools, and learning platforms.

### 📋 Topics Covered

| # | Topic | Resources |
|---|-------|-----------|
| 1 | **Karel the Robot** | [Content](topics/karel-the-robot/content.json) · [Quiz](topics/karel-the-robot/quiz.json) · [Vocab](topics/karel-the-robot/vocabulary.json) · [Cheatsheet](topics/karel-the-robot/cheatsheet.json) · [Pseudocode](topics/karel-the-robot/pseudocode.json) |
| 2 | **Control Flow** | [Content](topics/control-flow/content.json) · [Quiz](topics/control-flow/quiz.json) · [Vocab](topics/control-flow/vocabulary.json) · [Cheatsheet](topics/control-flow/cheatsheet.json) · [Pseudocode](topics/control-flow/pseudocode.json) |
| 3 | **Decomposition** | [Content](topics/decomposition/content.json) · [Quiz](topics/decomposition/quiz.json) · [Vocab](topics/decomposition/vocabulary.json) · [Cheatsheet](topics/decomposition/cheatsheet.json) · [Pseudocode](topics/decomposition/pseudocode.json) |
| 4 | **Variables and Types** | [Content](topics/variables-and-types/content.json) · [Quiz](topics/variables-and-types/quiz.json) · [Vocab](topics/variables-and-types/vocabulary.json) · [Cheatsheet](topics/variables-and-types/cheatsheet.json) · [Pseudocode](topics/variables-and-types/pseudocode.json) |
| 5 | **Loops** | [Content](topics/loops/content.json) · [Quiz](topics/loops/quiz.json) · [Vocab](topics/loops/vocabulary.json) · [Cheatsheet](topics/loops/cheatsheet.json) · [Pseudocode](topics/loops/pseudocode.json) |
| 6 | **Conditions** | [Content](topics/conditions/content.json) · [Quiz](topics/conditions/quiz.json) · [Vocab](topics/conditions/vocabulary.json) · [Cheatsheet](topics/conditions/cheatsheet.json) · [Pseudocode](topics/conditions/pseudocode.json) |
| 7 | **Strings** | [Content](topics/strings/content.json) · [Quiz](topics/strings/quiz.json) · [Vocab](topics/strings/vocabulary.json) · [Cheatsheet](topics/strings/cheatsheet.json) · [Pseudocode](topics/strings/pseudocode.json) |
| 8 | **Arrays and ArrayLists** | [Content](topics/arrays-and-arraylists/content.json) · [Quiz](topics/arrays-and-arraylists/quiz.json) · [Vocab](topics/arrays-and-arraylists/vocabulary.json) · [Cheatsheet](topics/arrays-and-arraylists/cheatsheet.json) · [Pseudocode](topics/arrays-and-arraylists/pseudocode.json) |
| 9 | **Object-Oriented Programming** | [Content](topics/object-oriented-programming/content.json) · [Quiz](topics/object-oriented-programming/quiz.json) · [Vocab](topics/object-oriented-programming/vocabulary.json) · [Cheatsheet](topics/object-oriented-programming/cheatsheet.json) · [Pseudocode](topics/object-oriented-programming/pseudocode.json) |
| 10 | **Graphics and Animation** | [Content](topics/graphics-and-animation/content.json) · [Quiz](topics/graphics-and-animation/quiz.json) · [Vocab](topics/graphics-and-animation/vocabulary.json) · [Cheatsheet](topics/graphics-and-animation/cheatsheet.json) · [Pseudocode](topics/graphics-and-animation/pseudocode.json) |
| 11 | **Event-Driven Programming** | [Content](topics/event-driven-programming/content.json) · [Quiz](topics/event-driven-programming/quiz.json) · [Vocab](topics/event-driven-programming/vocabulary.json) · [Cheatsheet](topics/event-driven-programming/cheatsheet.json) · [Pseudocode](topics/event-driven-programming/pseudocode.json) |
| 12 | **Memory Model** | [Content](topics/memory-model/content.json) · [Quiz](topics/memory-model/quiz.json) · [Vocab](topics/memory-model/vocabulary.json) · [Cheatsheet](topics/memory-model/cheatsheet.json) · [Pseudocode](topics/memory-model/pseudocode.json) |
| 13 | **File I/O** | [Content](topics/file-io/content.json) · [Quiz](topics/file-io/quiz.json) · [Vocab](topics/file-io/vocabulary.json) · [Cheatsheet](topics/file-io/cheatsheet.json) · [Pseudocode](topics/file-io/pseudocode.json) |
| 14 | **Collections and HashMaps** | [Content](topics/collections-and-hashmaps/content.json) · [Quiz](topics/collections-and-hashmaps/quiz.json) · [Vocab](topics/collections-and-hashmaps/vocabulary.json) · [Cheatsheet](topics/collections-and-hashmaps/cheatsheet.json) · [Pseudocode](topics/collections-and-hashmaps/pseudocode.json) |
| 15 | **Interactors and GUIs** | [Content](topics/interactors-and-guis/content.json) · [Quiz](topics/interactors-and-guis/quiz.json) · [Vocab](topics/interactors-and-guis/vocabulary.json) · [Cheatsheet](topics/interactors-and-guis/cheatsheet.json) · [Pseudocode](topics/interactors-and-guis/pseudocode.json) |

## 📦 Resources Per Topic

Each topic includes:

- 🧠 **Teaching Materials** — Key concepts, learning objectives, common mistakes, tips
- 📝 **Quiz** — 10 multiple-choice questions (beginner/intermediate/advanced) with explanations
- 📖 **Vocabulary** — 15 essential terms with definitions and Java code examples
- 📋 **Cheatsheet** — Concise syntax reference, common patterns, quick tips
- 💻 **Pseudocode Examples** — 3 examples each with pseudocode + Java implementation

## 🗂️ File Structure

```
├── README.md
├── LICENSE
├── index.json                    # Master index of all topics and file paths
├── all-content.json              # Complete combined dataset
└── topics/
    ├── karel-the-robot/
    │   ├── content.json          # Full topic content
    │   ├── quiz.json             # Quiz questions
    │   ├── vocabulary.json       # Vocabulary terms
    │   ├── cheatsheet.json       # Quick reference
    │   ├── pseudocode.json       # Code examples
    │   └── teaching.json         # Teaching materials
    ├── control-flow/
    │   └── ...
    └── ...
```

## 🚀 Usage

### Load a specific quiz
```javascript
const quiz = require('./topics/karel-the-robot/quiz.json');
console.log(quiz.questions[0].question);
```

### Load all content
```javascript
const allContent = require('./all-content.json');
allContent.topics.forEach(topic => {
  console.log(topic.topic + ': ' + topic.quiz.length + ' quiz questions');
});
```

## 🤖 How This Was Made

This entire repository was generated using **recursive AI content creation**:
1. Each topic was processed independently with structured JSON schema validation
2. Content was generated using GPT-5 with strict schema enforcement
3. The overview infographic was created with AI image generation
4. All files were assembled and pushed to GitHub programmatically

## 📄 License

MIT License — use freely for education, apps, study tools, and learning platforms.

---

*Made with 💜 by Papersaurus — bringing the joy of learning to everyone* 🦕
