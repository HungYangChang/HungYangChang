# GitHub Presence System — Hung-Yang (James) Chang

A complete toolkit for building and maintaining a professional, recruiter-ready GitHub presence.

## What's Inside

```
├── templates/
│   ├── profile/           # GitHub profile README + section modules
│   │   ├── README.md      # ← Deploy this to HungYangChang/HungYangChang repo
│   │   └── sections/      # Reusable profile sections
│   ├── repo/              # Standardized README, ARCHITECTURE, CHANGELOG templates
│   ├── github/            # Issue/PR templates, CODEOWNERS, SECURITY, CONTRIBUTING
│   ├── ci/                # GitHub Actions CI workflows (Python + Node.js)
│   └── writing/           # Blog post template + technical writing strategy
├── assets/
│   └── profile/           # Messaging foundation, pin strategy, checklists
│       ├── headline-options.md
│       ├── about-short.md
│       ├── about-long.md
│       ├── pin-selection.md
│       ├── repo-scorecard.md
│       ├── portfolio-github-alignment.md
│       ├── oss-contribution-cadence.md
│       └── final-checklist.md
└── docs/
    └── plans/             # Implementation plans
```

## How to Use

### 1. Deploy Profile README
Copy `templates/profile/README.md` to your `HungYangChang/HungYangChang` repository.

### 2. Standardize Flagship Repos
Apply `templates/repo/README-template.md` to each pinned repository.
Copy GitHub templates from `templates/github/` to each repo's `.github/` folder.

### 3. Add CI Pipelines
Copy the appropriate CI workflow from `templates/ci/` to `.github/workflows/ci.yml`.

### 4. Score and Pin Repos
Use `assets/profile/repo-scorecard.md` to evaluate candidates.
Follow `assets/profile/pin-selection.md` for ordering.

### 5. Align Portfolio ↔ GitHub
Work through `assets/profile/portfolio-github-alignment.md`.

### 6. Final Review
Complete every item in `assets/profile/final-checklist.md`.

### 7. (Option C) Build Authority
Follow `templates/writing/technical-writing-strategy.md` for content cadence.
Follow `assets/profile/oss-contribution-cadence.md` for OSS engagement.
