# Chess Coach

Chess game with Sherlock-style AI commentary powered by Groq.

## Deploy to Vercel

1. Push this folder to a GitHub repo
2. Go to https://vercel.com → New Project → import your repo
3. In Project Settings → Environment Variables add:
   - `GROQ_API_KEY` = your Groq API key
4. Click Deploy

## Local development

```bash
npm i -g vercel
vercel dev
```

Then open http://localhost:3000

## Structure

```
/api/chat.js       Serverless Edge function — proxies requests to Groq
/public/index.html Chess game frontend
vercel.json        Routing config
```
