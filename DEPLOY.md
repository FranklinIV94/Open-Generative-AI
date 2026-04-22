# Vercel Deployment Guide

## Quick Deploy

1. Go to [vercel.com](https://vercel.com) → Add New Project
2. Import from GitHub: **FranklinIV94/Open-Generative-AI**
3. Vercel auto-detects Next.js — click **Deploy**
4. Once deployed, open the app and enter your Muapi API key in the settings

## Getting Your Muapi API Key

1. Go to [muapi.ai](https://muapi.ai)
2. Sign up / log in
3. Dashboard → API section
4. Copy your key

## Environment Variables (Vercel Dashboard)

After deploying, set these in Vercel → Project → Environment Variables:

| Name | Value | Notes |
|------|-------|-------|
| `MUAPI_API_KEY` | `your_key_here` | Get from muapi.ai dashboard |

## Local Development

```bash
git clone https://github.com/FranklinIV94/Open-Generative-AI.git
cd Open-Generative-AI
npm install
npm run dev
```

Then open http://localhost:3000 and enter your Muapi API key.