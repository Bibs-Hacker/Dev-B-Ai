# DEV BRIAN AI

A futuristic personal AI web application powered by the OpenAI Responses API.

## Included
- Cinematic animated splash screen
- OpenAI streaming chat
- Server-side API key protection
- Optional OpenAI web search tool
- OpenAI image generation endpoint
- Local conversation history and search-style history screen
- Local memory editor
- Profile editor
- 10 themes
- 7 fonts
- Personality matrix
- Developer mode shortcuts
- File/text attachment into composer
- Browser voice input
- Export chat history as JSON
- Responsive mobile sidebar
- PWA-ready visual foundation

## Run
1. Install Node.js 20+.
2. Copy `.env.example` to `.env`.
3. Put your API key in `.env`.
4. Run `npm install`.
5. Run `npm start`.
6. Open `http://localhost:3000`.

Do not put the API key into `public/app.js` or `index.html`.

## Model
Set `OPENAI_MODEL` in `.env` to the model available to your API project. The default is `gpt-6-luna`.
