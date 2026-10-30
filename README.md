# StoryForge Studio

A responsive early-access workspace for planning original stories, characters, world rules and manga/manhwa page layouts.

## Run
Requires Node.js 18+. Run `npm start` and open `http://localhost:3000`. No external packages are required.

## Current features
- Create and list story projects (genre, format, logline).
- Save character profiles and world bible notes in browser localStorage.
- Draft three-panel comic pages and save them to a selected project.
- Export a page as a text file.
- Responsive desktop/mobile layout.

## Important limitations
This is an early working foundation, not the complete planned AI product. Projects are stored only in the current browser; account sign-in and cloud sync are not implemented. AI text/image generation, a full chapter manuscript editor, image-reference management, character consistency tools, and production security/testing remain to be built. Do not add API keys to browser code. A future AI provider integration may incur usage charges.

## Render
Create a Node web service from this repository. Build command: `npm install` (no dependencies currently); start command: `npm start`.
