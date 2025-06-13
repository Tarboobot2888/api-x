# Web Scraping with Gemini API
Example Node.js application to demonstrate parsing exchange rates data with AI

## Setup

1. Get your `API-KEY` in [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Execute following commands:
```bash
git clone git@github.com:Sherlockboy/gemini-node-scraper.git

cd gemini-node-scraper

npm install

cp .env.example .env

npm run start
```

## Deploying to Vercel

The application exports an Express server from `server.js`. Vercel runs this file
as a serverless function automatically, so you do not need to start the server
manually. Deploy using the Vercel CLI or through the dashboard:

```bash
vercel --prod
```

For local development you can still run:

```bash
npm start
```

## Useful resources
- [Gemini REST API Docs](https://ai.google.dev/tutorials/rest_quickstart)
- [Prompt design strategies](https://ai.google.dev/docs/prompt_best_practices)
- [Available Gemini models](https://ai.google.dev/models/gemini)

## Credits

[Khurshidbek Kobilov](https://www.linkedin.com/in/khurshid-kobilov/)
