# VTU Learners 🎓

A minimalist, high-performance study resource platform tailored for Visvesvaraya Technological University (VTU) engineering students. The platform provides a clean, distraction-free environment to access syllabus copies, notes, lab codes, question banks, and quick revision notes.

## ✨ Features.

- **Minimalist UI/UX:** Clean design built with vanilla CSS, focusing on readability and accessibility without relying on heavy frameworks.
- **Dark/Light Mode:** Seamless theme toggling to reduce eye strain during late-night study sessions. The preference is automatically saved in `localStorage`.
- **Responsive Layout:** Adaptive CSS grids ensure a perfect viewing experience across desktops, tablets, and smartphones.
- **Interactive Lab Programs:** Dedicated lab pages (like C Programming) featuring:
  - Expandable accordion-style questions.
  - Formatted code blocks.
  - One-click "Copy to Clipboard" functionality.
  - Built-in terminal-style expected output viewer.
- **Comprehensive Curriculum:** Structured layouts for Computer Science (CSE 2022 Scheme) from Semesters 1 through 8.

## 🛠️ Technology Stack

- **HTML5:** Semantic HTML structure.
- **CSS3 (Vanilla):** Custom CSS variables (`:root`) for theming, CSS Grid & Flexbox for layout. No external CSS frameworks were used to keep it extremely lightweight and fast.
- **JavaScript (Vanilla):** Handles theme toggling, mobile navigation, scroll-to-top buttons, dropdown accordions, and clipboard interactions.
- **Fonts & Icons:** Google Fonts (*Inter*) and FontAwesome (v6.5.1).

## 📁 Project Structure

- `vtu_learners.html` — The main landing dashboard and home page.
- `cse_sem1.html` to `cse_sem8.html` — Dedicated curriculum pages containing standard subject cards and resource buttons for each respective semester.
- `c_programming_lab.html` — Interactive lab manual with 10 standard VTU C programs, interactive copy buttons, and expected terminal outputs.

## 🚀 Getting Started

Since this project is built entirely with core client-side web technologies, no build tools, Node.js, or servers are required.

1. Clone or download the repository to your local machine.
2. Navigate to the project directory.
3. Open `vtu_learners.html` (or any other `.html` file) in your preferred modern web browser.
4. Enjoy!

## 💡 Future Enhancements

- Integrate actual PDF linking for Syllabus, Notes, Question Banks, and Solutions.
- Expand branch support to include Information Science (ISE), Artificial Intelligence & Machine Learning (AIML), and Data Science (DS).
- Add a global search feature to instantly look up subject codes and topics.
