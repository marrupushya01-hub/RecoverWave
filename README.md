# RecoverWave

AI-powered recovery companion between doctor visits.

## Setup

1. Install dependencies
```
npm install
```

2. Create your environment file
```
cp .env.local.example .env.local
```

3. Add your Anthropic API key to `.env.local`
```
ANTHROPIC_API_KEY=sk-ant-...
```

4. Run locally
```
npm run dev
```

Open http://localhost:3000

## Deploy to Vercel

1. Push this folder to a GitHub repository
2. Go to vercel.com → New Project → Import your repo
3. Add environment variable: ANTHROPIC_API_KEY = your key
4. Click Deploy

Done. Live in 2 minutes.
