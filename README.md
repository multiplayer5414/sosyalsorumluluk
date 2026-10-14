# EcoEnglish 🌿

A responsive, mobile-friendly English learning game for A1–A2 learners, built with plain HTML, CSS, and JavaScript. No build tools or account are required.

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Internet access is not required for the core site features.

## Publish with GitHub Pages
1. Create a new repository on GitHub (for example, `ecoenglish`).
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for the deployment and open the Pages URL shown there.

## Included working features
- Five mini lessons: recycling, saving water, animal protection, climate, and clean energy.
- Word-match game and fill-in-the-blank activity.
- 15-question quiz with immediate feedback, explanations, score, and results.
- Points, progress, badges, and an eco challenge.
- Responsive layout, keyboard-accessible buttons, high-contrast text, and browser text-to-speech when supported.
- A local rule-based practice helper with generated practice prompts.
- Progress saved locally in the browser using `localStorage`; no account or personal details are collected.

## Important: AI tutor status
The tutor currently uses simple, local rules. **It is not connected to a real AI service**, and it does not send messages to a server.

To connect a real AI model, use a backend (for example, a small serverless function) that stores the API key in a server-side environment variable and calls your chosen AI provider. Then change the browser chat code to send the learner's message to your backend endpoint. **Do not put an API key in `index.html` or any public GitHub repository**: visitors could copy it and use your account. If deploying on GitHub Pages only, you still need a separate backend/serverless service for secret API keys.

## Notes
- All scores are stored in the current browser only. Clearing browser site data may reset progress.
- Audio uses the browser's Speech Synthesis feature and may vary by device/browser.
- Environmental facts are simplified for beginner learners.


## New features in this version
- **Word of the Day:** an environment-related English word with an illustration, definition, pronunciation, and example sentence. The word changes daily.
- **Clean-up Mission (Drag & Drop):** sort litter into recycling, compost, and general-waste bins. On touch screens, tap an item and then its bin.
- **Your Habitat:** rescue a burning forest for 50 points, then plant trees for 10 points each. Habitat progress is saved in the browser along with your existing points.
