# 🈶 Kanji Learning App
> Practice writing kanji with instant feedback and a built-in timer.

**Live:** Localy

---

## Stack

![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?style=flat-square&logo=vite&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-Custom-1572B6?style=flat-square&logo=css3&logoColor=white)

| Layer | Choice |
|---|---|
| Framework | React 18 |
| Bundler | Vite |
| Language | JavaScript (JSX) |
| Styling | Custom CSS |

---

## Features

- **Timed sessions** — click Start to begin; the timer runs until you finish your word list
- **Kanji input** — type the kanji for each displayed word and get immediate feedback
- **Instant feedback** — clear responses for correct answers, wrong answers, and completion
- **Progress tracking** — see how many words you've completed out of your total list
- **Cozy UI theme** — a warm, comfortable design to make studying enjoyable

---

## Getting Started

```bash
git clone https://github.com/Mohammed-Zaouk/Jap-Kanji-learning-app.git
cd Jap-Kanji-learning-app
npm install
npm run dev
```

Then open your browser at `http://localhost:5173`.

---

## How to Use

1. Open the app in your browser
2. Click **Start** — the timer begins immediately
3. A word appears on screen — type its kanji in the input field and confirm
4. You'll see a message based on your answer:
   - ✅ **Correct!** — move on to the next word
   - ❌ **Wrong answer, try again!** — the word stays until you get it right
5. Keep going until you finish your entire word list
6. Your total completion time is shown at the end 🎉

---

## Project Structure

```
Jap-Kanji-learning-app/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── layouts/
│   ├── pages/
│   ├── styles/
│   ├── App.jsx
│   └── main.jsx
├── index.html
├── vite.config.js
└── package.json
```

---

## Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start local dev server |
| `npm run build` | Production build |
| `npm run preview` | Preview the production build locally |

---

## License

This project is open source. Feel free to fork and build on it!
