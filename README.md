# AI Summarizer
This is a simple project that takes the URL of the article and generates a summary using Artificial Intelligence (AI). The summaries of articles are generated using Article Extractor and Summarizer library from RapidAPI.

You can view the working project at: https://sulavaisummarizer.netlify.app/

## Tech Stack:
1. VITE: https://vitejs.dev/
2. React: https://react.dev/
3. 4. TailwindCSS: https://tailwindcss.com/
5. Rapid API: https://rapidapi.com/
6. Article Extractor and Summarizer: https://rapidapi.com/restyler/api/article-extractor-and-summarizer
4. React-Redux: https://react-redux.js.org/

## How to RUN?
Create a new environment `.env` file in the root of the project directory and add a key for Rapid API in the environment file. The environment file will look like below, replace the value for `{RAPID_API_KEY}`
```dotenv
VITE_RAPID_API_ARTICLE_KEY={RAPID_API_KEY}
```
Then run the project using the command `npm start dev` which will start the project on `http://localhost:5173/`
