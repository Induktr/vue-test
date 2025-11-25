# Copilot Instructions

## About This Project

This project, "Insight Keeper," is a practical experiment to compare Vue 3's **Options API** and **Composition API**. It contains two separate implementations of the same mini-blog application, each in its own directory:

- `options-api-version/`: The classic Options API implementation.
- `composition-api-version/`: The modern Composition API implementation using `<script setup>`.

The primary goal is to analyze and contrast these two approaches. The key findings are documented in `docs/doc-analizys.md`.

## Key Project Structure

- `docs/`: Contains the project's requirements, design specifications, and the final comparative analysis.
- `options-api-version/`: The complete source code for the Options API version of the app.
- `composition-api-version/`: The complete source code for the Composition API version of the app.

## Development Workflow

To work with either version of the application, follow these steps:

1.  **Navigate to the correct directory:**
    - For the Options API version: `cd options-api-version`
    - For the Composition API version: `cd composition-api-version`
2.  **Install dependencies:** `npm install`
3.  **Run the development server:** `npm run dev`

When assisting with this project, be mindful of which version the user is working on. The core logic is the same, but the implementation details will differ significantly between the two versions. Always check the current file path to determine the context.
