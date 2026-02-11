**AI Decision Tree Builder**
🌍 Live demo: https://ai-decision-tree.netlify.app 

AI Decision Tree Builder is a single-page HTML/CSS/JS app to evaluate **if**, **when**, **and how to adopt AI **across different business processes, using guided decision trees and structured scoring ( **Fit/Readiness/Risk** ).

![Screenshot](https://github.com/user-attachments/assets/7f3f33a0-99ec-4cb1-9c84-e618771c4f1a)

**Key Features**

* **Multi-use-case:** 3 built-in cases (email triage, HR screening, predictive maintenance), easily extensible.
* **Numeric scoring**: Progressive calculation of Fit, Readiness, and Risk along the decision path.
* 	**Node editor**: Live editing of the tree (texts, choices, scores, connections).
* 	O**ffline-first**: Runs entirely locally in a single file, ai-decision-tree.html, with persistence via localStorage.
* 	**Decision Memo**: Generates a board-ready memo including problem statement, recommendation, risks, and next steps.
* 	**JSON export/import**: Snapshot of state and configuration, versionable in Git.
* 	**Tree visualization**: Interactive graphical view of the decision tree, with the current path highlighted.
* 	**Print / PDF**: Layout optimized for printing or saving as PDF.

**How to Use**

1. Clone the repository or download ai-decision-tree.html.
1. Open the file in a modern browser (Chrome, Edge, Firefox, Safari).
1. 	Select a **case study** from the top-left menu.
1. 	Answer the questions by following the decision tree.
1. 	Review:
 
a) Fit / Readiness / Risk **scores**

b) The suggested verdict

c) The generated Decision Memo

>>> Use the Editor to adapt the tree to your context (nodes, copy, weights, outcomes). 

**Who It’s For**

* 	**Founders**, **C-level executives**, and **function heads** deciding where AI actually makes sense.
* 	**Innovation**, **digital**, and **data teams** looking for a repeatable framework to assess AI use cases.
* 	**Consultants** who want a lightweight, offline, demo-friendly tool to use with clients.

Roadmap (Future Ideas)
	Path history and comparison across multiple use cases.
	Full undo/redo for decisions.
	Export tree as an image (PNG/SVG) for slides.
	New vertical templates (finance, retail, healthcare, etc.)

**License**

MIT (or the license of your choice).
