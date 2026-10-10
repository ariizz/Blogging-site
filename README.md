# Scribble Lab ✏️
> A lightweight, retro-styled personal blogging web app built from scratch with pure HTML, CSS, and JavaScript.

---

## 📌 Project Overview
**Scribble Lab** is a frontend web development project created as part of my college coursework. 

The idea behind this project was to build a clean, responsive, and functional blog platform without relying on heavy external frameworks or libraries like React, Bootstrap, or Tailwind. I wanted to see how far vanilla web technologies could take me while maintaining good performance, accessible design, and a unique visual identity.

The site is themed around a tactile **"notebook / neo-brutalist"** aesthetic — featuring bold ink borders, playful paper color palettes, subtle offset drop shadows, and lively typography.

---

## ✨ Key Features

- **Single-Page Application (SPA) Experience:** Smooth hash-based navigation (`#/` for the feed and `#/post/:id` for full articles) without full page reloads.
- **Publish Custom Posts:** An interactive modal allowing users to create, preview, and publish new articles with markdown-like subheadings.
- **Client-Side Persistence:** Newly created posts, likes, comments, and theme preferences are saved in browser `localStorage`, so your data stays even after refreshing.
- **Category Filtering & Live Search:** Quick-filter tags (Coding, Study, Gadgets, Life) and an instant search bar that filters by title, tags, and summary text.
- **Interactive Comments & Likes:** A functional comment section on every article where readers can leave remarks with automatic timestamps.
- **Light & Dark Theme:** Built-in theme switcher that adapts to your system preferences by default and can be toggled manually anytime.
- **Reading Time Estimation:** Dynamically computes estimated read times for each article based on word count.
- **Fully Responsive:** Adapts cleanly across mobile phones, tablets, and desktop screens with custom media queries.

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Markup** | Semantic HTML5 (Custom dialogs, semantic tags, accessible forms) |
| **Styling** | Custom Vanilla CSS (CSS Variables, Flexbox, CSS Grid, Neo-brutalism design) |
| **Fonts** | Google Fonts (*Space Grotesk* for headings, *Space Mono* for meta info & code) |
| **Scripting** | Modern Vanilla JavaScript (ES6+, DOM manipulation, Event listeners) |
| **Storage** | Web Storage API (`localStorage`) |

---

## 📂 Project Structure

```text
blogging site/
├── blogging-site.html   # Main application file containing markup, styling & script
└── README.md            # Project documentation
```

> **Note:** The entire logic, style system, and interface are self-contained to keep deployment and local testing as effortless as possible.

---

## 🚀 How to Run the Project Locally

Because this project uses standard browser APIs and vanilla code, no package manager (`npm` or `yarn`) or build step is required!

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ariizz/Blogging-site.git
   ```
2. **Navigate to the folder:**
   ```bash
   cd Blogging-site
   ```
3. **Open the site:**
   - Simply double-click `blogging-site.html` to open it in your default browser (Chrome, Edge, Firefox, Brave, Safari).
   - *Or* open the folder in **VS Code** and click **"Go Live"** using the **Live Server** extension.

---

## 🧠 What I Learned

Building this project helped me strengthen practical frontend fundamentals:
1. Handling client-side routing without a router library using `window.location.hash` and the `hashchange` event.
2. Managing UI state and persisting user data across sessions using the `localStorage` API.
3. Writing organized, maintainable CSS using design tokens (CSS variables) to build a two-tone light/dark mode system.
4. Structuring accessible HTML forms and working with modern elements like native `<dialog>` modals.

---

## 🔮 Future Roadmap

If I continue expanding this project in future semesters, I'd like to explore:
- [ ] Adding image upload support (storing base64 or linking external URLs)
- [ ] Markdown editor with real-time preview
- [ ] Export/Import notes as JSON or Markdown files
- [ ] Hooking up a backend database (e.g., Supabase, Firebase, or Node.js/Express) for real multi-user persistence

---

## 👤 Author

- **Name:** Ayush
- **Coursework:** Web Development Assignment
- **GitHub:** [@ariizz](https://github.com/ariizz)

Feel free to fork this project, suggest improvements, or use it as inspiration for your own projects!