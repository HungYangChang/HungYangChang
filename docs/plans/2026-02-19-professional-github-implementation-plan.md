# Professional GitHub Presence Implementation Plan

> **For Claude:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task.

**Goal:** Build a recruiter-ready GitHub presence for Hung-Yang (James) Chang that clearly communicates AI/LLM engineering strength, production impact, and practical product-building ability.

**Architecture:** Create a profile-first system centered on one strong `README` in the profile repository, then standardize 4-6 flagship repositories with consistent structure, proof of quality, and clear business/engineering outcomes. Use lightweight automation (templates + CI) so every public repository signals the same professional standard.

**Tech Stack:** GitHub profile README, Markdown templates, GitHub Actions (CI + badges), issue/PR templates, project screenshots/demo links, optional static assets.

---

## Inputs Used
- CV source: `/Users/jameschang/Desktop/Smart_james/CV/CV.tex`
- Portfolio: [james-portfolio-psi.vercel.app](https://james-portfolio-psi.vercel.app/)
- Existing links in CV: [GitHub](https://github.com/HungYangChang), [LinkedIn](https://www.linkedin.com/in/hungyang), [Google Scholar](https://scholar.google.com/citations?hl=en&user=TXVBQjYAAAAJ&view_op=list_works)

## Positioning Direction (Recommended)
- Primary brand: `AI Software Engineer (LLMs + Production Systems)`
- Secondary signal: `Product-minded builder` (selected side projects with live demos)
- Proof pillars:
  - Production impact (99.9% uptime, 95%+ coverage, orchestration architecture)
  - Performance impact (9x throughput, latency/efficiency gains)
  - Research credibility (peer-reviewed publications)

## Approach Options

### Option A: Quick polish (1 day)
- Build profile README + pin repos + basic cleanup.
- Pros: Fast.
- Cons: Still shallow during technical screening.

### Option B: Recruiter-ready system (Recommended, 3-5 days)
- Option A plus repository standardization, CI quality signals, and narrative alignment.
- Pros: Strong hiring impact with moderate effort.
- Cons: Requires disciplined repo cleanup.

### Option C: Authority track (2-4 weeks)
- Option B plus regular technical writing + OSS contribution cadence.
- Pros: Best long-term compounding brand value.
- Cons: Ongoing maintenance commitment.

Recommended path: **Option B**.

## Success Criteria
- Profile README communicates role fit in under 30 seconds.
- 4-6 pinned repositories each have: problem, architecture, stack, setup, demo, results.
- Every flagship repo shows quality indicators (tests/CI or explicit reason if N/A).
- Recruiter can find: current focus, strongest projects, production/research credibility, contact links.

## Scope
- In scope:
  - Profile repository (`HungYangChang/HungYangChang`) README redesign
  - Pinned repo curation + metadata consistency
  - README and repo template standardization
  - CI/test badge strategy for flagship repos
- Out of scope (this phase):
  - Rewriting old project codebases end-to-end
  - Deep redesign of all historical repositories

## Implementation Tasks

### Task 1: Build profile messaging foundation
**Files:**
- Create: `assets/profile/headline-options.md`
- Create: `assets/profile/about-short.md`
- Create: `assets/profile/about-long.md`

**Steps:**
1. Write 3 headline variants focused on AI/LLM production engineering.
2. Draft a concise `About` block using CV metrics (9x throughput, 99.9% uptime, 95%+ coverage).
3. Draft a long-form profile summary with sections: `Current`, `Core Strengths`, `Selected Impact`, `What I’m building now`.
4. Verify language for recruiter readability (short paragraphs, concrete outcomes).

### Task 2: Author profile README (core asset)
**Files:**
- Create: `templates/profile/README.md`
- Create: `templates/profile/sections/contact.md`
- Create: `templates/profile/sections/featured-work.md`
- Create: `templates/profile/sections/publications.md`

**Steps:**
1. Create a hero section: name, role, location, links.
2. Add `Impact Highlights` with 3-5 quantifiable bullets from CV.
3. Add `Featured Projects` section mapped to portfolio apps.
4. Add `Publications / Research` section with top papers.
5. Add `Tech Stack` section grouped by domains (LLM systems, backend, infra, app).
6. Add `Contact` and `Open to` section.

### Task 3: Curate and pin flagship repositories
**Files:**
- Create: `assets/profile/pin-selection.md`
- Create: `assets/profile/repo-scorecard.md`

**Steps:**
1. Score candidate repositories using rubric: relevance, completeness, quality signal, demo readiness.
2. Select 4-6 repos balancing AI/backend/product breadth.
3. Define one-line positioning statement for each pinned repo.
4. Configure pin order: strongest technical signal first.

### Task 4: Standardize repository README quality
**Files:**
- Create: `templates/repo/README-template.md`
- Create: `templates/repo/ARCHITECTURE-template.md`
- Create: `templates/repo/CHANGELOG-template.md`

**Steps:**
1. Define a standard README structure:
   - Problem
   - Solution
   - Architecture
   - Stack
   - Local run steps
   - Demo/screenshots
   - Results/metrics
2. Apply template to each flagship repository.
3. Ensure all demo links and screenshots work.
4. Add explicit `Known limitations` to improve credibility.

### Task 5: Add professional collaboration hygiene
**Files:**
- Create: `templates/github/ISSUE_TEMPLATE/bug_report.md`
- Create: `templates/github/ISSUE_TEMPLATE/feature_request.md`
- Create: `templates/github/PULL_REQUEST_TEMPLATE.md`
- Create: `templates/github/CODEOWNERS`

**Steps:**
1. Add issue and PR templates for consistent public collaboration.
2. Add contribution guidance where appropriate.
3. Add license consistency check across flagship repos.
4. Add security/contact policy for responsible disclosure.

### Task 6: Add CI + quality signals
**Files:**
- Create: `templates/ci/ci.yml`
- Create: `templates/ci/README-badges.md`

**Steps:**
1. Add lightweight CI workflow pattern (lint/test/build where relevant).
2. Add status/test badges to README headers.
3. Ensure one green pipeline per flagship repo.
4. Document exceptions for repos where tests are not yet feasible.

### Task 7: Align portfolio and GitHub narrative
**Files:**
- Create: `assets/profile/portfolio-github-alignment.md`

**Steps:**
1. Ensure project naming is consistent between portfolio and GitHub.
2. Match one-sentence project descriptions across both surfaces.
3. Cross-link portfolio projects to source repos and vice versa.
4. Remove stale links.

### Task 8: Final quality review checklist
**Files:**
- Create: `assets/profile/final-checklist.md`

**Steps:**
1. Validate all external links.
2. Validate mobile readability of profile README.
3. Validate pinned repo order against target role.
4. Run a final “30-second recruiter scan” test.

## Suggested 5-Day Execution Schedule
- Day 1: Tasks 1-2 (positioning + profile README)
- Day 2: Task 3 (pin selection + ordering)
- Day 3: Task 4 (README standardization for top repos)
- Day 4: Tasks 5-6 (hygiene + CI)
- Day 5: Tasks 7-8 (alignment + final review)

## Recruiter-Scan Draft (for profile hero)
- `AI Software Engineer (LLM Systems, Production AI, Backend)`
- `Built and shipped multi-agent orchestration systems for automotive assistants; improved throughput by 9x and maintained 99.9% uptime in production services.`

## Risks and Mitigations
- Risk: Overly academic presentation may hide product impact.
- Mitigation: Put production outcomes before publication list.
- Risk: Too many side projects dilute core story.
- Mitigation: Pin only role-relevant, quality-complete projects.
- Risk: Inconsistent quality across pinned repos.
- Mitigation: Apply single README/CI template before pinning.

## Decision Log (Assumptions)
- Target role assumed: AI/LLM software engineer with full-stack capability.
- Geography and contact details follow CV sources.
- Portfolio projects are treated as supporting signals, not primary claim.

