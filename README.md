# Koalafi

A web app that helps users discover which career field best suits them, powered by the OpenAI API rather than a static list of if/else rules.

**[Live Demo →](https://asher013.github.io/Koalafi/)**

## What It Does

Koalafi walks users through a short set of questions about their interests, strengths, and preferences, then uses OpenAI's GPT models to generate a personalized recommendation for which job field or career path might suit them best. Unlike a traditional quiz app built on hardcoded decision trees, the matching logic is handled dynamically by an LLM, allowing for more nuanced and natural-language-driven recommendations.

This project was built as the final project for CISC275 (Software Engineering) at the University of Delaware.

## Tech Stack

- **React 18** + **TypeScript** — component-based UI with static typing
- **Bootstrap 5** / **react-bootstrap** — responsive styling and layout
- **OpenAI API** — drives the core recommendation logic
- **canvas-confetti** — small celebratory UI flourish
- **Create React App** — build tooling and dev server
- **GitHub Pages** (`gh-pages`) — deployment

## Getting Started

Clone the repo and install dependencies:

```bash
git clone https://github.com/asher013/Koalafi.git
cd Koalafi
npm install
```

### Environment Setup

This project calls the OpenAI API, so you'll need an API key. Create a `.env` file in the project root:

```
REACT_APP_OPENAI_API_KEY=your_api_key_here
```

> **Note:** Never commit your API key. Make sure `.env` is included in `.gitignore`.

### Available Scripts

In the project directory, you can run:

| Command | Description |
|---|---|
| `npm start` | Runs the app in development mode at [http://localhost:3000](http://localhost:3000). Reloads on edit. |
| `npm test` | Launches the test runner in interactive watch mode. |
| `npm run build` | Builds an optimized production bundle to the `build/` folder. |
| `npm run deploy` | Builds and publishes the app to GitHub Pages. |

## Project Structure

```
Koalafi/
├── public/          # static assets
├── src/             # application source (components, logic, styling)
├── package.json     # dependencies and scripts
└── tsconfig.json    # TypeScript configuration
```

## Roadmap / Possible Improvements

- [ ] Expand question set for more granular career matching
- [ ] Add persistent user results (local storage or backend)
- [ ] Add unit tests for core recommendation logic
- [ ] Improve accessibility (a11y) across form components

## Acknowledgments

Built with [Create React App](https://github.com/facebook/create-react-app). See the [CRA documentation](https://facebook.github.io/create-react-app/docs/getting-started) and [React documentation](https://reactjs.org/) for more on the underlying tooling.

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
