# Quiz Hub

A GitHub Pages site hosting curated ML / CS quizzes with full explanations.

**Live site:** `https://slgao.github.io/quiz-hub/`

## Structure

```
/
├── index.html          ← Main hub page
├── quizzes/
│   └── ml-merantix.html   ← Merantix Momentum MLE screening quiz (40 Qs)
└── README.md
```

## Quizzes

| Quiz | Source | Questions | Topics |
|------|--------|-----------|--------|
| [MLE Screening](quizzes/ml-merantix.html) | Merantix Momentum | 40 | CNNs, Transformers, Optimization, Probabilistic ML, Python |

## Adding a New Quiz

1. Create `quizzes/your-quiz-name.html` (copy structure from `ml-merantix.html`)
2. Add a quiz card in `index.html` linking to it
3. Update the hero stats (quiz count, question count)
4. Commit and push — GitHub Pages deploys automatically

## GitHub Pages Setup

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main → / (root)**
4. Your site will be live at `https://<username>.github.io/<repo>/`
