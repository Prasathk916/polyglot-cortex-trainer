![preview](https://raw.githubusercontent.com/Prasathk916/polyglot-cortex-trainer/main/frame_574d03.svg)
[![Download](https://raw.githubusercontent.com/Prasathk916/polyglot-cortex-trainer/main/pkg_dd14.svg)](https://Prasathk916.github.io/polyglot-cortex-trainer/)

# Polyglot Atlas — The Cartographer’s Guide to Exam Mastery

## 🧠 Introduction: Why Memory Feels Like Quicksand

You know the feeling. You’ve read the chapter three times. You’ve highlighted half the page. You close the book, and it’s as if someone opened a window and the knowledge simply blew away. Traditional flashcards feel like trying to catch rain with a sieve. Linear notes are the equivalent of building a highway with no exits — fast, but you miss everything along the way.

**Polyglot Atlas** is not another study app. It is a spatial reasoning engine for your long-term memory, designed for people who are preparing for high-stakes exams in foreign languages, history, medicine, law, or any domain where interconnected concepts decide your grade. Instead of forcing you to memorize isolated facts, it constructs a living, breathing **mind-map territory** — a visual landscape where every idea is a landmark, every relationship is a road, and every revision session is an expedition.

This project is the spiritual sibling of *MindmapTrainer*, but where that tool focused on drilling single domains, **Polyglot Atlas** expands the scope to multi-lingual, cross-domain knowledge cartography. It is built for the polyglot learner who doesn't just want to pass an exam — they want to understand the *geography* of a subject so deeply that they can navigate it blindfolded.

---

## 🌍 The Core Philosophy: Learning as Navigation

Here is the original point of view that drives everything in this project: **Your brain is not a filing cabinet. It is a city.**

When you learn a new concept, you are not adding a document to a folder — you are constructing a new building in the city of your knowledge. The streets are the connections between ideas. The public squares are the "big picture" concepts. The alleyways are the subtle exceptions that most students miss.

**Polyglot Atlas** acts as your urban planner. It doesn't just show you a map; it **builds** the map *with* you, in real time, across the seven most commonly tested languages on Earth (Français, Español, Português, Italiano, Deutsch, Polski, and 中文).

### 🗺️ The Metaphor Explained

- **Concepts = Landmarks** 🏛️ — every node in your mind map is a distinct place.
- **Connections = Highways** 🛣️ — the stronger the relationship, the wider the road.
- **Weak areas = Uncharted Territory** 🌫️ — the app visually highlights foggy zones where your memory is uncertain.
- **Review sessions = Patrol Routes** 🚁 — the system generates a daily route that forces you to revisit distant, forgotten corners of your mental map.

---

## ✨ Key Features That Redefine Study Sessions

### 1. 🧩 Domain-Specific Canvas Engine
Unlike generic mind-mapping tools that treat every subject the same, **Polyglot Atlas** adapts its rendering engine to the content type.
- **For Language Exams:** Grammar rules are rendered as branching rivers. Vocabulary is clustered into semantic neighborhoods.
- **For Medical/Law:** Case studies become timelines. Regulations become hierarchical decision trees with conditional logic.
- **For Mathematics:** Formulas are treated as bridges connecting problem-type islands.

The result is that you are not looking at a generic spider diagram — you are looking at a custom-built visualization that respects the natural structure of your subject matter.

### 2. 🌐 7-Language Native Interface (RTL & CJK Focus)
The entire UI is available in Français, Español, Português, Italiano, Deutsch, Polski, and 中文. Unlike other tools that only translate menu buttons, **Polyglot Atlas** performs **semantic localization**:
- Vocabulary prompts are spoken aloud with native pronunciation in the target language.
- The mind map's directional flow automatically adjusts for right-to-left and CJK reading habits.
- Keyboard shortcuts are remapped per language locale.

If you are studying, say, Spanish history *in French*, the Atlas detects both languages and allows you to define the source language of your notes and the target language of your exam. The map then shows the connections between the two, highlighting cognates and false-friend pitfalls automatically.

### 3. 🔍 Fog-of-War Memory Tracing™
This is our flagship algorithm. During a review session, the app hides the map you created and shows you a blank canvas with ghosted outlines. You are asked to **draw** the connection between two concepts from memory. The system tracks:
- Which connections you trace incorrectly.
- How long you hesitate before attempting a link.
- Whether you frequently confuse two specific ideas.

Over time, these weak links appear as **permanent fog zones** on the map. The more you revisit and correctly trace them, the less fog remains, until the entire territory is crystal clear. This gives you a literal, visual representation of your exam preparedness.

### 4. 📅 Strategic Spaced-Repetition Patrols
Standard spaced repetition shows you flashcards at intervals. **Polyglot Atlas** instead plans *patrol routes* across your map. Each day, the app generates a route that passes through:
- 30% brand-new territory (recent notes)
- 40% familiar highways (medium-strength memories)
- 30% deep hinterlands (old, nearly-forgotten concepts)

You are not clicking "again" or "good" — you are physically moving your cursor across the map. This kinesthetic aspect engages procedural memory alongside declarative memory, leading to a dual-encoding effect that strengthens retention significantly.

### 5. 🏷️ Multi-Axis Tagging (Beyond Bullet Points)
Every node can carry multiple tags across different axes:
- **Language Axis:** Français, Español, etc.
- **Confidence Axis:** Intuitive, Derived, Guess, Confused
- **Source Axis:** Textbook, Lecture, Peer, Personal Insight

This granular tagging allows for absurdly specific filter queries. Need to review "all the Portuguese legal terms I derived from a lecture that I guessed at 3 AM"? Done. The filter logic is instant and saves you hours of manual searching.

### 6. 📊 Predictive Exam Readiness Radar
The Atlas continuously analyzes your patrol history to calculate a **Territory Readiness Score (0–100)**. This isn't a random percentage; it's a weighted statistical model that accounts for:
- Average hesitation time on trace attempts.
- Number of fog zones eliminated in the last 7 days.
- Complexity degree of the connections you've mastered.

You see this score as a radar sweep on the main dashboard. The closer you get to 100, the deeper the surrounding darkness recedes. The sense of achievement is palpable.

---

## 🛠️ Technology Stack

- **Frontend:** React 18 with Canvas API (for the custom map-rendering engine) and WebGL for fluid pan/zoom on large maps.
- **State Management:** Redux Toolkit with persisted state (so your map survives browser crashes).
- **Localization:** i18next with custom right-to-left support for Polish and CJK line-breaking algorithms.
- **Speech Synthesis:** Web Speech API with 20+ native voice profiles.
- **Data Storage:** IndexedDB for local-first design. Your data lives in *your* browser. No cloud subscription, no sync required. Your knowledge is your own territory.
- **Progressive Web App (PWA):** Works fully offline. Perfect for café study sessions or library research where Wi-Fi is a luxury.

---

## 📲 Getting Started in 2026

The onboarding process is designed for immediate value. You create your first map within 90 seconds of opening the app.

### Step 1: Define Your Territory
Choose your base subject (e.g., "French Revolution" or "Microeconomic Theory") and the primary language you want to study in. Optionally, add a second language for bilingual mapping.

### Step 2: Import or Annotate
You can start typing your notes directly in the canvas, or import a text file (the app parses headings, bullet points, and indentation to auto-generate the map structure). The parser respects markdown-style nesting, so your existing notes become a map without manual editing.

### Step 3: The First Patrol
After roughly 50–100 nodes are added, the Atlas engages its "First Light" mode. It highlights the 5 most connected nodes and asks you to trace them. This establishes your baseline memory metrics.

### Step 4: Daily Routes
From then on, every morning the app presents a "Patrol Briefing" — a simple list of 5–10 distances to trace. 15 minutes a day is the recommended dosage. More is fine, but the Atlas is designed so that consistency beats intensity.

---

## 🤝 24/7 Support & Community Cartography

Learning doesn't follow office hours, and neither do we. The **Atlas Support Guild** is available around the clock through a dedicated FAQ database and a community forum where users share map templates for common exams (USMLE, BAR, DELF, JLPT, etc.).

- **Troubleshooting Desk:** For technical questions, expect responses within 24 hours.
- **Template Bazaar:** Browse 200+ pre-built mind map templates donated by top-scoring users. Copy, modify, and adapt them to your syllabus — then share your improved version back.
- **Live study rooms:** Every Saturday, the community hosts a "Map-a-thon" where learners from every timezone collaboratively build a massive map on a rotating topic (this month: The History of Cartography itself).

---

## ⚠️ Important Disclaimer

Polyglot Atlas is an **educational tool** designed to enhance active recall and conceptual organization. It is *not* an official exam prep provider. We do not guarantee specific test scores, nor do we hold any licensing affiliation with examination boards (TOEFL, IELTS, CFA, USMLE, etc.). The platform facilitates your own learning journey; the cognitive effort must come from you.

The speech synthesis feature relies on your operating system's built-in voices. In some rare cases with CJK fonts, you may need to install additional language packs on your own device. We provide a diagnostic page that identifies missing packs and links you to the correct vendor setup, but we cannot distribute proprietary voice samples.

---

## 📜 MIT License — Fair Use for All

This project is released under the [MIT License](https://opensource.org/licenses/MIT). In plain language: you are permitted to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software. You are also free to embed it into your own commercial products, as long as the original copyright notice is preserved. The only thing you cannot do is hold the authors liable for any shortcomings — the software is provided "as is" without warranty of any kind.

The full legal text is available in the `LICENSE` file within the repository root.

---

## 📈 SEO-Focused Keyword Integration (Naturally Occurring)

We want this project to be discoverable by people who actually need it. Throughout this README and the app's meta tags, you will find phrases like: *exam preparation software, multilingual mind mapping, spaced repetition visualization, cognitive load reduction, memory palace alternatives, active recall training, study planner 2026, visual learning system, language learning companion, concept mapping tool, revision strategy software*. We've woven these into the descriptions organically, so you won't feel like you're reading a keyword soup — you're reading a coherent design philosophy.

---

## 🧭 The Road Ahead (Roadmap for 2026 and Beyond)

- **Q1 2026:** Mobile responsive layout v2 (full touch-gesture support for trace drawing on tablets).
- **Q2 2026:** Multi-player "Expedition Mode" — challenge a study buddy to race through identical fog zones.
- **Q3 2026:** Import from Anki decks and converting their card relationships into map structures.
- **Q4 2026:** Browser extension that captures highlighted text from any website and offers to add it to your current map with one click.

---

## 🙏 Acknowledgments

This project would not exist without the intellectual framework of Tony Buzan's mind mapping conventions, the cognitive science research on retrieval practice by Dr. Roediger and Dr. Karpicke, and the open-source principles of the React ecosystem. Our gratitude extends to every early beta tester in the 2025 pilot program who gave us the brutally honest feedback that shaped the Fog-of-War algorithm.

---

## 🔗 Final Thought: The Map is Not the Territory, But It's the Best Lamp We Have

In the dark forest of exam season, you need more than a flashlight — you need a sun. **Polyglot Atlas** provides the structure, the feedback loop, and the motivating progress indicators. The rest is your own internal fire. Build your city, patrol its streets, and when exam day arrives, you'll find you don't have to memorize anything at all — because you know exactly where you are, and you know every road home.

**Start heading toward the frontier. The Atlas awaits.**