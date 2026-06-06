# 🧠 Aura – Mental Wellness Tracker for Indian Exam Students

A beautifully designed, fully client-side **Mental Wellness Tracker** built for students preparing for **JEE, NEET, UPSC, CAT, and GATE** exams.

> Built for **PromptWars – Google for Developers Hackathon**

---

## ✨ Features

| Feature | Description |
|---|---|
| 😊 **Daily Mood Check-in** | 5-emoji mood scale with WCAG-accessible radio group |
| 🏷️ **Stress Trigger Logger** | Tag-based logging (Study, Sleep, Family, Exam, Peer, Health) + stress slider |
| 📊 **7-Day Mood Trend Chart** | Responsive custom SVG line chart with hover tooltips |
| 🤖 **AI Wellness Tips** | Pattern-based personalized advice with loading & error states |
| 🌬️ **Box Breathing Widget** | 4-4-4-4 breathing rhythm with animated pulsing circle |
| 🌊 **Ocean Sound Synthesizer** | Web Audio API ambient waves — zero external files |
| 🎨 **Dual Themes** | Forest Sanctuary 🌲 and Deep Ocean 🌊 themes |
| 📈 **Stress Analytics Dashboard** | Trigger frequency bars, 7-day activity grid, smart local insights |
| 🔢 **5-4-3-2-1 Grounding** | Step-by-step sensory grounding exercise |
| 🔥 **Streak Tracker** | Day-by-day check-in streak display |
| 💾 **localStorage Persistence** | All data saved locally — no backend needed |

---

## 🚀 Usage

Just open `index.html` in any modern browser — no build step, no server required.

```bash
# Quick preview via Python server (optional)
python3 -m http.server 8080
# Then open: http://localhost:8080
```

---

## 🧪 Tests

Open the browser DevTools console after loading the page. Tests run automatically:

```
[TEST RUNNER] Starting Aura wellness application test suite...
✔ Mood scoring statistics logic - PASSED
✔ Streak calculations and date continuity rules - PASSED
✔ Async mock tip analyzer responses and error handling - PASSED
✔ Boundary parameters (empty vs 7-day bounds) - PASSED
[TEST RUNNER] All tests completed: 4/4 PASSED.
```

---

## ♿ Accessibility

- Full **WCAG 2.1 AA** compliance — 4.5:1+ contrast ratios
- `aria-label`, `aria-live`, `role` attributes throughout
- Skip-to-content link for keyboard users
- Full keyboard navigation support

---

## 🛠️ Tech Stack

- **Vanilla HTML/CSS/JS** — single file, zero dependencies
- **Web Audio API** — synthesized ocean sound
- **SVG** — custom responsive mood chart
- **localStorage** — client-side data persistence
- **CSS Custom Properties** — dynamic theme switching

---

## 📁 File Structure

```
Winner1/
├── index.html     ← Complete app (HTML + CSS + JS + Tests)
└── README.md
```
