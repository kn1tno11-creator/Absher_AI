# Absher Voice-First Prototype

This is a high-fidelity prototype for the enhanced Absher platform, featuring voice accessibility for elderly, illiterate, and visually impaired users.

## Project Structure

- **Frontend**: React 18, TailwindCSS
- **AI**: Google Gemini API (Natural Language Understanding)
- **Voice**: ElevenLabs API (Text-to-Speech)

## Setup & Deployment

1.  **Install Dependencies**
    ```bash
    npm install
    ```

2.  **Environment Variables**
    Create a `.env` file in the root directory and add your API Key:
    ```
    API_KEY=your_gemini_api_key
    ```

3.  **Run Locally**
    ```bash
    npm run dev
    ```

4.  **Build for Production (GitHub Pages)**
    ```bash
    npm run build
    ```
    The output will be in the `dist` folder.

## Deploying to GitHub

1.  Initialize git: `git init`
2.  Commit files: `git add . && git commit -m "Initial commit"`
3.  Push to your GitHub repository.
4.  Configure GitHub Pages to deploy from the branch or use a GitHub Action to build and deploy the `dist` folder.
