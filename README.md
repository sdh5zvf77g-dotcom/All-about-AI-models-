# AI Model Atlas

**Interactive scientific field guide to AI models, training, neural networks, weights, inference, evaluation, safety, AGI and ASI.**

A self-contained, offline-capable educational web app. No backend. No tracking. Works as a Progressive Web App (PWA) so you can add it to an iPhone (or Android) Home Screen with a custom AI icon.

---

## What’s inside

| Section | Content |
|--------|---------|
| **History & paradigms** | Timeline, symbolic vs connectionist vs hybrid, ML families |
| **Foundations** | Model vs system, capability ≠ consciousness |
| **Architecture** | Transformers, attention, other families, tokens & embeddings |
| **Weights & tensors** | Parameter storage calculator, quantization, training vs inference memory |
| **Training** | Lifecycle, loss/gradients, alignment, interactive learning-rate playground |
| **Inference** | Autoregressive generation, temperature/top-k lab, context, tools & agents |
| **Reasoning** | Scientific account of “thinking”, interpretability limits |
| **Code lab** | Linear layer, softmax, training loop, token flow snippets |
| **Evaluation** | Dimensions, benchmark pitfalls, hallucination, interactive scorecard |
| **Safety** | Reliability, security, social impact, safeguards |
| **Deployment** | Hardware, serving, monitoring, open weights vs open source |
| **AGI & ASI** | Definitions, technical paths, autonomy, alignment, timelines, grounded conclusion |
| **Society & ethics** | Labor, bias, misinformation, power concentration, governance |
| **Glossary + Quiz** | Essential terms and a short knowledge check |

Tone is scientific and cautious: no hype, no claim of secret weights, clear distinction between capability and consciousness.

---

## Run locally

```bash
# Clone (or download the folder)
git clone https://github.com/YOUR_USERNAME/ai-model-atlas.git
cd ai-model-atlas

# Any static server works. Examples:
python3 -m http.server 8080
# or
npx serve .
```

Open `http://localhost:8080` in a browser.

You can also just open `index.html` directly in a browser (some PWA / service-worker features need a server).

---

## Deploy on GitHub Pages

1. Create a new repository (e.g. `ai-model-atlas`).
2. Push this folder to the repository root (or a `docs/` folder).
3. In **Settings → Pages**, set source to the branch and folder that contains `index.html`.
4. After a minute, the site is live at `https://YOUR_USERNAME.github.io/ai-model-atlas/`.

---

## Add to iPhone Home Screen (with AI icon)

1. Open the site in **Safari**.
2. Tap the **Share** button → **Add to Home Screen**.
3. The custom icon (`icons/apple-touch-icon.png`) and name “AI Atlas” will appear.
4. Launching it opens in standalone mode (no browser chrome).

Android: Chrome → menu → **Install app** / **Add to Home screen**.

---

## Project structure

```
ai-model-atlas/
├── index.html          # Full interactive guide
├── manifest.json       # PWA manifest
├── sw.js               # Minimal offline service worker
├── icons/
│   ├── icon.svg        # Vector source
│   ├── icon-192.png
│   ├── icon-512.png
│   └── apple-touch-icon.png
└── README.md
```

---

## License & purpose

Educational field guide. Free to fork, adapt, and share for learning.  
Not affiliated with any model provider. Not a substitute for primary papers, model cards, or professional evaluation.

---

## Contributing ideas

- Additional quiz questions
- More interactive demos (attention visualization, simple diffusion step, etc.)
- Translations
- Accessibility improvements
- Updated references as the field moves

Pull requests and issues welcome.
