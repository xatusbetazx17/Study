# C++ Fundamentals – Interactive Quizzes & Video Resources (Mobile‑Friendly)

**Repo:** https://github.com/xatusbetazx17/Study  
**Live site (after Pages is enabled):** https://xatusbetazx17.github.io/Study/

This repository hosts **single‑file, mobile‑friendly C++ learning pages** that open like a normal website on any device:
- **No installs** required (pure HTML/CSS/JS).
- **Quizzes work offline** (everything is embedded).
- **Videos stream from YouTube** (internet required for videos).
- Tested on **Safari (iPhone/iPad)**, **Android (Chrome)**, **Windows/macOS/Linux** (Chrome/Edge/Firefox/Safari), and **Steam Deck**.

---

## 📁 Files in this repo (site map)

> If you rename any page to **`index.html`**, the root URL will load it automatically.

- **`First_interactive_quizpar_t01.html`**  
  **Chapters:** 1–3 — *Intro & I/O; Data Types & Expressions; Assignment/Input/Formatting*  
  - Topic filter, adjustable question count, instant feedback with **why**, review‑wrong‑answers mode.
  - **URL:** `https://xatusbetazx17.github.io/Study/First_interactive_quizpar_t01.html`

- **`Second_cpp_ch4,5,6_quiz.html`**  
  **Chapters:** 4–6 — *Selection (if/else, switch); Loops (for/while/do‑while); Functions (headers, params, return)*  
  - Practice mode, mobile‑friendly inputs, local progress persistence.
  - **URL:** `https://xatusbetazx17.github.io/Study/Second_cpp_ch4,5,6_quiz.html`

- **`Second_cpp_ch4,5,6_video_resources.html`**  
  **Chapters:** 4–6 — Curated beginner‑friendly videos (privacy‑enhanced embeds).  
  - **URL:** `https://xatusbetazx17.github.io/Study/Second_cpp_ch4,5,6_video_resources.html`

- **`First_cpp_interactive_quiz_mobile_option02.html`**  
  Mobile/desktop quiz shell (touch‑friendly UI, offline‑ready).  
  - **URL:** `https://xatusbetazx17.github.io/Study/First_cpp_interactive_quiz_mobile_option02.html`

> If you want a single “home” page, rename your preferred landing page to **`index.html`** or create a simple `index.html` that links to the four pages above.

---

## 🧭 Course coverage (6 chapters)

**Chapter 1 — Program Structure & I/O**  
- Program skeleton: `#include <iostream>`, `int main(){}`, `return 0;`  
- Console I/O: `cout`/`cin`, `\n` vs `endl`, comments (`//`, `/* … */`)

**Chapter 2 — Variables, Data Types & Expressions**  
- Identifiers & naming rules; reserved words  
- `int`, `long`, `float`, `double`, `char`, `bool`, `string`; `sizeof`  
- Operator precedence; integer vs floating‑point division; modulus `%`

**Chapter 3 — Assignment, Input, Formatting**  
- Assignment statements; `cin` prompts and echoing; basic formatting (`setprecision`, `fixed`)

**Chapter 4 — Selection**  
- `if/else if/else`, nested decisions  
- `switch`/`case`/`break`/`default`  
- Relational (`<`, `<=`, `>`, `>=`, `==`, `!=`) and logical (`&&`, `||`, `!`) operators

**Chapter 5 — Loops**  
- `for`, `while`, `do‑while`; counter vs sentinel loops  
- `break`/`continue`; common off‑by‑one pitfalls

**Chapter 6 — Functions**  
- Function headers (return type, name, params), calling functions  
- Return a single value; pass‑by‑value basics; scope/lifetime overview

---

## 📱 How students use it

- **Open the website:** share the GitHub Pages link.  
- **Use locally (optional):** download any `.html` and open it in a browser (iPhone/iPad via the **Files** app → **Open in Safari**).

**Works offline for quizzes** once loaded (no server needed).  
**Videos require internet**; each card also has an “Open on YouTube” link in case an iframe is blocked on mobile.

---

## ✏️ Editing / adding questions

Each quiz HTML is **self‑contained**:
- Open the file in a text editor and search for the **question bank** section (often an array/object named something like `QUESTION_BANK` or clearly labeled near the top).
- Add/edit questions (`q`, `choices`, `answer`, `why`), save, and refresh the page.
- You can adjust default question counts, topic filters, and labels in the same file.

> Keep the files single‑page to preserve **offline** behavior and easy hosting.

---

## 🔒 Privacy & data

- No analytics or tracking.  
- Local progress is saved only in the user’s browser (e.g., `localStorage`).  
- Videos are embedded from YouTube and follow YouTube’s terms.

---

## 🧪 Troubleshooting

- **Video not playing on mobile?** Tap **Open on YouTube** under the card.  
- **Changes not showing?** Hard‑refresh (Ctrl/Cmd+Shift+R) or append `?v=2` to the URL to bypass cache.  
- **Root URL not loading your page?** Ensure you have **`index.html`** at repo root (or share direct links).

---

## 🤝 Contributing

- PRs welcome for new questions, Spanish translations, accessibility tweaks (ARIA, keyboard navigation), and additional videos.  
- Please keep each HTML **self‑contained** (no external libraries) so the pages stay portable and offline‑ready.

---

## 📜 License

- **Code (HTML/CSS/JS):** MIT  
- **Text/explanations:** CC BY‑NC 4.0  
- **Videos:** Copyright remains with original channels (embedded under YouTube terms).


