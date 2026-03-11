# JMC 2033 Midterm Prep App

University of Oklahoma — School of Journalism & Mass Communication  
Spring 2026 Midterm Study App

## Deploy to Vercel

### Option 1 — Vercel CLI (fastest)
```bash
npm i -g vercel
cd jmc2033-vercel
vercel
```
Follow the prompts. Your app will be live at a `.vercel.app` URL instantly.

### Option 2 — Vercel Dashboard (no CLI needed)
1. Go to https://vercel.com/new
2. Click **"Add New Project"** → **"Import Third-Party Git Repository"**  
   — OR drag and drop this folder directly if using the Vercel dashboard uploader
3. No build settings needed — Vercel detects it as a static site automatically

### Option 3 — GitHub + Vercel (recommended for updates)
1. Push this folder to a GitHub repo
2. Go to https://vercel.com/new → Import your GitHub repo
3. Vercel auto-deploys on every push

## Project Structure
```
jmc2033-vercel/
├── index.html    ← The entire app (HTML + CSS + JS in one file)
└── vercel.json   ← Vercel routing config
```

## Features
- Flashcard mode (30 cards)
- Copyediting trainer (12 questions)
- AP vs Broadcast style quiz (14 questions)  
- Mock midterm exam (50 questions, shuffled answers)
- End-of-quiz summary showing score + missed questions
- Progress saved to localStorage
- Links to AP Stylebook, Working With Words, Canvas, OU Testing Center
