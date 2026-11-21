# IICS Technical Assessment — Candidate Site

A static, GitHub Pages-ready assessment site containing six candidate test versions.

## What's included

- Six selectable versions.
- 20 open-ended questions and 20 multiple-choice questions per version.
- The same topic is assessed in Part A and Part B in the same question order.
- Mixed difficulty in every version: 8 Beginner, 8 Moderate, 2 Advanced, 2 Expert.
- Candidate name, progress indicator, response capture, JSON export, and print support.

## Deliberate answer-key exclusion

**This repository contains no correct answers, answer keys, scoring logic, or automatic grading.** Candidate responses are exported for an assessor to review separately.

## Deploy on GitHub Pages

1. Create a new GitHub repository, for example `iics-assessment`.
2. Upload `index.html`, `styles.css`, `app.js`, and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site. Open the URL shown in the Pages settings.

## Run locally

Open `index.html` in a modern browser. No build step, framework, server, or API key is required.

## Candidate response handling

The site runs entirely in the candidate's browser. On completion, the candidate downloads a JSON file and sends it to the assessor through the organization's approved channel.

- Responses are not sent to a server.
- Refreshing or closing the page before downloading may lose responses.
- Do not ask candidates to enter passwords, secrets, or sensitive personal information.
- For centralized submissions, connect a separate backend or approved form service. Keep private grading materials outside this public repository.

## Files

- `index.html` — page structure
- `styles.css` — responsive styling
- `app.js` — question bank and candidate-side behavior

## Customization

Edit `QUESTION_BANK` in `app.js` to update candidate question wording. Do not add answer keys or grading data to this public repository.
